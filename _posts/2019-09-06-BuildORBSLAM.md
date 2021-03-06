---
layout: post
title: 'Building ORB-SLAM on Ubuntu 16.04 Desktop 64-bit' 
tags: ["ORB-SLAM"]

---

## 1. Install dependencies
```
#Pangolin
sudo apt-get install libglew-dev
sudo apt-get install libboost-dev libboost-thread-dev libboost-filesystem-dev
sudo apt-get install git
git clone https://github.com/stevenlovegrove/Pangolin.git
cd Pangolin
mkdir build
cd build
cmake -DCPP11_NO_BOOST=1 ..
make -j4
sudo make install
sudo ldconfig

#OpenCV 3.2.0
sudo apt-get install \
build-essential \
cmake git libgtk2.0-dev pkg-config libswscale-dev libv4l-dev \
python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev \
libxvidcore-dev libx264-dev \
ffmpeg libavcodec-dev libavformat-dev libavdevice-dev \
libatlas-base-dev gfortran \
qt5-default

wget https://github.com/opencv/opencv/archive/3.2.0.zip
wget https://github.com/opencv/opencv_contrib/archive/3.2.0.zip
sudo sudo apt-get install zip gzip tar
unzip 3.2.0.zip
unzip 3.2.0.zip.1
cd opencv-3.2.0
mkdir build
cd build
sudo cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D WITH_TBB=ON -D WITH_V4L=ON -D WITH_QT=ON -D INSTALL_C_EXAMPLES=ON  -D INSTALL_PYTHON_EXAMPLES=ON -D WITH_OPENGL=ON -D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib-3.2.0/modules .. -D WITH_LIBV4L=ON ..
sudo make -j4
sudo make install

#Eigen3
sudo apt-get install libeigen3-dev

#DBoW2
git clone https://github.com/dorian3d/DBoW2.git

#g2o
git clone https://github.com/RainerKuemmerle/g2o.git
apt-get install libblas-dev
apt-get install liblapack-dev

```

---

## Build ORB-SLAM2
```
git clone https://github.com/raulmur/ORB_SLAM2.git ORB_SLAM2
cd ORB_SLAM2
chmod +x build.sh
./build.sh
```

## Problem shooting - undefined "GetMap()"
- add `Map* GetMap() { return mpMap; };` as public member of System class in System.h (see [reference](https://github.com/raulmur/ORB_SLAM2/issues/468))

---


---
title: Image Processing 
#bigimg: /img/bgimage.png
project-list:
  - name: Canny Edge Detection
    img: ../img/canny.png
    desc: An edge detection algorithm, which includes five steps: RGB to grayscale, noise removal, edge detection, edge thinning, and connect weak edges. 
    github: https://github.com/hbyacademic/Game-Designing-PlayList/tree/master/GD_014_GomokuAPP
    youtube: https://youtu.be/txSBV9NB2jY
 
  - name: OTSU Thresholding
    img: ../img/otsu.png
    desc: An image binarization. Maximize between-class variance/Minimize within-class variance.
    github: https://github.com/hbyacademic/Game-Designing-PlayList/tree/master/GD_015_Ten10APP
    youtube: https://youtu.be/-c3Kcaj54Ik
  
  - name: 8 Bit Plane Slicing
    img: ../img/bitPlane.png
    desc: Slice grayscale image into 8 planes. 1st and 8th planes stand for low- and high-frequency signals, respectively.
    github:
    youtube:

  - name: Linear Contrast Stretching
    img: ../img/contrastStretching.png
    desc: Make low-constrast image more clear.
    github:
    youtube:

  - name: Morphological Processing
    img: ../img/morphological.png
    desc: Used to enhance features or texture of one image. Four major operations: dilation, erosion, opening (erosion then dilation), and closing (dilation then erosion).    github:
    github:
    youtube:



---
--------------------------------------

{% include clickable.html items=page.project-list %}

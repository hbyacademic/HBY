---
title: Image Processing 
#bigimg: /img/bgimage.png
project-list:
  - name: Canny Edge Detection
    img: ../img/canny.png
    desc: An edge detection algorithm. Five steps => RGB to grayscale, noise removal, edge detection, edge thinning, and connect weak edges. 
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
    github: https://youtu.be/-c3Kcaj54Ik
    youtube: https://youtu.be/-c3Kcaj54Ik

  - name: Linear Contrast Stretching
    img: ../img/contrastStretching.png
    desc: Make low-constrast image more clear.
    github: https://youtu.be/-c3Kcaj54Ik
    youtube: https://youtu.be/-c3Kcaj54Ik

  - name: Morphological Processing
    img: ../img/morphological.png
    desc: Be used to enhance features or texture of one image. Four major operations => dilation, erosion, opening (erosion then dilation), and closing (dilation then erosion). 
    github: https://youtu.be/-c3Kcaj54Ik
    youtube: https://youtu.be/-c3Kcaj54Ik

  - name: Image Scaling
    img: ../img/scaling.png
    desc: Two common techniques => nearest neighbor interpolation (NNI) and bilinear interpolation (BI).
    github:
    youtube:

  - name: XOR Encoding
    img: ../img/xorEncode.png
    desc: key XOR secret = cipher, cipher XOR key = secret
    github:
    youtube:

  - name: 
    img: ../img/xorEncode.png
    desc: Two common techniques => nearest neighbor interpolation (NNI) and bilinear interpolation (BI).
    github:
    youtube:
  
---
--------------------------------------

{% include clickable.html items=page.project-list %}

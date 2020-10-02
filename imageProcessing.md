---
title: Image Processing 
#bigimg: /img/bgimage.png
project-list:
  - name: Canny Edge Detection
    img: ../img/canny.png
    desc: An edge detection algorithm. Five steps => RGB to grayscale, noise removal, edge detection, edge thinning, and connect weak edges. 
    github: 
    youtube: https://youtu.be/PtSgA19sC5g

  - name: OTSU Thresholding
    img: ../img/otsu.png
    desc: An image binarization. Maximize between-class variance/Minimize within-class variance.
    github: 
    youtube: https://youtu.be/Ofi1Fn18YLc

  - name: 8 Bit Plane Slicing
    img: ../img/bitPlane.png
    desc: Slice grayscale image into 8 planes. 1st and 8th planes stand for low- and high-frequency signals, respectively.
    github: 
    youtube: https://youtu.be/JOpmTa4Lojs

  - name: Linear Contrast Stretching
    img: ../img/contrastStretching.png
    desc: Make low-constrast image more clear.
    github: 
    youtube: https://youtu.be/R25DMf8EveI

  - name: Morphological Processing
    img: ../img/morphological.png
    desc: Be used to enhance features or texture of one image. Four major operations => dilation, erosion, opening (erosion then dilation), and closing (dilation then erosion). 
    github: 
    youtube: https://youtu.be/QbjfZVLDyuY

  - name: Image Scaling
    img: ../img/scaling.png
    desc: Two common techniques => nearest neighbor interpolation (NNI) and bilinear interpolation (BI).
    github:
    youtube: https://youtu.be/UA7Wjr4WuhA

  - name: XOR Encoding
    img: ../img/xorEncode.png
    desc: key XOR secret = cipher, cipher XOR key = secret
    github:
    youtube: https://youtu.be/YrqRk7aTj3U

  - name: Harris Corner Detector
    img: ../img/harris.png
    desc: A corner detection algorithm.
    github:
    youtube: https://youtu.be/qX4gQIsBrhE
  
  - name: Histogram Equalization
    img: ../img/histogramEqualization.png
    desc: Non-linear contrast stretching. To equally make use of all available grayscales in the dynamic range.
    github:
    youtube: https://youtu.be/W7wjEq5MYPU

  - name: Alpha Blending
    img: ../img/alpha.png
    desc: Blend two images into one resultant image by linear combination.
    github:
    youtube: https://youtu.be/SUGjYvbaX1U
  
  - name: Frosted Glass Effect
    img: ../img/glass.png
    github:
    youtube: https://youtu.be/9Mf2MDZLyPA
  
  - name: Color Splitting Glitch Effect
    img: ../img/glitch.png
    github:
    youtube: https://youtu.be/B4J5-xsocOI

  - name: Oil Painting Effect
    img: ../img/oil.png
    github:
    youtube: https://youtu.be/CqSiZV-M1HY

  - name: Ordered Dithering 
    img: ../img/order.png
    desc: An image dithering algorithm, which is characterized by noticeable crosshatch patterns in the resultant image.
    github:
    youtube: https://youtu.be/e61N6tDnfSk
 
  - name: ASCII Art 
    img: ../img/ascii.png
    desc: Use characters represent an image. Each character stands for one intensity. Thinnest character => lower intensity, boldest character => higher intensity (or thinnest => higher, boldest => lower).
    github:
    youtube: https://youtu.be/YJ9HqHbICC8

---
--------------------------------------

{% include clickable.html items=page.project-list %}

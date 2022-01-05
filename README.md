# Image_and_Video_Processing_ECE_GY_6123
Code for NYU course Image and Video Processing (ECE GY 6123)
Text Book/References: 

1.    Richard Szeliski, Computer Vision: Algorithms and Applications. (Available online:”Link“) (Cover most of the material, except sparsity-based image processing and image and video coding)
2.    (Optional) Y. Wang, J. Ostermann, and Y.Q.Zhang, Video Processing and Communications. Prentice Hall, 2002. “Link” (Reference for image and video coding, motion estimation, and stereo)
3.    (Optional) R. C. Gonzalez and R. E. Woods, Digital Image Processing, Prentice Hall, (3rd Edition) 2008. ISBN number 9780131687288. “Link” (Good reference for basic image processing, wavelet transforms and image coding).


Links to Resources (lecture notes) in Previous Offerings: 

    ECE-GY 6123 Image and Video Processing (S20)
    ECE-GY 6123 Image and Video Processing (S19)
    EL 5123 Image Processing
    EL 6123 Video Processing
    EL 6123 Image and Video Processing (S16)
    EL 6123 Image and Video Processing (S18)
    The coursera image processing course by Prof. Katsaggelos: Link (https://www.coursera.org/learn/digital)
    The image processing course at Stanford: Link (http://web.stanford.edu/class/ee368/)
    The computer vision course at U. Washington: Link (http://courses.cs.washington.edu/courses/cse576/)
    Stanford course by Feifei Li, et al: CS231n: Convolutional Neural Networks for Visual Recognition. Link to class site(http://cs231n.stanford.edu/) 
      Link to lecture videos(https://youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
      
Other Useful Links 

    Basics of Python and Its Application to Image Processing Through OpenCV: Link (https://github.com/yaowangatpoly/introml/blob/master/Basics/PythonTutorial_ACK.pdf)
        Example codes and images used in the above guide: Link(https://github.com/yaowangatpoly/introml/blob/master/Basics/PythonSampleCodes.zip)
    OpenCV: an open source package including many computer vision algorithms
    Numpy
    Scipy
    Matrix Reference Manual
    Codeacdemy : python
    Anaconda
    
Tentative Course Schedule 

    Week 1 (1/28): Course introduction. Lecture note (Updated 1/24/2021) Part 1: Image Formation and Representation: 3D to 2D projection, photometric image formation, trichromatic color representation, video format (SD, HD, UHD, HDR). Lecture note (Updated 1/24/2021). Part 2: Contrast enhancement (concept of histogram, nonlinear mapping, histogram equalization). Lecture note (Updated 1/24/2021)
     
    Tutorial on python (1/29, 9:30 AM-11:00 AM). Materials (Updated 1/26/2021)
     
    Computer assignment 1 (Learning Python and histogram equalization) (Due 2/11)
     
    Week 2 (2/4): Review of 1D Fourier transform and convolution. Concept of spatial frequency. Continuous and Discrete Space 2D Fourier transform. Lecture note: “FT.pdf” (updated 2/1/2021)  2D convolution and its interpretation in frequency domain. Implementation of 2D convolution. Separable filters. Frequency response.Lecture note: “convolution.pdf” (updated 2/1/2021) Linear filtering (2D convolution) for noise removal, image sharpening, and edge detection. Gaussian filters, DOG and LOG filters as image gradient operators. Lecture note: “filtering_edge detection.pdf” (updated 2/1/2021)
     
    Computer assignment 2 (2D filtering) (Due 2/25)
     
    Week 3 (2/11): Image sampling and resizing. Antialiasing and interpolation filters. Spatial and temporal resolutions  of human visual systems.   Lecture note on ImageSampling (updated 2/7/21). Reference materials (updated 2/15/19):  Selesnick_MultirateSystems, Selesnick_SamplingTheorem
     
    2/18 Monday schedule. No class
     
    Week 4 (2/25):  Multi-resolution representation: Pyramid and Wavelet Transforms.     Lecture note on Wavelet (updated 2/20/2021).
     
    Programming assignment 3 (Pyramids and wavelet transforms) (Due 3/11)
     
    Week 5 (3/4): Overview of machine learning, neural networks, convolutional networks. Convolutional Network for classification. Training and validation. Lecture note on CNN (updated 2/28/2021)
     
    Week 6 (3/11): Convolutional Networks for Image Processing, including segmentation, denoising, object detection. part2 (updated 3/7/2021)
     
    Tutorial on using PyTorch and Google Cloud Platform for deep learning (3/12, 9:30AM-11:00AM) Materials (updated 3/11/2021)
     
    Programming assignment 4 (Training a U-Net for image segmentation) (Due 4/8)
     
    Week 7: Must have formed a project team and had ideas of what project will you do. Must schedule an individual meeting with the instructor to discuss your project ideas. 
     
    Week 7 (3/18): Feature detection (Harris corner, scale space, SIFT), feature descriptors (SIFT). Bag of Visual Word representation for image classification.  Lecture note on Features  (updated 3/17/2021)
     
    Week 8 (3/25): Geometric mapping (affine, homography), Feature based camera motion estimation (RANSAC). Image warping. Image registration. Panoramic view stitching.  Lecture note (updated 3/24/2021)
     
    Week 8 (3/25): Project proposal due (You should prepare the proposal following the format described in project guideline. You should have read a couple of reference papers and a detailed milestone chart and partition of project roles among the project team members).
     
    Programming assignment 5 (Due 4/29): Stitching a panoramic picture (Feature detection, finding global mapping, warping, combining).
     
    Week 9 (4/1): Dense motion/displacement estimation: optical flow equation, optical flow estimation (Lucas-Kanade method, KLT tracker); block matching, multi-resolution estimation. Deformable registration (medical applications). Deep learning approach. Lecture note. (updated 3/31/2021)
     
    Week 10 (4/8): Moving object detection (background/foreground separation). Global camera motion estimation from optical flows. Video stabilization. Video scene change detection.  Lecture note. (updated 4/7/2021)
     
    Week 11 (4/15): Image representation using orthonormal transform and dictionary. DCT and KLT; Transform-based image coding. Lecture note on transform (updated 4/14/2021)
     
    Week 12 (4/22): Video Coding Part 1: block-based motion-compensated prediction and interpolation, adaptive spatial prediction, block-based hybrid video coding, rate-distortion optimized mode selection, rate control, Group of pictures (GoP) structure, the tradeoff between coding efficiency, delay, and complexity. Lecture note (updated 4/19/2021) 
     
    Week 13 (4/29): Video Coding Part 2: Overview of video coding standards (AVC/H.264, HEVC/H.265); Layered video coding: general concept and H.264/SVC. Multiview video compression. Lecture note (updated 4/29/2021)
     
    Programming assignment 6 (Due 5/17): Video Coding
     
    5/2 (Sunday): Exam 9 AM-11:40 AM (including all material in Weeks 1-12)
     
    Week 14 (5/6): Stereo and multiview video: depth from disparity, disparity estimation, view synthesis. Multiview video compression. Depth camera (Kinect). 360 video camera and view stitching.  Lecture note. (updated 5/5/2021)
     
    Week 15 (5/13): Project Presentation.
     
    5/18: Project Report and all other material must be uploaded.     
    
      


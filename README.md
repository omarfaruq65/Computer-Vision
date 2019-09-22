# Computer-Vision-CSE-6239-
Assignment of Computer Vision (CSE 6239)
1. Write a function that convolves an image with a given convolution filter function 
 [output_Image]= myImageFilter( Input_image, filter) 
 Your function should output image of the same size as that of input Image (use padding). Test your function (on attached images House1.jpg and House2.jpg) and show results on the following Kernels. <br/>
  i. Averaging Kernel (3×3 and 5×5 ) <br/>
  ii. Gaussian Kernel (σ =1, 2, 3). Use (2σ +1)×(2σ +1) as size of Kernel (You may write a separate function to generate Gaussian Kernels for different values of σ.) <br/>
  iii. Sobel Edge Operators. <br/>
  iv. Prewitt Edge Operators. 
2. Attached ‘Noisy image1’ and ‘Noisy image2’ are corrupted by salt and paper noise. Apply 5 by 5 Averaging and Median filter and show your outputs.
3. Compute gradient magnitude for attached image ‘Q3_Image’; use your own function. 
  i. Stretch the resulting magnitude (between 0 to 255) for better visualization. <br/>
  ii. Compute and show the histogram of gradient magnitude <br/>
  iii. Compute gradient orientation <br/>
  iv. Compute and show histogram of gradient orientation (angle between 0 and 2*pi) 
4. Load walk_1.jpg and walk_2.jpg images in openCV. Convert them to gray scale and subtract walk_2.jpg from walk_1.jpg. What is the result? Why? Deliverables: 
<br/>
1. Report including Input and Output images (Soft Copy) <br/>
2. Code (Soft copy).


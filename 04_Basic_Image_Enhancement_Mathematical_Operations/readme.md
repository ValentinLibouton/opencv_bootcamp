# 4. Basic image enhancement mathematical operations
[Notebook](https://colab.research.google.com/drive/1ltqgOcv_aoYoxQ_5E-kFyXGf6KqSOwrg)<br>
[Video](https://www.youtube.com/watch?v=L7709jlgASk)

1. The range of pixel values in the output image when using `cv2.add()` to add two grayscale images? (Assume both the images have same data type)
- [ ] 0 to 127
- [ ] 0 to 255
- [ ] 128 to 255
- [x] It depends on the values of the input images

2. Which of the following is an example of an application where `cv2.multiply()` can be used?
- [ ] Detecting and tracking objects in a video stream
- [x] Enhancing the visibility of hidden features in medical images
- [ ] Creating a panoramic image from multiple images
- [ ] None of the above 

3. When `cv2.threshold()` function is applied to a grayscale image with a threshold value of 127 and maximum value of 255, then:<br>
*Hint: Assume **THRESH_BINARY** being applied in the process.*
- [ ] Pixels with intensity less than 127 are set to 0, and pixels with intensity greater than or equal to 127 are set to 255.
- [x] Pixels with intensity less than or equal to 127 are set to 0, and pixels with intensity greater than 127 are set to 255.
- [ ] Pixels with intensity greater than 127 are set to 0, and pixels with intensity less than or equal to 127 are set to 255.
- [ ] Pixels with intensity greater than or equal to 127 are set to 0, and pixels with intensity less than 127 are set to 255

4. Given 2 inputs:<br>
Input 1:<br>
111<br>100<br>000<br>
Input 2:<br>
110<br>110<br>100<br>
The output of the **bitwise AND** operation on the above binary inputs is:

- [x] [[110][100][000]]
- [ ] [[111][100][100]]
- [ ] [[110][110][000]]
- [ ] [[000][000][000]]



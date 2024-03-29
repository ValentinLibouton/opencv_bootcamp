# 1. Getting started with images
[Notebook](https://colab.research.google.com/drive/1qH55jpAaSTyWgsrrlv96-76eCiVbJQkF)<br>
[Video](https://www.youtube.com/watch?v=6mVOmFk3M_E)<br>

##  Quiz
1. What happens if the filename specified in `cv2.imwrite` already exists?
- [ ] An error is raised
- [x] The existing file is overwritten
- [ ] A new file is created
- [ ] None of the above

2. What type of errors can occur when using `cv2.imread`?
- [ ] File not found error
- [ ] Unsupported image format error
- [ ] Permission denied error
- [x] All of the above

3. What is the difference between `cv2.IMREAD_COLOR` and `cv2.IMREAD_GRAYSCALE`?
- [ ] `cv2.IMREAD_COLOR` reads the image as a grayscale image, while `cv2.IMREAD_GRAYSCALE` reads the image as a color image.
- [x] `cv2.IMREAD_GRAYSCALE` reads the image as a grayscale image, while `cv2.IMREAD_COLOR` reads the image as a color image.
- [ ] There is no difference between `cv2.IMREAD_COLOR` and `cv2.IMREAD_GRAYSCALE`
- [ ] None of the above

4. What is the purpose of the `cv2.cvtColor()` function?
- [x] To convert an image from one color space to another.
- [ ] To resize an image.
- [ ] To crop an image.
- [ ] To apply a filter to an image.

5. What is the return type of `plt.imshow()` of **Matplotlib**?
- [x] Matplotlib Image object
- [ ] NumPy array
- [ ] PIL Image object
- [ ] None of the above 
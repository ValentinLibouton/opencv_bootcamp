# 2. Basic image manipulations crop resize flip and modify pixels - Quiz
[Docs](https://docs.opencv.org/4.5.0/da/d54/group__imgproc__transform.html#ga5bb5a1fea74ea38e1a5445ca803ff121)
1. What is the default interpolation method used by `cv2.resize()`?
- [ ] `cv2.INTER_CUBIC`
- [x] `cv2.INTER_LINEAR`
- [ ] `cv2.INTER_NEAREST`
- [ ] `cv2.INTER_AREA`

2. What happens when the new size specified in `cv2.resize()` is larger than the original image?
- [ ] The image is cropped to fit the new size
- [ ] The image is padded with black pixels to fit the new size
- [x] The image is stretched to fit the new size
- [ ] None of the above

3. What happens when the flipCode parameter in `cv2.flip()` is set to 0?
- [x] The image is flipped vertically
- [ ] The image is flipped horizontally
- [ ] The image is flipped both horizontally and vertically
- [ ] The image is not flipped 
4. What is the purpose of the interpolation method parameter in `cv2.resize()` ?
- [ ] To specify the output size of the image
- [ ] To specify the scaling factor of the image
- [x] To specify the interpolation algorithm used to resize the image
- [ ] To specify the color space of the output image
- 
5. What is an example of an application where cropping an image using array slicing in OpenCV is useful?
- [ ] Extracting a region of interest from an image
- [ ] Removing unwanted borders or margins from an image
- [x] All of the above
- [ ] None of the above. 

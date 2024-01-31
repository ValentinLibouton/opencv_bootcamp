# 10. HDR
[Notebook](https://colab.research.google.com/drive/18j1GSuLeY8Xx13Ar5mtvH1F7M82kTsPU)<br>
[Video](https://www.youtube.com/watch?v=8lCnY7Kj2Kw)<br>
[Docs: `cv::AlignMTB`](https://docs.opencv.org/3.4/d7/db6/classcv_1_1AlignMTB.html)<br>
[Docs: `cv::Tonemap`](https://docs.opencv.org/3.4/d8/d5e/classcv_1_1Tonemap.html#details)<br>
[Docs: `cv::TonemapReinhard`](https://docs.opencv.org/4.x/d0/dec/classcv_1_1TonemapReinhard.html)<br>
[Docs: `cv::MergeDebevec`](https://docs.opencv.org/4.x/df/d62/classcv_1_1MergeDebevec.html)<br>

## Quiz
1. The purpose of `cv2.createAlignMTB` is:
- [ ] To create a multi-threaded image blending object for stitching images
- [ ] To create a camera calibration object for determining camera parameters
- [x] To create an object for aligning images based on brightness differences
- [ ] To create an object for color correction and white balancing of images

2. What is the purpose of the tone mapping process?
- [ ] To adjust the brightness and contrast of the HDR image
- [x] To reduce the dynamic range of the HDR image for display on a low dynamic range monitor
- [ ] To sharpen the edges and details of the HDR image
- [ ] To convert the HDR image to a grayscale format 

3. What are the applications of Reinhard's global tone mapping?
- [ ] Photography and videography
- [ ] Medical imaging and microscopy
- [ ] Computer graphics and visualization
- [x] All of the above 

4. Which OpenCV function is used to merge exposures into an HDR image?
- [ ] `cv2.merge()`
- [ ] `cv2.cvtColor()`
- [ ] `cv2.stitcher()`
- [x] `cv2.createMergeDebevec()`

5. How does `cv2.createMergeDebevec` handle over- and under-exposed pixels?
- [ ] By discarding them
- [ ] By compressing their values
- [x] By using an adaptive weighting function
- [ ] By interpolating their values

6. Which of the following is a potential issue when using `cv2.createMergeDebevec`?
- [x] Motion blur in the input images
- [ ] Overlapping regions in the input images
- [ ] Low contrast in the input images
- [ ] None of the above 
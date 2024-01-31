# 8. Image alignment
[Notebook](https://colab.research.google.com/drive/1cQqOYar7ZlPB6XRAdPHur4bLmPPdr59w)<br>
[Video](https://www.youtube.com/watch?v=_o6fSMCmNnQ)<br>
[Docs: `ORB.detectAndCompute()`](https://docs.opencv.org/3.4/d1/d89/tutorial_py_orb.html)
[Docs: `cv2.DescriptorMatcher_create()`](https://docs.opencv.org/3.4/db/d39/classcv_1_1DescriptorMatcher.html)<br>
[Docs: `cv2.getPerspectiveTransform()`](https://docs.opencv.org/3.4/da/d6e/tutorial_py_geometric_transformations.html)<br>

## Quiz
1. Which feature detection algorithm is the fastest?
- [ ] SIFT
- [ ] SURF
- [x] ORB
- [ ] All have similar speed

2. A key point in ORB feature detection is:
- [ ] A pixel in the image with high intensity
- [x] A point of interest in the image that is invariant to rotation and scale changes
- [ ] A point in the image where the gradient is high
- [ ] A point in the image where the Laplacian of Gaussian is maximum 

3. In `ORB.detectAndCompute()`, what is the role of the **mask** parameter?
- [x] It specifies a region of interest where keypoints should be detected
- [ ] It specifies the maximum number of keypoints to be detected
- [ ] It filters out keypoints that are not within the specified mask
- [ ] It has no role in `ORB.detectAndCompute()`

4. The role of `DescriptorMatcher_create` in feature matching is:
- [ ] It creates feature descriptors for the input image
- [x] It matches the feature descriptors of two images
- [ ] It removes the redundant features from an image
- [ ] It creates a binary mask for the matched features

5. Which method will be called for descriptor matching with the following code `matcher = cv2.DescriptorMatcher_create(2)` ?
- [x] Brute-Force
- [ ] Brute-Force-L1
- [ ] Brute-Force-Hamming
- [ ] FlannBased

6. The role of `cv2.getPerspectiveTransform()` in perspective transformation is:
- [x] It computes the homography matrix from the corresponding points
- [ ] It applies the homography matrix to the input image
- [ ] It specifies the region of interest in the input image
- [ ] It computes the inverse of the homography matrix 
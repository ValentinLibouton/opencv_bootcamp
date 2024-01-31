# 11. Object tracking
[Notebook](https://colab.research.google.com/drive/1zWOdwhoCR9NqeEuC-d29S0RmpWFmOgB2)<br>
[Video](https://www.youtube.com/watch?v=p6gp8CLMDOo)<br>

## Quiz
1. The Meanshift algorithm in computer vision is used for:
- [ ] Image segmentation
- [ ] Object detection
- [x] Object tracking
- [ ] Feature extraction 

2. How does the object tracking process work in OpenCV?
- [ ] The user selects the object to be tracked and the program automatically tracks it.
- [x] The program detects the object in each frame of the video sequence and updates its position accordingly.
- [ ] The program uses machine learning algorithms to identify the object in each frame of the video sequence
- [ ] The program uses a pre-trained neural network to track the object in the video sequence 

3. Which of the following is an advantage of using a pre-built tracker in OpenCV?
- [x] It is faster than implementing a custom tracker
- [ ] It is more accurate than implementing a custom tracker
- [ ] It allows for more customization than implementing a custom tracker
- [ ] None of the above

4. Which OpenCV function is commonly used to measure the FPS(Frame per second)?
- [ ] `cv2.VideoCapture()`
- [ ] `cv2.imshow()`
- [x] `cv2.getTickCount()`
- [ ] `cv2.waitKey() `

5. What is the recommended FPS for real-time computer vision applications?
- [ ] 10-15 FPS
- [ ] 30 FPS
- [ ] 60 FPS
- [x] There is no recommended FPS and it depends on the specific application 
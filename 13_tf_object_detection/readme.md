# 13. Tensorflow object detection
[Notebook](https://colab.research.google.com/drive/1OiyJNXnIow-tXfj_ZhnjMNOFC96d8iEe)<br>
[Video](https://www.youtube.com/watch?v=9V2qPmWTfaY)<br>
[Docs: `cv::dnn::blobFromImages`](https://docs.opencv.org/3.4/d6/d0f/group__dnn.html#ga2b89ed84432e4395f5a1412c2926293c)<br>
## Quiz
1. What is a TensorFlow model?
- [ ] A dataset used for training machine learning models.
- [ ] A set of rules that a machine learning model uses to make predictions.
- [ ] A software library for developing and training machine learning models.
- [x] A machine learning model that has been trained on a specific task. 

2. The benefits of using TensorFlow is/are:
- [ ] Scalability and performance
- [ ] Flexibility and ease of use
- [ ] Wide range of supported platforms and languages
- [x] All of the above

3. What is the default order of the channels in the output of `cv2.dnn.blobFromImage` function?
- [ ] RGB
- [x] BGR
- [ ] GRB
- [ ] BRG 

4. What is the purpose of the `crop=false` parameter in `cv2.dnn.blobFromImage` function?
- [ ] To crop the image to the specified size
- [x] To resize the image to the specified size
- [ ] To perform center cropping of the image
- [ ] To perform random cropping of the image

5. How does the Meanshift algorithm work in object tracking?
- [ ] It uses machine learning to detect objects in a video sequence
- [x] It uses a histogram-based approach to track the object's position in each frame of the video sequence
- [ ] It uses a pre-trained neural network to track the object in the video sequence
- [ ] It detects the object in the first frame of the video sequence and then tracks it in subsequent frames 
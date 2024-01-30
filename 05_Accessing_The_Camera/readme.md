# 5. Accessing the camera
[Video](https://colab.research.google.com/drive/1ltqgOcv_aoYoxQ_5E-kFyXGf6KqSOwrg)

1. What is the correct way to release the resources used by `cv2.VideoCapture()` when done with the webcam?
- [x] cap.release()
- [ ] cap.end()
- [ ] cap.close()
- [ ] None of the above.

2. What is the recommended way to handle errors when using `cv2.VideoCapture()` with a webcam?
- [x] Use try and except blocks to catch errors
- [ ] Ignore errors and continue running the program
- [ ] Restart the webcam if an error occurs
- [ ] None of the above

3. What is the purpose of `cv2.waitKey(1) != 27` in OpenCV?
- [ ] To pause the execution of the program until a key is pressed
- [ ] To wait for 1 millisecond before executing the next frame
- [x] To check if the Esc key has been pressed correct
- [ ] To check if the Enter key has been pressed


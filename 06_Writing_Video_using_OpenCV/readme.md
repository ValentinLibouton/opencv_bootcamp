# 6. Writing video using openCV
[Notebook](https://colab.research.google.com/drive/1g0YaxF4qLnzPY1VQBK2APsmO-H7QQXSw)<br>
[Video](https://www.youtube.com/watch?v=phjICOhF8EM)
## Notes
`cv2.VideoWriter_fourcc(*'XVID')` doesn't work for me. I have to use ***'avc1'** or ***'mp4v'**

For the two pieces of code below, you need to open the Notebook from a web browser and not from the IDE environment.
```python
mp4 = open("race_car_out_x264.mp4", "rb").read()
data_url = "data:video/mp4;base64," + b64encode(mp4).decode()

HTML(f"""<video width=700 controls><source src="{data_url}" type="video/mp4"></video>""")
```

```python
video = YouTubeVideo("2Gju7YLfkP0", width=700, height=438)
display(video)
```

## Quiz
1. `VideoWriter` in OpenCV is used to:
- [ ] To capture video from a webcam
- [ ] To play video files
- [ ] To write frames to a video file
- [ ] To read frames from a video file

2. How can you check if `cap.read()` was successful (Here: `cap = cv2.VideoCapture()`)
- [ ] By checking the value of the `isOpened()` function.
- [ ] By checking the value of the `capOpened()` variable
- [ ] By checking the return value of the function `cap.read()`
- [ ] None of the above 

3. The importance of checking `cap.isOpened()` in an OpenCV program:
- [ ] It ensures that the video file is opened successfully before reading or writing it.
- [ ] It helps in detecting any errors or issues with the VideoCapture object.
- [ ] Both a and b
- [ ] None of the above

4. How can you handle errors that may occur when using `cap.read()`?
- [ ] By checking the return value of the function and handling any errors accordingly.
- [ ] By using a try-except block to catch any exceptions that may be raised.
- [ ] By using the isOpened() function to check if the video capture object is still open before calling cap.read()
- [ ] All of the above

5. What does fourcc mean in `cv2.VideoWriter()`?
- [ ] It refers to the four-character code used to specify the codec to be used for video compression
- [ ] It is a parameter to set the frame rate of the output video
- [ ] It is the size of the video frame in pixels
- [ ] It is the file extension of the output video file 


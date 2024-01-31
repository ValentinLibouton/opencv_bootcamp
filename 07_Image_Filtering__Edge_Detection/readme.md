# 7. Image filterging (Edge Detection)

[Video](https://www.youtube.com/watch?v=dgZ8ejWfNOg)

## Notes
Replace
 ```python
for x, y in numpy.float32(corners).reshape(-1, 2):
    cv2.circle(result, (x, y), 10, (0, 255, 0), 1)
```
With
 ```python
for x, y in numpy.float32(corners).reshape(-1, 2):
    cv2.circle(result, (int(x), int(y)), 10, (0, 255, 0), 1)
```
Because, error code:
```python
cv2.circle(result, (x, y), 10, (0, 255, 0), 1)
cv2.error: OpenCV(4.6.0) :-1: error: (-5:Bad argument) in function 'circle'
> Overload resolution failed:
>  - Can't parse 'center'. Sequence item with index 0 has a wrong type
>  - Can't parse 'center'. Sequence item with index 0 has a wrong type
```

## Quiz
1. Which of the following is not a blurring filter in OpenCV?
- [ ] Median Filter
- [ ] Gaussian Filter
- [ ] Bilateral Filter
- [x] Canny Filter

2. Which of the following is true about the Bilateral Filter in OpenCV?
- [ ] It only blurs the edges in an image
- [x] It can blur the edges and smooth the textures in an image
- [ ] It can only be applied to grayscale images
- [ ] It is faster than other blurring filters in OpenCV 

3. In which field can the Canny Edge Detector be used?
- [ ] Medical Imaging
- [ ] Robotics
- [ ] Computer Vision
- [x] All of the above

4. How does `cv2.goodFeaturesToTrack` detect corners?
- [ ] It looks for areas with high gradient magnitude in the image
- [ ] It applies a threshold to the image and detects local maxima in the resulting binary image
- [x] It looks for areas where the structure tensor has a small eigenvalue
- [ ] It applies a Laplacian of Gaussian filter to the image and detects zero-crossings 

5. What is the function of cv2.blur() in OpenCV?
- [ ] It applies a Gaussian blur to an image.
- [ ] It applies a median blur to an image.
- [x] It applies an average blurring filter to an image.
- [ ] It applies a bilateral filter for edge-preserving and noise-reducing image smoothing. 
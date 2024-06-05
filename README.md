# Multimedia-Final-Project Traditional Method
code is in traditional.ipynb  
this code uses Otsu's method to determine the threshold based on the histogram: https://zh.wikipedia.org/zh-tw/%E5%A4%A7%E6%B4%A5%E7%AE%97%E6%B3%95
### variables can adjust
- scaleFactor: magnification multiplier
- interpolation method: cv2.INTER_NEAREST, cv2.INTER_LINEAR, cv2.INTER_CUBIC, cv2.INTER_LANCZOS4, or any methods from scratch
- invert: need to invert if the object is darker than the background
- remember to change the input and output path

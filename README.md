<h1 align="center" id="title">Color Conversion in OpenCV</h1>

## Overview
This Python script demonstrates color conversion using OpenCV, a popular computer vision library. The code reads an image, performs different color conversions, and visualizes the results using Matplotlib.

## Code Explanation

*   `cv2.imread('28.jpg')`: Reads the image '28.jpg' using OpenCV.

*   `cv2.COLOR_BGR2RGB`: Converts BGR to RGB. The original image is in BGR format, commonly used by OpenCV.

*   `cv2.COLOR_BGR2GRAY`: Converts BGR to grayscale. The resulting image will be in shades of gray.

*   `cv2.COLOR_RGB2BGR`: Converts RGB to BGR. This is useful when working with libraries that expect images in BGR format.

*   `cv2.cvtColor(img, cv2.COLOR_BGR2RGB)`: Applies the BGR to RGB conversion to the original image.

*   `cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)`: Converts the original image to grayscale.

*   `cv2.cvtColor(img, cv2.COLOR_RGB2BGR)`: Converts the original RGB image to BGR.

*   `plt.imshow(img_rgb), plt.imshow(img_rgb1), plt.imshow(img_rgb2)`: Displays the three converted images using Matplotlib.



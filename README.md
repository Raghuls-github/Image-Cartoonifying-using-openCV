# Image-Cartoonifying-using-openCV
This module converts a normal image into cartoon images using opencv.

## Process

- Step 1: Converts the original image into grayscale images using BGR2GRAY Flag.
    - For every transformation the image is being resized.
    
- Step 2: The grayscale image is smoothend using the medianblur() function. In this method the center pixel is assigned a mean value and other fall under the kernal.

- Step 3: Using the adptive thresholding technique the edges of the images are retrived. 
    - (The threshold value is the mean of the neighborhood pixel value area minus the constant 'C')
    

- Step 4: Now the image is lightend and masked with the retrived edges.

- Step 5: Finally, we get the cartoonified image.

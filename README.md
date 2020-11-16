## Invisibility_cloak
A small project on image processing. Have fun with it and enjoy it.

## Requirements   

> #### Python3   
> #### WebCam / Test Video     
> #### Red color cloth
> #### Libraries : 
> - OpenCV (pip install opencv-python)
> - Numpy (pip install numpy)
> - time

## Instructions    

If you wish to use this with your web cam, change Line 5 to `cap = cv2.VideoCapture(0)`
Or if you wish to use it with a pre-recorded video, change it to `cap = cv2.VideoCapture('video_path')` and enter your video path in 'quotes'.    

This needs to capture the background before it can actually work, so you need to let it capture the Background for atleast 2 seconds before coming into the picture.

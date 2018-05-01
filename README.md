# AutoBackup-IoT
An alarm system to alarm a user if he/she leaves without his IoT device.
This part of the code is for the IoT part where response to request made by the server.
 - Read gyro sensor's data and returns 0 (not moving) or 1 (moving)

-----------------------------------------------------------------------

The rest of this information is meant for IoT Server part. But this part of the code is lost so only my instructions are left.
1. Install OpenCV 3 on Raspbian Jessie
- https://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/

2. Access raspberry pi camera with opencv and python
- https://www.pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/

3. Increase raspberry pi FPS (not necessary though)
- https://www.pyimagesearch.com/2015/12/28/increasing-raspberry-pi-fps-with-python-and-opencv/

4. Face recognition with python
https://realpython.com/blog/python/face-recognition-with-python/

5. Face detection Raspberry WebCam.
https://realpython.com/blog/python/face-detection-in-python-using-a-webcam/

6. Combine step 5 and step 2 so that it works for raspberry cam + change "cv2.cv.CV_HAAR_SCALE_IMAGE" to "cv2.CASCADE_SCALE_IMAGE"



Creating Server
0. Create file named main.js
1. npm init (so that I can get npm created by others)
2. npm install express -- save, npm install supervisor -g, npm install python-shell, body-parser, request

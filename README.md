## Python Phone Camera

Intall following modules
```
pip install opencv-python
pip install requests
pip install imutils
```
- Download and install IP Webcam application (https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en) on your mobile phone.

- Then make sure your PC and Phone both are connected to the same network. Open your IP Webcam application on your both, click “Start Server” (usually found at the bottom). This will open a camera on your Phone.

- A URL is being displayed on the Phone screen, type the same URL on your PC browser, and under “Video renderer” Section, click on “Javascript”.

![alt text](https://s3.ap-southeast-1.amazonaws.com/upload.nasir.id/phone-camera.jpg)

- You can see video captured on your phone, which starts showing up on your browser. Now, what we will be going to do is, taking image data from the URL using the request module and convert this to an image frame using NumPy, and finally, start using our Android camera as a webcam in Python.

- In the code:
   - Import module
   - Add URL displayed in your phone
   - Continuous fetch data from URL
   - Keep displaying this data collected
   - Close window



# Hand-Gesture-Volume-Control
By using a webcam, the program captures real-time video frames. It then applies the hand tracking algorithm provided by Mediapipe to detect and track the landmarks of the hand in the video stream. The landmarks correspond to specific points on the hand, such as the fingertips.

The program identifies two landmarks: one on the index finger (id=8) and one on the thumb (id=4). By calculating the distance between these two landmarks, it estimates the distance between the fingertips. Based on this distance, it determines whether to increase or decrease the volume.

When the distance is greater than a threshold value, it triggers the pyautogui.press("volumeup") command to increase the volume. Conversely, when the distance is smaller than the threshold, it triggers the pyautogui.press("volumedown") command to decrease the volume.


# To install the required libraries, you can use the following commands:

## For OpenCV (cv2)
pip install opencv-python
## For Mediapipe
pip install mediapipe 
## For PyAutoGUI
pip install pyautogui



#
#
![image](https://github.com/Divyagaikwadd/Hand-Gesture-Volume-Control/assets/99081628/8882d4b1-c0c5-4217-9183-ff785a56ad79)
#
#
#
#
![image](https://github.com/Divyagaikwadd/Hand-Gesture-Volume-Control/assets/99081628/a72f191a-e0fe-45e6-95a8-98ea8da75c73)


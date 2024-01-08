Dynamic Hand-Guided Image Insertion<br>
This Python script provides a solution for dynamically inserting an image into videos with real-time occlusion handling, guided by hand movements. The code utilizes the MediaPipe library for hand tracking and provides a customizable approach to handle occlusions.
<br>
Features:<br>
Real-time Hand Tracking: Utilizes the MediaPipe Hands library for tracking hand landmarks in each video frame.<br>
Dynamic Image Insertion: Inserts an image into the video based on hand movements, providing a dynamic and interactive visual experience.<br>
Occlusion Handling: Addresses occlusion challenges by adjusting the image position when the hand is above a specified level, ensuring the image remains visible.<br>
Customization:<br>
Base Hand Level: Set the base level for hand detection, controlling when the image starts moving.<br>
Image Scale: Adjust the size of the inserted image relative to the video frame.<br>
Initial Image Position: Define the initial position of the image in the top-left corner.<br>
Dependencies:<br>
OpenCV (cv2)<br>
NumPy (numpy)<br>
MediaPipe (mediapipe)<br>
Usage:<br>
Install the required dependencies: pip install opencv-python numpy mediapipe.<br>
Replace the video_path, image_path, and output_path variables with your video file, image file, and desired output path.<br>
Optionally, customize the script by adjusting parameters such as base_hand_level, image_scale, and initial position.<br>

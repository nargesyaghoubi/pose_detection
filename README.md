# Pose Detection using MediaPipe Model with Kalman & Butterworth Filters
This project performs human pose detection in video streams using the MediaPipe Pose model. The detected landmarks are refined with Kalman and Butterworth filters to reduce noise, resulting in smoother and more accurate visualization of body movements.
## Output

<p align="center">
  <img src="https://github.com/nargesyaghoubi/pose_detection/blob/main/video/pose.gif" />
</p>


 ## Features
✔️ Detects body landmarks from video using MediaPipe Pose
✔️ Applies Kalman and Butterworth filters for smoother and more stable tracking
✔️ Handles high-speed videos with reliable pose detection
✔️ Draws pose skeleton with customizable colors
✔️ Outputs a refined video with accurate pose visualization

## Usage
1. Clone the repository:
```
git clone https://github.com/nargesyaghoubi/pose_detection
```

2. Install required libraries:
```
pip install -r requirements.txt
```



## Notes

- The script uses MediaPipe's Pose model for detecting landmarks.
- If you want real-time pose detection from a webcam, replace ``` cap = cv2.VideoCapture("yoga_pose.mp4") ``` with ``` cap = cv2.VideoCapture(0) ```.


## License  
This project is licensed under the MIT License . see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact:
- nargersyaghoubi2001@gmail.com
## Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/narges-yaghoubi-656a28243/)

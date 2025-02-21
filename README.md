# Pose Detection With MediaPipe

This project detects human poses in a  video using **MediaPipe Pose** and **OpenCV**. It processes each frame, detects key landmarks, and visualizes body movements.
## Output

<p align="center">
  <img src="https://github.com/nargesyaghoubi/pose_detection/blob/main/video/pose.gif" />
</p>


 ## Features
✔️ Processes video frames to detect body landmarks  
✔️ Draws pose connections with customizable colors  
✔️ Displays the processed video with detected poses  

## Usage
1. Clone the repo
```
$ git clone https://github.com/nargesyaghoubi/pose_detection
```

2. Install required libraries
```
$ pip install -r requirements.txt
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
### Narges Yaghoubi
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/narges-yaghoubi-656a28243/)

# 🚗 Real-Time Object Detection and Tracking

This project performs real-time object detection and tracking using OpenCV. The application detects moving objects in a video and tracks them, assigning unique IDs to each detected object.

## 📁 Files

- **'highway.mp4'**: Input video file for object detection 🎥
- **'tracker.py'**: Contains the EuclideanDistTracker class for object tracking 🔄
- **'main.py'**: Main script for object detection and tracking 🚀

You can install OpenCV using pip:

```bash
pip install opencv-python
```

## 📜 How It Works

**Object Detection**:
- Uses a background subtraction method (cv2.createBackgroundSubtractorMOG2) to detect moving objects. 🕵️‍♂️
- Applies a binary threshold and finds contours to identify objects. 📊
  
**Object Tracking**:
- Utilizes the EuclideanDistTracker class to assign and update unique IDs for each detected object. 🆔
- Tracks objects based on their center points and Euclidean distance. 📍
  
**Visualization**:
- Displays the region of interest (ROI), the original video frame, and the binary mask. 📺
- Draws bounding boxes and IDs around detected objects in the ROI. ✏️


**Run the script:**

```bash
python main.py
```

**Stop the program:**

Press Esc to stop the video and exit the application. 🚪

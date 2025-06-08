# 🎥 Detection Summary Engine
This repository contains the solution for "Detection Summary Engine", a project designed to analyze video streams using a pre-trained object detection model (YOLO). It processes video frames, extracts detailed detection information, summarizes object occurrences, and visualizes key insights.

### ✨ Features
* Object Detection: Utilizes a pre-trained YOLO model (defaulting to YOLOv8n) to detect objects within video frames.
* Frame Processing: Processes every 5th frame of a given .mp4 video (optimized for 15-20 second clips).
* Detailed Per-Frame Output: Generates a JSON output for each processed frame, including:
    - Class labels of detected objects
    - Bounding box coordinates
    - Confidence scores
* Object Counting: Counts the total occurrences of each detected object class across the entire video.
* Class Diversity Analysis: Identifies the specific video frame that exhibits the maximum diversity of object classes.
* Frequency Visualization: Creates a bar chart to visualize the overall frequency of each detected object class.

### Dataset Used: <a href="viratdata.org">viratdata.org</a>

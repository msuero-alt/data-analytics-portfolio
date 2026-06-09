Basketball Trajectory Reconstruction ML Pipeline
Computer vision system for trajectory extraction and physics-based motion reconstruction
This project demonstrates an end-to-end computer vision data pipeline that transforms unstructured video into structured, time-series motion data for downstream analysis and physics-based modeling.
Demo: https://youtube.com/watch?v=luLLZKf26uw
 GitHub: https://github.com/msuero-alt/basketball-shot-trajectory

1

Input video is processed frame-by-frame using a YOLOv8 object detection model 
Ball coordinates are extracted from detections and structured into a time-series sequence 


Technologies: Python, OpenCV, YOLOv8, NumPy, Matplotlib
Detection & Tracking Pipeline 
2
The system logs frame-level detections and transitions from active tracking to predictive modeling once sufficient motion data is collected.

System Pipeline Overview 
3
End-to-end machine learning pipeline combining vision-based detection with physics-based trajectory reconstruction. 


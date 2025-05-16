# 🎯 Lucas-Kanade Motion Tracking

This project implements the **Lucas-Kanade optical flow algorithm** to track motion between two or more consecutive frames in a video. It's a cornerstone method in computer vision, widely used for motion estimation, object tracking, and visual odometry.



## 📌 What is Lucas-Kanade?

The **Lucas-Kanade method** is a differential method for optical flow estimation. It assumes that:
- Motion between two frames is small and constant within a neighborhood.
- The brightness of a point does not change between frames.

It calculates the flow vector (displacement) for key points by solving a set of linear equations using image gradients.



## 🧠 Applications

- Object tracking in video streams
- Camera motion estimation
- Gesture recognition
- Augmented reality overlays
- Autonomous vehicle navigation


## 🛠️ Requirements

If you're using Python + OpenCV:

```bash
pip install opencv-python numpy

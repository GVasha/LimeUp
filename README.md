# LimeUp Project for Hackathon

## Introduction

The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match.

We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered.

This project covers various concepts and addresses real-world problems. In the future, we will be able to calculate how many passes have been completed, goal shots, goal kicks, corners, free kicks, and more.

## Programs Used

The following modules are used in this project:

- **YOLO**: AI object detection model
- **Kmeans**: Pixel segmentation and clustering to detect t-shirt color
- **Optical Flow**: Measure camera movement
- **Perspective Transformation**: Represent scene depth and perspective
- **Speed and Distance Calculation**: Measure speed and distance covered per player

## Trained Models

- [Trained Yolo v5](https://drive.google.com/file/d/1r3pbOQtkixsVNzqJccpOO3seRRdOnWcu/view?usp=sharing)

## Sample Video

- [Sample Input Video](https://drive.google.com/file/d/1x3ugIf9m-TMEek9qPMeI-xn_OSZK-d1J/view?usp=sharing)

## Requirements

To run this project, you need to have the following requirements installed:

- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

## Additional Information

- **YouTube Video**: [Project Overview](https://youtu.be/fSbtjn_Qp0E)
- **LimeUp Website**: [LimeUp](https://limeup.co/) (not finished yet)


# Image Recognition
Stack for image recognition packages based on ROS2.

<div align="center">
  
[![Build and Test](https://github.com/mjlee111/image_recognition/actions/workflows/colcon.yml/badge.svg)](https://github.com/mjlee111/image_recognition/actions/workflows/colcon.yml)
</div>

## Overview
This repository provides a set of packages designed for image recognition and camera control using ROS2. Each package is designed with a focus on modularity, lifecycle management, and real-time control over image streams.

## Requirements
To use the packages in this repository, make sure you have the following installed:

- **OpenCV**: Version **4.2** or higher  
  Required for image processing and camera interfacing.
  
- **V4L2 (Video4Linux2)**:  
  Linux-based video capture and output library, necessary for interfacing with USB cameras.

- **ROS2**:  
  ROS2 distribution, such as **Foxy** or **Humble**, is recommended.

## Development Environment

| Component   | Version          |
|-------------|------------------|
| **OS**      | Ubuntu 20.04     |
| **ROS**     | Foxy Fitzroy     |
| **OpenCV**  | 4.5.2            |


## Packages
<div align="center">

| Category          | Package              | Description                                                         | Documentation                                        |
|-------------------|----------------------|---------------------------------------------------------------------|-----------------------------------------------------|
| Camera Nodes      | `usb_camera`          | V4L2 USB Camera Node with lifecycle management.                     | [Link to docs](usb_camera/README.md)                |
| Image Projection  | `pan_tilt_camera`     | Advanced V4L2 USB Camera Node with lifecycle management and pan-tilt control via ROS topics. | [Link to docs](image_projection/pan_tilt_camera/README.md) |
| Image Recognition  | `yolov8_detection`    | Real-time image recognition using YOLOv8, with GPU support and dynamic parameter configuration. | [Link to docs](image_recognition/yolov8_detection/README.md)          |


</div>

## Contributing
I welcome all contributions! Whether it's bug reports, feature suggestions, or pull requests, your input helps me to improve. If you're interested in contributing, please check out my contributing guidelines or submit an issue.

## License
This project is licensed under the [Apache 2.0 License](LICENSE). Feel free to use and distribute it according to the terms of the license.

## Contact
If you have any questions or feedback, don't hesitate to reach out! You can contact us at [menggu1234@naver.com][email].

[email]: mailto:menggu1234@naver.com

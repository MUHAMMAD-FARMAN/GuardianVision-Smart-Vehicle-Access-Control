# GuardianVision Smart Vehicle Access Control

GuardianVision is a smart vehicle access control system designed to detect vehicles and individuals, allowing security personnel to monitor and manage access to restricted areas in real-time. With just a click, users can restrict access beyond specified boundaries and receive alerts when unauthorized access is detected.🚨🛡️

## Installation

Ensure you have the required packages installed:

```bash
pip install opencv-python==4.8.1
pip install ultralytics==8.2.2
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/MUHAMMAD-FARMAN/GuardianVision-Smart-Vehicle-Access-Control.git
cd GuardianVision-Smart-Vehicle-Access-Control
```

2. Run main.ipynb using jupyter notebook
## Configuration

### Line Configuration

Modify the following variables in the code to adjust the line position:

```python
# Define the start and end points of the line (x, y)
start_point = (1000, 0)
end_point = (1000, 720)
```

## Features

- Real-time detection and tracking of vehicles and individuals.
- Click-based access restriction beyond specified boundaries.
- Alarm notification upon unauthorized access.

## Dependencies

- [OpenCV](https://github.com/opencv/opencv-python) - Wrapper package for OpenCV Python bindings.
- [Ultralytics](https://docs.ultralytics.com/) - YOLOv8 for object detection and multi-object tracking

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

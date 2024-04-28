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


## Using YOLOv9

If you want to use YOLOv9 instead of YOLOv8, follow these steps:

1. Replace the model instantiation line in the code:
   
   ```python
   # Load the YOLOv8 model
   model = YOLO('yolov8n.pt')
   ```

   with:

   ```python
   # Load the YOLOv9 model
   model = YOLO('yolov9c.pt')
   ```

2. Save the changes and run the Python script again.

Now, your project will utilize YOLOv9 for object detection and tracking.

## Features

- Real-time detection and tracking of vehicles and individuals.
- Click-based access restriction beyond specified boundaries.
- Alarm sound upon unauthorized access.

## Dependencies

- [OpenCV](https://github.com/opencv/opencv-python) - Wrapper package for OpenCV Python bindings.
- [Ultralytics](https://docs.ultralytics.com/) - YOLOv8 for object detection and multi-object tracking

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

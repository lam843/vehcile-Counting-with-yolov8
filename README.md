# vehicle-Counting-with-yolov8



## Introduction
This repository supply a user-friendly interactive interface for [YOLOv8](https://github.com/ultralytics/ultralytics) with vehicle Tracking and Counting capability. The interface is powered by [Streamlit](https://github.com/streamlit/streamlit).



## Installation
### Create a virtual environment
```commandline
# create
python -m venv yolov8-mot-streamlit

# activate
source yolov8-mot-streamlit/bin/activate
```

### Install packages
```commandline
# Streamlit dependencies
pip install streamlit

# YOLOv8 dependecies
pip install -e '.[dev]'
```

| Model                                                                                | size<br><sup>(pixels) | mAP<sup>val<br>50-95 | Speed<br><sup>CPU ONNX<br>(ms) | Speed<br><sup>A100 TensorRT<br>(ms) | params<br><sup>(M) | FLOPs<br><sup>(B) |
| ------------------------------------------------------------------------------------ | --------------------- | -------------------- | ------------------------------ | ----------------------------------- | ------------------ | ----------------- |
| [YOLOv8n](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt) | 640                   | 37.3                 | 80.4                           | 0.99                                | 3.2                | 8.7               |
| [YOLOv8s](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8s.pt) | 640                   | 44.9                 | 128.4                          | 1.20                                | 11.2               | 28.6              |
| [YOLOv8m](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8m.pt) | 640                   | 50.2                 | 234.7                          | 1.83                                | 25.9               | 78.9              |
| [YOLOv8l](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8l.pt) | 640                   | 52.9                 | 375.2                          | 2.39                                | 43.7               | 165.2             |
| [YOLOv8x](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8x.pt) | 640                   | 53.9                 | 479.1                          | 3.53                                | 68.2               | 257.8             |


## Run
```commandline
streamlit run app.py
```
Then will start the Streamlit server and open your web browser to the default Streamlit page automatically.
For vehicle Counting, you can choose "Video" from "Select Source" combo box and use "test3.mp4" inside videos folder as an example.

## Result in Colab


  
## Result in App



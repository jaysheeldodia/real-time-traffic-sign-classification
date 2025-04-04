# Real-Time Traffic Sign Detection using YOLOv5 🚦

Welcome to the repository for a real-time traffic sign detection system powered by **YOLOv5**. This project demonstrates how to train a custom object detection model and perform inference on a video file to detect traffic signs.

---

## Project Overview

This project utilizes a Jupyter notebook to guide you through the process of:
- Preparing a custom datasaet
- Training a YOLOv5 model for traffic sign detection.
- Running inference on a sample video to visualize detection results.

The code is contained within the notebook `traffic_sign_detection.ipynb`.

---

## Demo Videos

### Input Video
Watch the input video used for inference:

<video width="640" height="480" controls>
  <source src="input/input.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Output Video
Watch the output video displaying the detection results:

<video width="640" height="480" controls>
  <source src="output/output.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## How to Run the Project

1. **Clone the Repository and Install Dependencies**
    ```bash
    git clone https://github.com/jaysheeldodia/traffic-sign-detection.git
    cd traffic-sign-detection
    ```

2. **Launch the Notebook**
    ```bash
    jupyter notebook traffic_sign_detection.ipynb
    ```
   Follow the instructions in the notebook to train the model and run inference.

3. **View the Results**
   The model performance and detection results can be viewed within the notebook. Additionally, training metrics are saved under the `metrics/` directory.

---

## Notable Files

- **`traffic_sign_detection.ipynb`**: Main notebook detailing the complete detection pipeline.
- **`input/input.mp4`**: Video file used for testing the model.
- **`output/output.mp4`**: Video file with annotated detection results.

---

## Results & Metrics

The project logs various performance metrics during training and validation. These metrics are stored in the `metrics/` directory and are visualized in the notebook for better analysis of the model’s performance.

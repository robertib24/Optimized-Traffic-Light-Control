# Smart Traffic Light Control using YOLOv8

This project implements a **Smart Traffic Light Control System** using **YOLOv8** for real-time object detection. The system detects vehicles, pedestrians, and traffic signs in both video feeds and simulation environments to optimize traffic light management.

## 🛠 Features
- **Object Detection:** Utilizes YOLOv8 for identifying cars, pedestrians, traffic lights, and signs.
- **Traffic Light Optimization:** Adjusts traffic signals based on real-time traffic flow data.
- **Video Evaluation:** Performs live detection on video streams.
- **Simulation Integration:** Operates within a simulated environment to evaluate traffic flow optimization.
- **Data Processing:** Includes preprocessing, augmentation, and visualization of the dataset.

---

## 🚀 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Smart-Traffic-Light-YOLOv8.git
    cd Smart-Traffic-Light-YOLOv8
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Install YOLOv8 using Ultralytics:
    ```bash
    pip install ultralytics
    ```

---

## 🗂 Dataset Preparation

- Ensure your dataset follows the **YOLO format** with labeled annotations.

---

## 🧑‍💻 Training the Model

To train the YOLOv8 model:
```bash
python train.py --data data.yaml --epochs 100 --imgsz 640 --batch 32
```
---

## 🛑 Traffic Simulation and Control
- The system integrates with a traffic simulation for real-time testing.
- It detects vehicles and dynamically adjusts traffic light signals to optimize traffic flow.
- Results are visualized to analyze improvements in traffic management.

---

## 📊 Evaluation
- The model was evaluated using video footage and simulation results.
- Real-time detection accuracy and system performance were analyzed.
- The impact of optimized traffic light control was assessed through comparison metrics.

---

## 📅 Future Improvements
- Enhance the detection model using larger datasets and advanced augmentation techniques.
- Implement reinforcement learning for adaptive traffic light management.
- Optimize the system for edge devices using lightweight YOLO versions.

---

## 📜 License

This project is licensed under the MIT License.
Feel free to contribute or modify the project!

---

## Special thanks to @mihir-m-gandhi for the simulation game




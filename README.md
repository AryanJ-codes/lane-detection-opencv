# Lane Detection using Classical Computer Vision

This repository accompanies the case study:

**Analyzing the Effectiveness of Edge Detection and Hough Transform Methods in Detecting Road Lanes for Autonomous Vehicles**

The project evaluates a classical computer vision pipeline using Canny edge detection and Hough Line Transform on the TuSimple lane detection dataset.

## 📄 Case Study
- [Read the full paper (PDF)](paper/lane_detection_case_study.pdf)

## 🧠 Methodology
The lane detection pipeline consists of:
1. Grayscale conversion
2. Gaussian blurring
3. Canny edge detection
4. Region of Interest masking
5. Hough Line Transform for lane extraction

## 🛠️ Tools & Technologies
- Python 3
- OpenCV
- NumPy
- TuSimple Lane Detection Dataset

## 📊 Results

### Pipeline Visualization
![Pipeline](results/figures/pipeline_steps.png)

### IoU under Different Lighting Conditions
![IoU](results/figures/iou_lighting_conditions.png)

### Performance Metrics
![Metrics](results/figures/performance_metrics.png)

### Qualitative Results
![Qualitative](results/figures/qualitative_results.png)

## 📌 Key Observations
- Performs well on straight, well-lit roads
- Degrades under shadows, low light, and curved lanes
- Computationally efficient and suitable for real-time systems

## 📂 Repository Structure
lane-detection-opencv/
│── README.md
├── paper/
│ └── lane_detection_case_study.pdf
└── results/
└── figures/

## 👤 Author
Aryan Jhamnani

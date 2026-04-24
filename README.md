# CS5296 Cloud Computing Individual Project
## Edge-Cloud Task Offloading Performance Evaluation

This repository contains the full implementation, experimental results, and final report for the CS5296 Cloud Computing individual technical project.
All experiments run **locally with pure Python** — no cloud services, GPUs, or external dependencies are required.

---

## Project Information
- **Course**: CS5296 Cloud Computing, Spring 2026
- **Project Type**: Technical (Individual)
- **Topic**: Performance Evaluation of Edge-Cloud Task Offloading Strategies
- **Author**: WANG Yanzhuo
- **University**: City University of Hong Kong

---

## Strategies Evaluated
1. **Cloud-only**: All tasks executed in the cloud
2. **Edge-only**: All tasks processed locally on edge devices
3. **Edge-Cloud Collaborative**: Dynamic task scheduling between edge and cloud

---

## Evaluation Metrics
- Accuracy (%)
- Latency (seconds)
- Standard Deviation of Accuracy (%)
- Efficiency Score (Accuracy / Latency)

---

## File Structure
├── main.py # Main experiment code├── results/│ ├── task_offloading_results.csv # Performance table│ ├── accuracy_bar.pdf # Accuracy comparison figure│ └── latency_bar.pdf # Latency comparison figure├── CS5296_Individual_Report.tex # LaTeX final report└── README.md
plaintext

---

## Environment Requirements
- Python 3.8 or higher
- numpy
- pandas
- matplotlib
- scikit-learn

---

## Installation
```bash
pip install numpy pandas matplotlib scikit-learn
Run the Project
bash

python main.py
The script will automatically generate:
Performance data table (CSV)
Accuracy and latency charts (PDF)
Complete LaTeX report source file
Experimental Results

Strategy	Accuracy (%)	Std (%)	Latency (s)	Efficiency
Cloud-only	96.12	1.03	0.3812	252.15
Edge-only	92.36	1.21	0.0245	3769.80
Edge-Cloud Collaborative	95.24	0.97	0.1966	484.44
Conclusions
Cloud-only achieves the highest accuracy but has high latency.
Edge-only provides the lowest latency but relatively lower accuracy.
Edge-Cloud Collaborative achieves the best balance between accuracy and latency, making it the most suitable solution for real-world edge computing applications.
Reproducibility
All experiments are fully reproducible. Random seeds are fixed, and all parameters are hard-coded to ensure consistent results across different devices.
Acknowledgment
This project is completed as an individual technical project for CS5296 Cloud Computing.
plaintext

### ✅ How to use
1. Create a new file named **`README.md`** in your Gitee repo
2. **Copy everything above** and paste directly into it
3. Commit and push – done!

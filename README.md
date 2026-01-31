# WaferDefect-CNN
An end-to-end Deep Learning pipeline to automate semiconductor quality control. This project utilizes Convolutional Neural Networks (CNNs) to classify spatial defect patterns in semiconductor wafer maps using the WM-811K dataset.
In semiconductor manufacturing, identifying defect patterns on silicon wafers is critical for improving yield and diagnosing process issues. Manual inspection is slow and prone to error.

This project implements a Convolutional Neural Network (CNN), built with fast.ai and PyTorch to automatically detect and classify eight distinct defect categories (such as Center, Donut, Edge-Loc, Scratch, etc...) from the WM-811K dataset.

Key Features: 
1. Domain Specific: Tailored for semiconductor fabrication and yield engineering.
2. Deep Learning Architecture: Utilizes a CNN backbone optimized for spatial pattern recognition.
3. Data Pipeline: Includes preprocessing steps for handling imbalanced wafer map data.

🚀 Tech Stack
Language: Python

Libraries: fast.ai, PyTorch, NumPy, Matplotlib

Dataset: WM-811K (811,457 wafer maps)

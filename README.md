# Automated-Detection-of-Fetal-Anomalies-Using-Deep-Learning

This project applies deep learning techniques to detect fetal anomalies and brain tumors using medical imaging data such as ultrasound and MRI scans. It automates the segmentation of fetal head circumference and tumor regions, helping enhance diagnostic precision in both prenatal and neurological healthcare.

Key Features
Fetal Head Circumference (HC) Segmentation
Accurately segments and measures fetal head size, a vital metric in monitoring fetal growth.

Dual Medical Application
Designed for both fetal anomaly detection and brain tumor segmentation tasks.

Deep Learning Architectures
Uses U-Net and SegNet, highly efficient for medical image segmentation.

Accurate Segmentation
Delivers high Dice scores and low training/validation losses, ensuring reliability in medical predictions.

Visualization Support
Displays side-by-side comparisons of original and segmented images for better analysis.

Dataset Summary
The dataset comprises both public and hospital-collected ultrasound images, including a wide range of cases with normal and abnormal fetal growth patterns.

Total Images: 1,998

999 normal fetal images

999 annotated with fetal abnormalities

Image Formats: PNG, JPG, JPEG

Images were resized during preprocessing to ensure consistency.

Split: 80% training set and 20% validation set.

Requirements
To run this project, ensure the following libraries and tools are installed:

Python 3.7 or higher

TensorFlow 2.x

Keras

NumPy

OpenCV

scikit-learn

Matplotlib

All other dependencies are listed in the requirements.txt file.

Results
The models performed with the following accuracy levels:

U-Net Model
Training Dice Score: 96.51%
Validation Dice Score: 95.29%
Training Loss: 648.65
Validation Loss: 1260.94

SegNet Model
Training Dice Score: 91.24%
Validation Dice Score: 91.19%
Training Loss: 1754.22
Validation Loss: 1833.84

Future Directions
Dataset Expansion
Collect more labeled data from diverse institutions to enhance robustness and accuracy.

Model Innovation
Explore hybrid and advanced models such as Mask R-CNN, Attention U-Net, or Transformer-based networks.

Real-Time Deployment
Develop real-time integration tools for clinical ultrasound and MRI machines to enable on-the-spot anomaly detection.

Contributions
This project is open for improvement. If you have ideas, suggestions, or enhancements, feel free to collaborate. Contributions are welcome!

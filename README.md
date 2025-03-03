# Detection-of-pores-in-Welding-with-Auto-encoder

## Authors
- **mnidgu2s** - Mohammed Zaid Nidgundi  
- **smoses2s** - Swithinraj Moses Daniel  

## Introduction
This project explores acoustic-based weld inspection using neural networks to enhance weld seam quality assessment. Traditional methods are time-consuming and manual; our approach leverages sound analysis for automation and real-time defect detection.

## Solution Overview
- **Acoustic Signal Processing**: Uses Mel Frequency Cepstral Coefficients (MFCC) to extract meaningful patterns.
- **Neural Networks for Analysis**: Autoencoder detects anomalies, while a CNN classifies weld seams.
- **Real-time Insights**: Faster and more reliable defect identification.

## Dataset & Processing
- Custom welding sound dataset analyzed via Short-Time Fourier Transform (STFT).
- MFCC features extracted and stored for model training.
- Autoencoder trained on normal signals to detect reconstruction errors.

## Model Training
- **Autoencoder**: Learns normal signal representations to highlight anomalies.
- **CNN**: Classifies weld seams as normal or containing pores.
- **Evaluation**: Histogram visualization of reconstruction errors to set classification thresholds.

## Results & Insights
- Real-time anomaly detection and classification with deep learning.
- Visual analysis of sound features for defect identification.

## References
- Rohe et al., "Detecting Process Anomalies in GMAW using CNNs," *Journal of Manufacturing and Materials Processing*.
- [AWS Sound Anomaly Detection Repo](https://github.com/aws-samples/sound-anomaly-detection-for-manufacturing/tree/main).

                                     Deep Learning-Based Video Fight Detection
This project implements video-based fight detection using deep learning techniques, leveraging two different architectures: ViViT (Video Vision Transformer) and a CNN-RNN model that extracts frame-wise features and processes them with a recurrent classifier. ViViT employs a Transformer-based approach to process video data, effectively capturing long-range dependencies in visual sequences. On the other hand, the CNN-RNN model first extracts features from individual video frames using a Convolutional Neural Network (CNN) and then processes these features as a time-series using a Recurrent Neural Network (RNN), focusing on learning temporal dependencies in video sequences.

For this study, two different datasets were combined to enhance fight detection performance. These datasets include videos from real-life scenarios, movie scenes, sports matches, and surveillance footage. Each video is labeled to indicate fight and non-fight moments, with a maximum duration of 2.5 seconds per clip. The diversity of the dataset improves the model’s generalization across different environments and conditions, leading to more robust results.

Data Splitting for ViViT:

Training Set (72%): Used for the model’s learning process.

Validation Set (8%): Used to evaluate the model's performance during training.

Test Set (20%): Independently used for final model evaluation.

Data Splitting for CNN-RNN:

Video features and masks are split into training and test sets.

The data is divided as 80% training and 20% testing.

Video features and masks are assigned accordingly to training and test sets.

Labels are also aligned with these splits for consistency.

<img src="https://github.com/user-attachments/assets/5398963e-2ba4-4464-b413-5c9308dd42d8" width="600"/>


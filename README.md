Overview
This project is a real-time American Sign Language (ASL) gesture recognition system that bridges the communication gap between sign language users and non-users. By leveraging deep learning and Mediapipe, the system recognizes hand gestures and converts them into readable text, fostering inclusivity and accessibility.

Features
Real-time detection and recognition of ASL gestures.
Trained deep learning model for accurate classification.
Interactive interface for testing and integration.
Supports gestures corresponding to the ASL alphabet and custom classes.
Dataset
The model uses the publicly available ASL alphabet dataset, featuring labeled images of hand gestures representing letters and special characters like "space."

Workflow
Data Preprocessing: Hand landmarks are extracted from images using Mediapipe.
Model Training: A deep learning model classifies gestures with TensorFlow/Keras.
Evaluation: Accuracy and metrics are evaluated using confusion matrices and ROC curves.
Real-Time Testing: Uses a webcam to detect and classify gestures in real-time.

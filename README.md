**Speech Emotion Recognition**

This project focuses on developing a speech emotion recognition system using machine learning techniques. The goal is to accurately classify emotions conveyed through speech signals, utilizing the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS).

**Technologies Used:**

Python: A high-level programming language used for implementing machine learning algorithms and data analysis.
Librosa: A Python package for music and audio analysis, providing tools for feature extraction and signal processing.
Scikit-learn: A machine learning library in Python, offering a wide range of algorithms and tools for model training, evaluation, and hyperparameter optimization.
NumPy: A fundamental package for scientific computing with Python, providing support for large, multi-dimensional arrays and matrices.
Soundfile: A Python library for reading and writing sound files, facilitating audio file handling in the project.

**Description:**

The project employs the Multilayer Perceptron (MLP) classifier, a type of artificial neural network, for emotion classification. The dataset is preprocessed using Librosa to extract relevant features from the audio signals, including MFCCs, chroma features, and mel-spectrogram features. The Scikit-learn library is used for model training and evaluation.

**Hyperparameter Tuning:**

Hyperparameter optimization is performed to fine-tune the MLP classifier. Parameters such as the size of the hidden layers, learning rate, batch size, and maximum number of iterations are optimized using techniques like grid search or randomized search. The optimal hyperparameters are selected based on their impact on the model's performance, measured by accuracy on the testing set.

**Accuracy:**

The model achieved an accuracy of **86.75%** on the testing set, demonstrating its effectiveness in accurately classifying emotions from speech signals.

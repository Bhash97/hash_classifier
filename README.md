This project implements a neural network classifier for evaluating and selecting optimal hash functions based on multiple performance metrics.

Project Overview
The goal of this project is to classify hash functions like SHA-256, SHA-512, SHA-3-256, SHA-3-512, and MD5 using evaluation metrics such as:

Speed
Collision Resistance
Per-Image Resistance
Second-per-Image Resistance
Entropy
Memory Usage
Efficiency Score
Files in This Repository
hash_classifier.ipynb: Jupyter Notebook containing the neural network classifier code.
hash_functions_results.csv: Dataset used for training and evaluation. It includes performance metrics for different hash functions.

Dataset Description
The dataset (hash_functions_results.csv) includes the following columns:
Iteration: Iteration number for the tests.
Hash Function: Name of the hash function tested.
Speed (s): Time taken for hashing.
Collisions: Number of hash collisions detected.
Per-Image Resistance: Boolean indicating resistance to per-image attacks.
Second-per-Image Resistance (s): Time for resistance per image.
Entropy: Randomness measure.
Memory Usage (MiB): Memory consumed during computation.
Efficiency Score: Calculated score to rank the hash function’s efficiency.

Key Features
Neural Network Classifier: Built with TensorFlow/Keras, the classifier uses multiple input features and evaluates hash functions.
Custom Evaluation Metrics: Grading system ranks hash functions on a scale of 1 to 5.
Visualization and Analysis: Provides detailed performance insights through plots and tables.

Environment Setup
Development Environment
Python Version: 3.8 or higher
Environment: Anaconda (recommended for package and environment management)
IDE: Jupyter Notebook or any Python-compatible IDE

License
This project is licensed under the MIT License.

Feel free to contribute by submitting issues or pull requests.


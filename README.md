Siamese Network Implementation from Scratch (Keras)

Overview

This repository contains an implementation of a Siamese Network from scratch using Keras. Siamese Networks are used for tasks like facial recognition, signature verification, and other similarity-based learning problems.

Features

Implemented from scratch using Keras

Uses contrastive loss for training

Demonstrates one-shot learning capabilities

Includes dataset preparation and model evaluation

Installation

To get started, clone this repository and install the necessary dependencies:

git clone https://github.com/Siddhant128-bit/Siamese_Network_Code_Implementation_From_Scratch_Keras.git
cd Siamese_Network_Code_Implementation_From_Scratch_Keras
pip install -r requirements.txt

Usage

Run the training script:

python train.py

Evaluate the model:

python evaluate.py

File Structure

├── dataset/            # Contains the dataset used for training
├── models/             # Trained models and architecture
├── train.py            # Script to train the Siamese Network
├── evaluate.py         # Script to evaluate the trained model
├── utils.py            # Helper functions
├── README.md           # This documentation

Results

The model achieves good performance on the given dataset by correctly identifying similar and dissimilar pairs.

Contributing

Feel free to contribute and improve the implementation! Open a pull request with your changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.


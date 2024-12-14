# MNIST Classification with CI/CD Pipeline

 This project uses GitHub Actions to implement a simple Convolutional Neural Network (CNN) for MNIST digit classification with a complete CI/CD pipeline.

## Project Structure

├── .github/
│   └── workflows/
│       └── ml-pipeline.yml
├── model.py
├── test_model.py
├── train_model.py
├── requirements.txt
└── .gitignore

## CI/CD Pipeline
The GitHub Actions workflow:

Checks if the model has less than 25,000 parameters
Trains for exactly 1 epoch
Verifies accuracy is above 95%
Uploads trained model as an artifact

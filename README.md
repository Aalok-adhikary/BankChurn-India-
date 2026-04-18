🏦 BankChurn India

Next-Gen Customer Retention Intelligence for the Indian Banking Sector

🌟 Executive Summary

BankChurn India is a sophisticated predictive analytics platform designed to address one of the most critical challenges in the Indian financial landscape: Customer Attrition.

By leveraging an Artificial Neural Network (ANN), this application processes complex customer behavioral patterns—tailored specifically to Indian demographics—to predict churn risk with high precision. This allows banking institutions to transition from reactive to proactive retention strategies.

🚀 Access the Live Dashboard

✨ Key Value Propositions

Feature

Description

🧠 Deep Learning Engine

Powered by a multi-layer ANN optimized for binary classification tasks.

🇮🇳 Geo-Specific Logic

Account parameters and demographic features tuned for the Indian market.

⚡ Real-Time Inference

Dynamic risk scoring as you toggle customer parameters.

📊 Analytical Depth

Visualizes not just the "if" but the "why" behind customer churn.

📱 Responsive UI

A sleek, modern dashboard built for both desktop and mobile viewing.

🛠️ Technical Architecture

The Neural Core

The model is architected to capture non-linear relationships between financial variables:

Input Layer: Processes 10+ customer features (Credit Score, Geography, Gender, Age, Tenure, Balance, etc.).

Hidden Layers: Two dense layers utilizing the ReLU activation function for feature extraction.

Output Layer: A Sigmoid neuron producing a probability score between $0$ and $1$.

Optimization: Adam Optimizer with Binary Cross-Entropy loss function.

Tech Stack

Frontend: Streamlit (Reactive Web Framework)

Machine Learning: TensorFlow / Keras

Data Processing: Scikit-Learn, Pandas, NumPy

Styling: Custom CSS for a premium "Midnight Blue" FinTech theme

📈 Model Performance Metrics

Based on case study simulations, the model achieves robust performance indicators:

$$\text{Accuracy} \approx 86\%$$

$$\text{Precision} \approx 84\%$$

The model is specifically trained to minimize False Negatives, ensuring that high-risk customers are rarely missed.

⚙️ Quick Start Guide

1. Prerequisites

Python 3.9+

Virtual Environment (Recommended)

2. Installation

# Clone the repository
git clone [https://github.com/Aalok-adhikary/BankChurn-India-.git](https://github.com/Aalok-adhikary/BankChurn-India-.git)

# Navigate to the directory
cd BankChurn-India-

# Install dependencies
pip install -r requirements.txt


3. Execution

streamlit run app.py


📂 Project Structure

├── app.py              # Streamlit Web Application
├── model.h5            # Pre-trained ANN Model
├── scaler.pkl          # Feature Scaling object
├── dataset/            # Historical data samples
└── requirements.txt    # Project Dependencies


🤝 Contribution & License

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

Distributed under the MIT License. See LICENSE for more information.

Developed with ❤️ by Aalok Adhikary

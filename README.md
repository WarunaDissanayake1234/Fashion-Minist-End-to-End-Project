

# Fashion MNIST End-to-End Project

This repository contains code for a Deep Learning model that classifies fashion items using a Neural Network. The project is deployed with Streamlit and can be containerized using Docker.

## Overview

This project implements a Neural Network for classifying fashion items from the Fashion MNIST dataset. Python programming language is used for implementation, and the model is built with Keras. Streamlit is utilized for creating a user interface, and the project can be containerized using Docker. The VS Code IDE is used for development.

## Requirements

- Python
- VS Code (for development)
- Docker (for containerization)
- Libraries: keras, streamlit

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Fashion-MNIST-End-to-End-Project.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install keras streamlit
   ```

3. **Run the Code Locally:**
   - Open the project in VS Code.
   - Use the VS Code interface to run the code and interact with the Streamlit app.

4. **Build and Run Docker Container:**
   ```bash
   docker build -t fashion-mnist-project .
   docker run -p 8501:8501 fashion-mnist-project
   ```
   Open your web browser and visit http://localhost:8501 to access the Streamlit app.

## Files

- `main.py`: Python script containing the code for fashion item classification using a Neural Network.
- `Dockerfile`: Docker configuration file for containerizing the application.
- `requirements.txt`: File containing the required Python packages for Docker.

## Dataset

The dataset used in this project is Fashion MNIST, which includes grayscale images of fashion items. The Neural Network aims to classify these items into different categories.

## Acknowledgments

The model is built with Keras, and the project is deployed using Streamlit. Docker is used for containerization.

# Alzheimer's Detection through Brain Imaging using Deep Learning Models

This project detects Alzheimer's disease using deep learning techniques (CNN and RNN) from brain imaging data. It provides a web interface where users can upload brain scans and get a diagnosis.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Running the App](#running-the-app)
- [Usage](#usage)

## Features

- Upload brain scan images for Alzheimer’s detection.
- Utilizes CNN and RNN for image classification.
- Provides an intuitive web interface for users to interact with.
- FastAPI-based backend for model inference and API handling.

## Tech Stack

- **Frontend**: React.js
- **Backend**: FastAPI
- **Machine Learning Models**: CNN, RNN
- **Other**: Python, TensorFlow, Keras, Numpy

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) and npm
- [Python 3.x](https://www.python.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [TensorFlow](https://www.tensorflow.org/)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/alzheimers-detection.git
   cd alzheimers-detection
   ```

2. Install the dependencies for the frontend:

   ```bash
   cd frontend
   npm install
   ```

3. Install the dependencies for the backend:

   ```bash
   cd ..
   pip install -r requirements.txt
   ```

## Running the App

### Frontend

To start the frontend server, run the following commands:

```bash
cd frontend
npm run start
```

The frontend will be available at `http://localhost:3000`.

### Backend (FastAPI)

To start the FastAPI backend, run the following command:

```bash
python main.py
```

The backend API will be available at `http://localhost:8000`.

## Usage

1. Visit `http://localhost:3000` to access the web interface.
2. Upload a brain image for Alzheimer's detection.
3. The results will be displayed on the screen after model inference.

![image](https://github.com/user-attachments/assets/6970eb39-5b86-4a81-9400-834910413135)
![image](https://github.com/user-attachments/assets/e5de7d96-03e1-48ab-a8c3-955e6e6a7f72)




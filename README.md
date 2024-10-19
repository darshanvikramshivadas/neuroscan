# Alzheimer's Detection Through Brain Imaging Using Deep Learning Models

This project detects Alzheimer's disease using deep learning techniques (CNN) from brain imaging data. It provides a web interface where users can upload brain scans and get a diagnosis.

## Features

- Upload brain scan images for Alzheimer’s detection.
- Utilizes CNN for image classification.
- Provides an intuitive web interface for users to interact with.
- FastAPI-based backend for model inference and API handling.

## Tech Stack

- **Frontend**: React.js
- **Backend**: FastAPI
- **Machine Learning Models**: CNN
- **Other**: Python, TensorFlow, Keras, Numpy

## Installation

### Setup for Python

1. Install Python (refer to setup instructions for your OS).

2. Install the required Python packages:

   ```bash
   pip3 install -r training/requirements.txt
   pip3 install -r api/requirements.txt
   ```

3. Install TensorFlow Serving (refer to setup instructions).

### Setup for ReactJS

1. Install [Node.js](https://nodejs.org/) and npm (setup instructions available on the respective website).

2. Install the necessary dependencies for the frontend:

   ```bash
   cd frontend
   npm install --from-lock-json
   npm audit fix
   ```

## Running the App

### Running the API (Using FastAPI)

1. Navigate to the `api` folder:

   ```bash
   cd api
   ```

2. Run the FastAPI server using `uvicorn`:

   ```bash
   uvicorn main:app --reload --host 0.0.0.0
   ```

   Your API is now running at `http://0.0.0.0:8000`.

### Running the Frontend

1. Navigate to the `frontend` folder:

   ```bash
   cd frontend
   ```

2. Start the frontend server:

   ```bash
   npm run start
   ```

   The frontend will be available at `http://localhost:3000`.

## Usage

1. Visit `http://localhost:3000` to access the web interface.
2. Upload a brain image for Alzheimer's detection.
3. The results will be displayed on the screen after model inference.

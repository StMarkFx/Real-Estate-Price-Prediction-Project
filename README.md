# Real-Estate-Project

## Project Overview
This project aims to predict real estate prices using machine learning models. The web application allows users to input property features and get an estimated price. The project encompasses frontend, backend, and machine learning components, all integrated to provide a seamless user experience.

## Tech Stack
- Frontend: React (JavaScript)
- Backend: Flask (Python)
- Machine Learning: Scikit-learn
- Hosting: AWS EC2

## Directory Structure
- `client/`: Contains the React frontend code.
- `model/`: Contains the machine learning model code.
- `server/`: Contains the Flask backend code.

## Setup and Installation

### Prerequisites
Ensure you have the following installed:
- Node.js and npm
- Python 3.x and pip
- Virtualenv

### Frontend Setup
1. Navigate to the `client` directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the frontend application:
   ```bash
   npm start
   ```

### Backend Setup
1. Navigate to the `server` directory:
   ```bash
   cd server
   ```
2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the backend server:
   ```bash
   python app.py
   ```

### Machine Learning Model Setup
1. Navigate to the `model` directory:
   ```bash
   cd model
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model (if applicable):
   ```bash
   python train.py
   ```
4. Save the model and ensure it is correctly referenced in the backend code.

## Usage
To use the application:
1. Start the backend server.
2. Start the frontend application.
3. Navigate to `http://localhost:3000` in your web browser.
4. Input property features to get an estimated price.

## API Endpoints
- **GET /predict**: Returns the predicted price for given property features.
  - Parameters: `feature1`, `feature2`, ..., `featureN`
  - Example request:
    ```bash
    curl http://localhost:5000/predict?feature1=value1&feature2=value2
    ```

## Acknowledgements
- Special thanks to Mr Dhaval Patel and CodeBasics, and the open-source community for providing the tools and libraries used in this project.


## Contact
For any inquiries, please contact me: adebayomarkadedayo@gmail.com


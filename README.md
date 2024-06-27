# Multiple Disease Prediction System

## Project Description

The Multiple Disease Prediction System aims to predict several diseases, including diabetes, heart disease, and Parkinson's disease, using machine learning models. It allows users to input patient data and obtain predictions about the likelihood of these diseases. The system leverages pre-trained models for each disease, making it an accessible and efficient tool for early disease detection.

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on user input.
- **Heart Disease Prediction**: Evaluates the risk of heart disease using patient data.
- **Parkinson's Disease Prediction**: Assesses the possibility of Parkinson's disease.
- **User-Friendly Interface**: Simple interface for inputting data and receiving predictions.
- **Streamlit Deployment**: Easily deployable as a web application using Streamlit.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/multiple-disease-prediction.git
   cd multiple-disease-prediction

2. **Create and activate a virtual environment (optional but recommended):**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the required libraries:**:
   ```bash
   pip install -r requirements.txt

### Usage

1. **Run the Streamlit Application:**:
   ```bash
   streamlit run multiple-disease-pred.py

2. **Interact with the Application::**:
- Open your web browser and go to http://localhost:8501.
- Input the required patient data for the desired prediction.
- Receive the prediction results and analyze the likelihood of the disease.

## File Structure

- **`multiple-disease-pred.py`:** Main script for running the Streamlit application.
- **`requirements.txt`:** List of required Python libraries.
- **`diabetes_model.sav`:** Pre-trained model for diabetes prediction.
- **`heart_disease_model.sav`:** Pre-trained model for heart disease prediction.
- **`parkinsons_model.sav`:** Pre-trained model for Parkinson's disease prediction.
- **`dataset/`:** Directory containing the datasets used for training.
- **`colab files/`:** Jupyter notebooks for training the models.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

Thanks to the dataset providers and inspiration from various open-source disease prediction projects.

# Shushruta: Disease Prediction System

![Logo](https://via.placeholder.com/150)

## Overview

Shushruta is a comprehensive tool designed to predict multiple diseases, including diabetes, heart disease, and Parkinson's disease, using machine learning models. The system leverages various datasets and provides a user-friendly interface for making predictions.

## Features

- **Multi-Disease Prediction**: Supports predictions for diabetes, heart disease, and Parkinson's disease.
- **Machine Learning Models**: Utilizes advanced machine learning techniques for accurate predictions.
- **User-Friendly Interface**: Easy-to-use interface built with Streamlit for seamless interaction.
- **Extensive Datasets**: Uses well-known datasets to train and validate models.

## Project Structure

```
Shushruta-main/
├── dataset/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
├── notebooks/
│   ├── Multiple disease prediction system - diabetes.ipynb
│   ├── Multiple disease prediction system - heart.ipynb
│   └── Multiple disease prediction system - Parkinsons.ipynb
|── models/
|   ├── diabetes_model.sav
|   ├── heart_disease_model.sav
|   └── parkinsons_model.sav
├── requirements.txt
└── streamlit_app.py
```

## Installation

### Prerequisites

- [Python 3.10 or Above](https://www.python.org/)
- [Streamlit](https://streamlit.io/)

### Steps

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/Shushruta.git
    cd Shushruta
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit Application**

    ```bash
    streamlit run streamlit_app.py
    ```

## Usage

1. Open your browser and navigate to the Streamlit app (usually at `http://localhost:8501`).
2. Select the disease you want to predict (diabetes, heart disease, or Parkinson's).
3. Enter the required input parameters.
4. Click on the "Predict" button to get the prediction results.

## Datasets

- **Diabetes Dataset**: Contains various health metrics used to predict diabetes.
- **Heart Disease Dataset**: Includes features relevant to heart disease prediction.
- **Parkinson's Disease Dataset**: Consists of attributes related to Parkinson's disease.

## Notebooks

The project includes Jupyter notebooks for each disease prediction model, detailing the data preprocessing, model training, and evaluation processes:

- `Multiple disease prediction system - diabetes.ipynb`
- `Multiple disease prediction system - heart.ipynb`
- `Multiple disease prediction system - Parkinsons.ipynb`

## Contributing

We welcome contributions from the community! Please read our [contributing guidelines](CONTRIBUTING.md) before making any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please reach out to us at [devakash2905@gmail.com](mailto:devakash2905@gmail.com).

![Demo](https://via.placeholder.com/600x400)

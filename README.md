# Time-Series-Forecasting

## Project Overview

Time-Series-Forecasting is a Python project focused on predicting future values in a time series using an LSTM (Long Short-Term Memory) neural network.

## Repository Contents

- **model.ipynb**: Jupyter Notebook that contains the code for data preprocessing, training, and evaluating the LSTM model for time series forecasting.
- **LSTM_MODEL.keras**: Pre-trained LSTM model saved in Keras format, which can be loaded and used for predictions on new time series data.
- **README.md**: Documentation file describing the project, how to set it up, and how to use it.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.12
- Jupyter Notebook
- pip

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Lokesh-DataScience/Time-Series-forecasting.git
    cd Time-Series-forecasting
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook

To open and run the Jupyter Notebook for training and evaluating the LSTM model:

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open `model.ipynb` and run the cells to execute the code.

### Model Usage

- **LSTM_MODEL.keras**: This file contains a pre-trained LSTM model that can be loaded and used for predictions. To use the model, load it using Keras as follows:

    ```python
    from tensorflow.keras.models import load_model
    
    # Load the model
    model = load_model('LSTM_MODEL.keras')
    
    # Use the model for predictions
    predictions = model.predict(your_data)
    ```

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Acknowledgements

- **Keras** for providing the deep learning framework used to build the model.
- **Jupyter** for offering an interactive environment for coding and experimentation.

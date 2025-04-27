## Setup and Installation

This project requires Python 3.9.7.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MohamedAbuella/TSA4EESSS.git
    cd TSA4EESSS
    ```

2.  **Create and activate a virtual environment (Recommended):**
    ```bash
    # Create the environment
    python -m venv venv

    # Activate the environment
    # On Linux/macOS:
    source venv/bin/activate
    # On Windows (Command Prompt/PowerShell):
    .\venv\Scripts\activate
    ```
    *(You should see `(venv)` preceding your command prompt after activation.)*

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Running the Code

The core models and analysis are implemented in Jupyter Notebooks (`.ipynb` files) located in the `Codes/` directory.

1.  Ensure your virtual environment is activated (see Step 2 above).
2.  Start Jupyter Notebook or JupyterLab:
    ```bash
    # Using classic Notebook
    jupyter notebook
    # Or using JupyterLab
    jupyter lab
    ```
3.  Navigate to the `Codes/` directory in the Jupyter interface that opens in your web browser and open the desired notebook (e.g., `LSTM_SOG_Weathers_v1.ipynb`).
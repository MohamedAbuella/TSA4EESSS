# TSA4EESSS
Several approaches have been developed for improving the ship energy efficiency, thereby reducing operating costs and ensuring compliance with climate change mitigation regulations. Many of these approaches will heavily depend on measured data from onboard IoT devices, including operational and environmental information, as well as external data sources for more navigational data.
In this paper, we develop a framework that implements time-series analysis techniques to optimize the vessel's speed profile for improving the vessel's energy efficiency.
We present a case study involving a real-world data from a passenger vessel that was collected over a span of 15 months in the south of Sweden. 
The results reveal that DTW-based model, primarily by selecting the best speed profiles, outperforms LSTM and kNN-based models in identifying optimal vessel behavior from observed data. Whereas, the HMM-based model proves to be the most effective model in optimizing the speed profiles with respect to different weather conditions.
Consequently, these findings highlight the effectiveness of time-series-based approach for optimizing vessel voyages within the context of constrained landscapes, as often seen in short-sea shipping.

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

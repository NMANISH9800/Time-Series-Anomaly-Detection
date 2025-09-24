# Time Series Anomaly Detection

## Project Description
**Time Series Anomaly Detection** is an open-source library designed for researchers working with time series anomaly detection. This project provides an end-to-end framework for evaluating and comparing the performance of different time series anomaly detection models. The library includes several baseline algorithms and various evaluation strategies and metrics to assess the performance of models on time series data.

### Key Features:
- **End-to-End Evaluation**: Clean codebase for benchmarking time series anomaly detection methods.
- **Multiple Models**: Includes baseline models for anomaly detection.
- **Evaluation Metrics**: Compare the performance of models using various metrics.
- **Pre-trained Checkpoints**: Ready-to-use pre-trained models for benchmarking.

## Project Requirements

Before running the project, ensure that you have the following installed:

1. **Python 3.8+**  
   You can install Python from [python.org](https://www.python.org/).

2. **Required Libraries**  
   Install the dependencies using the `requirements.txt` file:
 
   pip install -r requirements.txt
   
Additional Tools:

Ensure Git is installed for version control.

You may also need Jupyter Notebook for running tutorials or experiments.

**How to Run the Project Locally**

Step 1: Clone the Repository

Clone the repository to your local machine:

git clone https://github.com/NMANISH9800/Time-Series-Anomaly-Detection.git

cd Time-Series-Anomaly-Detection

Step 2: Set Up the Virtual Environment

Create and activate a virtual environment:

python -m venv ts_env

Activate the virtual environment:

Windows:

ts_env\Scripts\activate

macOS/Linux:

source ts_env/bin/activate

Step 3: Install Dependencies

Install all the necessary dependencies:

pip install -r requirements.txt

Step 4: Prepare Data.

Download the pre-processed datasets from Google Drive.

Place the downloaded dataset in the ./dataset folder.

Step 5: Prepare Checkpoints

Download the checkpoints from Google Drive.

Move the checkpoint files to the appropriate folders:

For LLM-based models, move to ts_benchmark/baselines/LLM/checkpoints.

For pre-trained models (UniTS, Timer, TimesFM), move to ts_benchmark/baselines/pre_train/checkpoints.

Additional models' checkpoints can be obtained via Huggingface.

Step 6: Train and Evaluate Model

Run the experiment script to train and evaluate the model. For example, to run the CATCH experiment:

sh ./scripts/CATCH.sh

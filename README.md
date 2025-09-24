
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
   ```bash
   pip install -r requirements.txt
````

3. **Additional Tools**:

   * Ensure **Git** is installed for version control.
   * You may also need **Jupyter Notebook** for running tutorials or experiments.

## How to Run the Project Locally

### Step 1: Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/NMANISH9800/Time-Series-Anomaly-Detection.git
cd Time-Series-Anomaly-Detection
```

### Step 2: Set Up the Virtual Environment

Create and activate a virtual environment:

```bash
python -m venv ts_env
```

Activate the virtual environment:

* **Windows**:

  ```bash
  ts_env\Scripts\activate
  ```
* **macOS/Linux**:

  ```bash
  source ts_env/bin/activate
  ```

### Step 3: Install Dependencies

Install all the necessary dependencies:

```bash
pip install -r requirements.txt
```

### Step 4: Prepare Data

1. Download the pre-processed datasets from [Google Drive](https://drive.google.com/file/d/1V5BAHWBKU8uih3hE1R7WdF6_crZlIbQT/view?usp=drive_link).
2. Place the downloaded dataset in the `./dataset` folder.

### Step 5: Prepare Checkpoints

1. Download the checkpoints from [Google Drive](https://drive.google.com/file/d/14VKcv_sIPDJgSgzOxUIN80kAzqXdzhC0/view?usp=sharing).
2. Move the checkpoint files to the appropriate folders:

   * For LLM-based models, move to `ts_benchmark/baselines/LLM/checkpoints`.
   * For pre-trained models (UniTS, Timer, TimesFM), move to `ts_benchmark/baselines/pre_train/checkpoints`.
   * Additional models' checkpoints can be obtained via Huggingface.

### Step 6: Train and Evaluate Model

Run the experiment script to train and evaluate the model. For example, to run the **CATCH** experiment:

```bash
sh ./scripts/CATCH.sh
```

## Conclusion

This project provides a comprehensive framework for benchmarking and evaluating time series anomaly detection models. It allows you to compare different models under consistent conditions, ensuring you can assess their effectiveness in detecting anomalies in time series data.

```

This README file provides the necessary instructions for setting up and running the **Time Series Anomaly Detection** project locally. Let me know if you need further adjustments!
```

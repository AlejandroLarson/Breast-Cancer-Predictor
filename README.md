# Breast-Cancer-Predictor
## Overview
The Breast Cancer diagnosis app uses machine learning to assist medical professionals in diagnosing breast cancer. Using a set of measurements the app can predict if a breast mass is benign or malignant. It provides a radar chart to display the information and provides the predicted diagnosiis and probability of it being benign or malignant. One can also manually input measurements using the sidebar. 

The app uses the public data set [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
and is for educational purposes.

A live version of the app has been deployed using [Streamlit Community Cloud](https://breast-cancer-predictor-2024.streamlit.app/).

## Installation
You can run the app inside a virtual environment. You can run it using conda to install requires packages. Create an environment by running:
```bash
conda create -n cancer-predict python=3.10
```

Activate environment:
```bash
conda activate cancer-predict
```

Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
To start the app run this:

```bash
streamlit run app/main.py
```

It will open the app in your default web browser.
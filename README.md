# Time Series Forecasting Benchmark


This project explores the benchmarking of **univariate time series forecasting**, focusing on comparing the performances of various models. The models analyzed include traditional 
**statistical models** such as **ARIMA** and **SARIMA**, as well as modern **deep learning models** like **LSTM** and **Transformer** networks. 
Additionally, the study delves into a new class of emerging technologies, **continuous deep learning models**, 
with a particular emphasis on **Liquid Time Constant Networks** and their **Closed-form Approximation**.

The benchmark is conducted using a simple univariate time series dataset, serving as a reference for all models. 
Beyond evaluating the **inference performance** of each model, the analysis also considers the **advantages and trade-offs** 
of using one class of models over others for similar forecasting tasks. 
This comprehensive approach provides insights into the conditions under which certain models may outperform others, 
facilitating more informed decision-making in model selection for time series forecasting.


------

# Requirements

| Component | Version |
|-----------|---------|
| Python    | `3.12.5`|
| pip       | `22.0.4`|

<br>
<br>

# Set Up the Python Environment

```bash
python -m venv data-analytics
```

# Download the Dependencies

```bash
python -m pip install -r requirements.txt
```
------

# Run the notebook

Clone the GitHub repo and change into the repo's directory:

```bash
git clone https://github.com/AndrewDarnall/TSF-Benchmark.git
cd TSF-Benchmark
```
From the commandline terminal (in Linux and macOS) run the following command:

```bash
jupyter-notebook ./TSF-Benchmark.ipynb --port=8086
```

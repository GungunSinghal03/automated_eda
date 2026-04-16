# 📊 Automated Exploratory Data Analysis (EDA) using ydata-profiling

## 🚀 Overview

This project performs **Automated Exploratory Data Analysis (EDA)** using the `ydata-profiling` library in Python.
It generates a detailed HTML report containing insights about the dataset, helping in faster data understanding and preprocessing.

---

## ✨ Features

* 📈 Summary statistics of dataset
* 🔍 Missing value analysis
* 📊 Correlation analysis
* 🧮 Data distribution visualization
* ⚠️ Duplicate and anomaly detection
* 📄 Interactive HTML report generation

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* ydata-profiling
* Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```
├── AutomatedEDA.ipynb   # Main notebook
├── output.html          # Generated EDA report
├── README.md            # Project documentation
```

---

## ⚙️ Installation

```bash
pip install pandas ydata-profiling
```

---

## ▶️ Usage

```python
from ydata_profiling import ProfileReport
import pandas as pd

# Load dataset
df = pd.read_csv("your_dataset.csv")

# Generate report
profile = ProfileReport(df, explorative=True)
profile.to_file("output.html")
```

---

## 📥 Output

* The script generates an **`output.html`** file
* Open it in your browser to view detailed EDA insights

---

## 📌 Use Cases

* Data preprocessing
* Machine learning pipeline preparation
* Quick dataset understanding
* Hackathons & projects

---

## ⚠️ Note

* The generated file is large for big datasets
* In Google Colab, download the file before runtime reset

---

## 🙌 Contributing

Feel free to fork this repo and improve it!

---

## 📧 Contact

For any queries or suggestions, reach out!

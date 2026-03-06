# 🍄 Mushroom Classification Web App

This is a **binary classification web application** built using **Streamlit** and **scikit-learn**. The app predicts whether a mushroom is **edible** or **poisonous** based on its features.

---

## Features

- Upload or use the included mushroom dataset (`mushrooms.csv`)
- Choose from three classifiers:
  - Support Vector Machine (SVM)
  - Logistic Regression
  - Random Forest
- Tune hyperparameters for each model
- Display performance metrics:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix
  - ROC Curve
  - Precision-Recall Curve
- Option to view the raw dataset

---

## Demo

<img width="1859" height="926" alt="demo" src="https://github.com/user-attachments/assets/ce62f63f-f48a-4a0a-abcb-7bdecc85b46c" />
<img width="968" height="715" alt="demo2" src="https://github.com/user-attachments/assets/dc8c46ae-eff7-4bc4-b480-7fb89bb81458" />

---

## Installation

1. **Clone the repository:**

```bash
git clone <your-repo-url>
cd ML\ App
````

2. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

* Open the URL shown in the terminal (usually `http://localhost:8501`) to interact with the app.
* Use the sidebar to select classifiers, adjust hyperparameters, and choose metrics to plot.
* Check **Show raw data** to view the mushroom dataset.

---

## Project Structure

```
ML APP/
├── venv/                # Virtual environment (ignored by Git)
├── app.py               # Main Streamlit application
├── mushrooms.csv        # Mushroom dataset
├── requirements.txt     # Python dependencies
└── .gitignore           # Git ignore rules
```

---

## Dependencies

* Python 3.12+
* numpy==1.27.4
* pandas==2.1.1
* matplotlib==3.8.0
* scikit-learn==1.3.0
* streamlit==1.27.0

*Install all dependencies with:*

```bash
pip install -r requirements.txt
```

---

## Notes

* `venv/` is ignored in Git, so your virtual environment won’t be uploaded.
* Metrics plots require models that support `predict_proba` or `decision_function`.
* Dataset `mushrooms.csv` is already encoded using `LabelEncoder`.

---

## Author

**MD. Mehedi Hasan Rafy**

* GitHub: [your-github-username](https://github.com/your-github-username)
* Email: [your-email@example.com](mailto:your-email@example.com)

```

---

If you want, I can also **add a “How to contribute” and “License” section** so your GitHub repo looks very professional.  

Do you want me to add that?
```

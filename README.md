# Placement Predictor (ML Model) – Toy Dataset

## Overview
This project is a simple **Machine Learning model** that predicts whether a student will get placed or not based on academic features.

The model uses a small **toy dataset** containing student CGPA and IQ scores to classify placement outcomes.  
This project demonstrates the **basic machine learning workflow** including data loading, preprocessing, visualization, model training, and prediction.

---

## Dataset

The dataset contains the following features:

| Feature | Description |
|--------|-------------|
| `cgpa` | Student's CGPA |
| `iq` | IQ score of the student |
| `placement` | Target variable (1 = Placed, 0 = Not Placed) |

Example:

| cgpa | iq | placement |
|-----|----|-----------|
| 6.8 | 123 | 1 |
| 5.9 | 106 | 0 |
| 7.4 | 132 | 1 |

---

## Project Workflow

- Data loading
- Data preprocessing
- Exploratory data visualization
- Train-test split
- Model training
- Prediction

---

## Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook / Google Colab**

---

## Model

A **classification algorithm** is used to predict student placement.

**Input Features**
```
CGPA
IQ
```

**Output**
```
Placement (0 = Not Placed, 1 = Placed)
```

---

## Project Structure

```
Placement-Predictor-MLM-Toy-DataSet
│
├── placement.csv
├── Placement_predictor_MLM.ipynb
└── README.md
```

---

## Learning Outcomes

This project helps in understanding:

- Basic Machine Learning pipeline
- Data handling using **Pandas**
- Data visualization with **Matplotlib**
- Training a classification model
- Understanding decision boundaries

---

## Future Improvements

- Use a larger and real-world dataset
- Compare multiple machine learning algorithms
- Add model evaluation metrics
- Build a web interface using **Flask** or **Streamlit**
- Deploy the model

---

## Author

**Akash Kumar**  
BCA Student  
Interested in Machine Learning, Data Science, and Web Development

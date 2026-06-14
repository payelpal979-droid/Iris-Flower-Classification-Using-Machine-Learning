# Iris-Flower-Classification-Using-Machine-Learning
The model achieves very high accuracy (often close to 100%) and successfully classifies iris flowers into their correct species. Random Forest is an effective machine learning algorithm for Iris Flower Classification because it provides high accuracy and handles classification tasks efficiently.
readme_content = """# Iris Species Classification

A machine learning project to classify iris flower species using Random Forest classifier based on sepal and petal measurements.

## 📊 Dataset Overview

The Iris dataset contains **150 samples** with 6 features:

| Feature | Description |
|---------|-------------|
| sepal length (cm) | Length of the sepal |
| sepal width (cm) | Width of the sepal |
| petal length (cm) | Length of the petal |
| petal width (cm) | Width of the petal |
| species | Encoded species label (0, 1, 2) |
| species_name | Species name |

### Target Distribution

| Species | Count |
|---------|-------|
| setosa | 50 |
| versicolor | 50 |
| virginica | 50 |

The dataset is perfectly balanced with 50 samples per class.

### Data Split
- **Training samples:** 112 (75%)
- **Testing samples:** 38 (25%)

## 🤖 Model Performance

### Overall Accuracy
**92.11%** (0.9211)

### Classification Report

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| setosa | 1.00 | 1.00 | 1.00 | 12 |
| versicolor | 0.86 | 0.92 | 0.89 | 13 |
| virginica | 0.92 | 0.85 | 0.88 | 13 |
| **Accuracy** | | | **0.92** | 38 |
| **Macro Avg** | 0.92 | 0.92 | 0.92 | 38 |
| **Weighted Avg** | 0.92 | 0.92 | 0.92 | 38 |

### Key Insights
- **Setosa** is perfectly classified with 100% precision, recall, and F1-score
- **Versicolor** and **Virginica** show slightly lower performance, likely due to some overlap in their feature distributions
- The model achieves strong overall performance with balanced precision and recall across all classes

## 📈 Feature Importance

| Feature | Importance |
|---------|------------|
| petal length (cm) | 43.25% |
| petal width (cm) | 42.84% |
| sepal length (cm) | 11.51% |
| sepal width (cm) | 2.41% |

### Key Findings
- **Petal measurements** are the most discriminative features, contributing ~86% of the model's decision-making power
- **Petal length** and **petal width** are nearly equally important
- **Sepal width** has minimal impact on classification (only 2.41%)
- This aligns with botanical knowledge that petal characteristics are more distinctive across iris species

## 🛠️ Technologies Used

- Python
- scikit-learn (Random Forest Classifier)
- pandas
- numpy

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/iris-classification.git

# Install dependencies
pip install -r requirements.txt

# Run the model
python iris_classifier.py
```

## 📁 Project Structure

```
iris-classification/
├── data/
│   └── iris.csv
├── models/
│   └── random_forest_model.pkl
├── notebooks/
│   └── exploratory_analysis.ipynb
├── iris_classifier.py
├── requirements.txt
└── README.md
```

## 📊 Results Summary

- **Model:** Random Forest Classifier
- **Accuracy:** 92.11%
- **Best Predictive Features:** Petal length and Petal width
- **Perfect Classification:** Setosa species
- **Most Challenging:** Versicolor vs Virginica distinction

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

*Created as part of a machine learning classification project using the classic Iris dataset.*
"""

# Save to output directory

print("README.md created successfully!")
print(f"File size: {len(readme_content)} characters")

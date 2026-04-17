[readmefile.md](https://github.com/user-attachments/files/26821742/readmefile.md)
# 🩺 Breast Cancer Prediction

## 📁 Files

- **`Breast_cancer_data.csv`** – Dataset with mean radius, texture, perimeter, area, smoothness, and diagnosis (0 = benign, 1 = malignant).
- **`Breast_cancer_data.ipynb`** – Jupyter notebook for data exploration, feature scaling, and training a Gaussian Naive Bayes model.

## 📊 Dataset

- **569 samples**, 6 columns (5 features + target)
- Target: `diagnosis` (0 = Benign, 1 = Malignant)

## 🔧 Steps

1. Load and explore data (head, shape, info, null check)
2. Visualize correlation heatmap and class distribution
3. Split features (`X`) and target (`y`)
4. Apply `StandardScaler` for normalization
5. Train `GaussianNB` model
6. Evaluate with accuracy score and confusion matrix

## 📈 Results

- **Test Accuracy: ~94.7%**
- Confusion matrix visualizes true/false positives and negatives

## 📦 Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

# 📈 Task 1 – PDF and CDF of Iris Dataset

## 🧠 Objective

The goal of this task is to visualize the **Probability Density Function (PDF)** and the **Cumulative Distribution Function (CDF)** for each feature in the **Iris dataset**. These visualizations help in understanding the distribution and behavior of data features.

## 📋 Description

1. Load the Iris dataset using `scikit-learn`.
2. For each feature in the dataset:
   - **Plot the PDF** using a histogram with `density=True` to approximate the probability density.
   - **Plot the CDF** by sorting the data and computing the cumulative sum of probabilities.

The four features in the Iris dataset are:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 📊 Output

The task produces:
- 📌 4 PDF plots — one for each feature
- 📌 4 CDF plots — one for each feature

Each plot should include:
- Appropriate axis labels
- Clear titles
- Gridlines (optional but recommended)
- Legend (if needed)

## 📦 Tools Used

- Python
- NumPy
- Matplotlib
- Scikit-learn

## 📁 File

- `task1_iris_pdf_cdf.py`: Contains the implementation for plotting PDFs and CDFs for all Iris dataset features.

---

## 📝 Notes

- Make sure to scale histograms properly using `density=True` when plotting PDFs.
- Sort the data before computing CDF values to ensure accurate plots.

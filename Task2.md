# Q-Q Plot for Normality Check

This project demonstrates how to use **Q-Q (Quantile-Quantile) plots** to visually assess whether a dataset follows a normal distribution.

## 📊 Objective

The goal is to generate synthetic datasets and verify their normality using Q-Q plots. This is a common preprocessing step in statistical analysis and machine learning, where many models assume normally distributed data.

## 🧪 Datasets

1. **Dataset 1**: 1000 points drawn from a normal distribution.
2. **Dataset 2**: 1500 points drawn from a normal distribution.

## 🔍 What is a Q-Q Plot?

A **Q-Q plot** compares the quantiles of your dataset against the quantiles of a theoretical distribution (in this case, the normal distribution). If the data is normally distributed, the points in the Q-Q plot will approximately lie on a straight diagonal line.

## 🧰 Libraries Used

- `numpy` – for generating random data
- `scipy.stats` – for statistical functions including `probplot`
- `matplotlib` – for plotting the Q-Q plots

## 📁 File Structure

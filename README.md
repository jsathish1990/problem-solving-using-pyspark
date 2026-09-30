# PySpark Notebooks

Notebooks and datasets for the Udemy course **Problem Solving using PySpark - Regression & Classification**:
https://www.udemy.com/course/problem-solving-using-pyspark-regression-classification/

All the analysis in the Jupyter notebooks in this folder is from references in Medium or TDS (Towards Data Science).

The notebooks were vetted with Claude Code.

## Datasets

The datasets below are from the UCI Machine Learning Repository and are shared under the CC BY 4.0 license.

- **MetroPT-3 Dataset** (Segment 2 - Descriptive Statistics). Not included in this repository because of its size (209 MB). Download it from UCI; see `Segment 2 - Descriptive Statistics/README.md`.
  Davari, N., Veloso, B., Ribeiro, R., & Gama, J. (2021). MetroPT-3 Dataset [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5VW3R

- **Electrical Grid Stability Simulated Data** (Segment 4 - Regression, Segment 5 - Classification).
  Arzamasov, V. (2018). Electrical Grid Stability Simulated Data [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5PG66

- **Sentiment Labelled Sentences** (Segment 6 - Text Analytics).
  Kotzias, D. (2015). Sentiment Labelled Sentences [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C57604

Other datasets:

- Black Friday Sales (Segment 3 - Data Cleaning): https://www.kaggle.com/datasets/rajeshrampure/black-friday-sale
- Store Item Demand Forecasting (Segment 7 - Time Series): https://www.kaggle.com/competitions/demand-forecasting-kernels-only

## Running the notebooks

The notebooks were written for Google Colab and read data from Google Drive (`/content/drive/MyDrive/...`). To run them with the data in each segment folder, change the path to the file name and skip the `drive.mount(...)` cell.

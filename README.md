# Mall Customer Segmentation

This project uses K-means clustering to segment 200 mall customers by annual income and spending score. The notebook explores the data, standardizes both features, plots the elbow curve, and profiles three customer segments.

[View the notebook](Mall%20Customer%20Segmentation%20Analysis.ipynb) · [View the dataset](Mall_Customers.csv)

## Results

| Segment | Customers | Average annual income | Average spending score |
| --- | ---: | ---: | ---: |
| Lower income, mid score | 123 | $44.2k | 49.8 |
| Higher income, high score | 39 | $86.5k | 82.1 |
| Higher income, low score | 38 | $87.0k | 18.6 |

The two higher-income groups earned about the same on average, yet their spending scores differed by about 63 points.

The notebook uses three clusters. In a separate check across 2–7 clusters, five clusters had the highest silhouette score (0.555 vs. 0.467 for three). The dataset has no campaign outcomes, so the suggested marketing strategies would need to be tested.

## Run locally

Install Jupyter Notebook, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn. Keep the CSV beside the notebook. Open the notebook, set the first cell to Markdown if it is still set to Code, then run all cells.

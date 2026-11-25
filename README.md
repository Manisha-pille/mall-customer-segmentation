# Mall Customer Segmentation

Grouping 200 mall customers into segments by income and spending, using K-Means clustering.

## What I did
- Cleaned and scaled the data
- Chose 5 groups with the elbow method
- Built the groups with K-Means (silhouette score: 0.555)
- Named each group and described who they are

## Results

| Segment | Customers | Who they are |
|---|---|---|
| Average shoppers | 40.5% | Medium income, medium spending |
| Premium targets | 19.5% | High income, high spending |
| Careful high earners | 17.5% | High income, low spending |
| Budget savers | 11.5% | Low income, low spending |
| Impulsive spenders | 11.0% | Low income, high spending |

## Key finding
Income doesn't decide spending. The biggest opportunity is the "Careful high earners": they have money but spend little.

## Tools
Python, Pandas, Matplotlib, scikit-learn

## Files
- `mall_customer_segmentation.ipynb`: full analysis
- `Mall_Customers.csv`: dataset ([source on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python))

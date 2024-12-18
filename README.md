# Comparative Study of Support Vector Regression and Linear Regression on a YouTube Dataset

This project analyzes performance metrics for a YouTube channel using Python. It uses a dataset containing key metrics like video views, subscriber count, watch time, revenue, and engagement statistics. The goal is to compare the performance of Support Vector Regression (SVR) and Linear Regression in predicting various metrics.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dependencies](#dependencies)
- [Setup and Usage](#setup-and-usage)
- [Key Metrics and Insights](#key-metrics-and-insights)
- [Challenges](#challenges)
- [Contributor](#contributor)
- [License](#license)

## Project Overview
This project involves:
- Loading and exploring a dataset of YouTube video performance analytics.
- Cleaning and preprocessing the data.
- Performing exploratory data analysis (EDA) using Python libraries like Pandas, Matplotlib, and Seaborn.
- Comparing the effectiveness of Support Vector Regression (SVR) and Linear Regression in predicting video performance metrics.

## Features
The project focuses on analyzing:
- **Video Metrics**: Duration, views, impressions, click-through rates (CTR), and engagement.
- **Revenue Metrics**: Estimated revenue, revenue per 1000 views, and monetized playbacks.
- **Engagement Metrics**: Subscriber growth, likes, comments, and shares.

## Dependencies
The following libraries are required to run the notebook:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Setup and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-analytics.git
   cd youtube-analytics
   ```

2. Ensure that the dataset `youtube_channel_real_performance_analytics.csv` is present in the working directory.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

4. Run the cells sequentially to:
   - Load and explore the dataset.
   - Generate visualizations and insights.
   - Compare the performance of SVR and Linear Regression models.

## Key Metrics and Insights
### Example Insights:
- **SVR vs. Linear Regression**: Evaluation of model performance on metrics like R², Mean Squared Error, and accuracy of predictions.
- **Video Duration vs. Engagement**: Analysis of how video duration impacts watch time and viewer retention.
- **CTR Analysis**: Insights into thumbnail and end-screen click-through rates.
- **Revenue Optimization**: Identifying trends in revenue-per-view and monetized playbacks.

## Challenges
- **Small Dataset**: The dataset is relatively small, with only 364 entries. This limits the robustness of certain analyses and makes it challenging to generalize findings.

## Contributor
- **Emre Erdin** - Data Scientist and Creator of this project.

## License
This project is open-source and available under the MIT License.
# Comparative-Study-of-Support-Vector-Regression-and-Linear-Regression-on-a-YouTube-Dataset

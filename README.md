# ScalableAnalytics-Facebook-Ads-Analysis-with-PySpark

## Overview

This project analyzes Facebook Ads data using PySpark and Apache Spark on a distributed cluster. It applies text processing, topic modeling (LDA), and time-series analysis to extract insights from large-scale advertising data.

## Repository Structure

```
ScalableAnalytics-Facebook-Ads-Analysis-with-PySpark
│── README.md                # Project overview & instructions
│── requirements.txt          # Python dependencies
│── notebooks/
│   ├── facebook_ads_analysis.ipynb  # Jupyter Notebook for reference
│── reports/
│   ├── project_report.pdf    # Final report summarizing insights
│── images/
│   ├── wordcloud_topic1.png  # Word cloud for topic 1
│   ├── wordcloud_topic5.png  # Word cloud for topic 5
│   ├── sentiment_distribution.png  # Sentiment distribution plot
│   ├── feature_count_vertical.png  # Feature count (vertical)
│   ├── feature_count_horizontal.png  # Feature count (horizontal)
```

### Important Notice

This project is not directly reproducible because:

- The dataset was hosted on the master node of a university cluster and is no longer accessible.

- The analysis was performed during the lecture period, and the dataset was removed after the course ended.

However, the methodology, code, and report provide a detailed process that can be adapted to other datasets.

## Technologies Used

- Big Data Processing: PySpark, Apache Spark

- Machine Learning: LDA (Latent Dirichlet Allocation)

- Visualization: Matplotlib, WordCloud

- Storage & Computing: Hadoop HDFS (Cluster-Based Processing)

## What I've done in this project

1. Feature Engineering & Data Preprocessing:

  - Extracted and cleaned ad text content.

  - Processed advertising metadata, including impressions, spend, and engagement metrics.

  - Applied TF-IDF transformation to prepare text data for topic modeling.


2. Topic Modeling with LDA:

  - Performed Latent Dirichlet Allocation (LDA) clustering to identify key topics within ad texts.

  - Mapped high-impact words to topics, revealing themes related to political discourse, environmental issues, and economic policies.


3. Trend Analysis & Visualization:

  - Analyzed topic volume trends over time, highlighting shifts in advertising focus.

  - Generated word clouds to visualize dominant terms in each topic.

  - Explored spending patterns across different ad categories and topics.


4. Findings & Insights:

  - Identified key advertising themes and their evolution over time.

  - Discovered correlations between ad spending and audience engagement.

  - Highlighted demographic distribution trends in targeted advertisements.


## Future improvement
- Adapt this approach for real-time ad trend analysis.

- Integrate streaming data pipelines for continuous insights.

- Optimize Spark configurations for large-scale processing.

# Recommendation System Using Amazon Reviews

![Title](Title_Amazon.png)

## Overview
This project presents a custom hybrid recommender system that utilizes various models to provide product recommendations to users. The project's primary goal is to offer valuable and relevant product recommendations, even when dealing with limited user data. The methodology includes product clustering with K-means and a custom hybrid recommendation algorithm employing Frequent Itemset Mining (FIM), Content-Based Recommender System, and Popularity-Based Recommender System as visualized below.

![Recsys360](RecSys360%20Algorithm.png)

The results include eight product clusters and the RecSys 360 algorithm, which can recommend products through three different pipelines. Recommendations for further optimization and utilization are also provided, including promoting specific products, incentivizing user reviews, and considering demographic data. RecSys 360 is a versatile tool for enhancing user experience, revenue, and research in recommendation systems.

## Dataset

The [Amazon Customer Reviews Dataset](https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset) from Kaggle is a valuable resource with over two decades of customer reviews and opinions on Amazon.com products. It consists of millions of reviews that provide insights for researchers in Natural Language Processing (NLP), Information Retrieval (IR), and Machine Learning (ML), among other fields. This dataset is designed to represent customer evaluations, regional variations in product perception, and potential promotional bias in reviews, making it a rich source for various research disciplines related to understanding customer product experiences.

## Installation

To run this project, you can set up the required environment by installing the necessary packages using the provided `requirements.txt` file:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the [MIT License](LICENSE).
# Toothpaste Customer Review Text Classification & Prediction

## Scope & Objective

The aim of the project is to critically analyze and evaluate the effectiveness of text classification and prediction models applied to customer feedback, specifically for toothpaste reviews. The focus is on the use of AI to generate a synthetic dataset and the subsequent application of various classification models to accurately categorize the feedback into positive or negative sentiments.

## Data Generation Using ChatGPT:
- Dataset Composition: The dataset consists of 1,000 synthetically generated toothpaste reviews, with an equal split of 500 positive and 500 negative reviews.
- Generation Techniques: The reviews were generated to mimic real-world variations in language and style. Key generation conditions included ensuring uniqueness, expression variety, and the reflection of real-world communication patterns in the reviews.
- Objective: The synthetic dataset aims to tackle common challenges such as class imbalance and to provide a balanced foundation for model training.

## Model Deployment and Evaluation:
- Models Used: The study utilized Fasttext and Nearest Centroid algorithms to classify the reviews.
- Evaluation Metrics: The models were evaluated based on their precision and recall. The study placed a particular emphasis on the recall metric to minimize the impact of false negatives, which are more costly and impactful in a business context.

## Business Impact Analysis:
- Cost Implications: The document details the financial impact of misclassified feedback, emphasizing the importance of accurate classification to prevent customer dissatisfaction and potential financial losses.
- Importance of High Recall: Given the high costs associated with false negatives, the study highlights the strategic need for models with high recall to reduce the risk of misinterpreting negative sentiments as positive.

## Limitations and Challenges:
- Model Limitations: The analysis acknowledges limitations in the Fasttext model, particularly its focus on subwords, which may fail to capture the full context of the feedback.
- Data Generation Challenges: It also points out potential issues with synthetic data generation, such as the risk of non-authenticity and the difficulty of ensuring diversity and uniqueness across a large dataset.

## Findings and Recommendation:
- The findings suggest that while synthetic data generation using ChatGPT is efficient and cost-effective, it is crucial to address its limitations for practical application.
- Recommendations: The document recommends further exploration of different NLP algorithms to identify the most effective solutions for specific text classification tasks, enhancing both the accuracy and applicability of the models in real-world scenarios.

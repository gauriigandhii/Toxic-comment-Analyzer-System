# Toxic-comment-Analyzer-System
In the era of widespread digital communication, maintaining a positive and respectful online environment has become increasingly challenging. Toxicity in user-generated content can harm individual well-being and disrupt community dynamics. To address this, our project, Toxic Comment Classification and User Detection System, aims to identify and quantify harmful behavior by analyzing user comments for potential toxicity.

This system leverages a fine-tuned BERT model to classify comments into six predefined categories: Toxic, Severe Toxic, Obscene, Identity Hate, Insult, and Threat. Our dataset consists of approximately 20,000 comments, which serve as the foundation for training and evaluating the model's performance. Upon classification, each comment is assigned a probabilistic score, reflecting its degree of toxicity.

The backend server plays a pivotal role in aggregating these scores for each user by linking them to their unique user ID. Based on these aggregated scores, users are ranked, and the top 5% of users with the highest scores are flagged as potentially contributing the most toxic content.

To provide actionable insights, the system generates comprehensive statistical reports. These include visualizations, such as graphs and charts, showcasing the distribution of comments across toxicity categories. The results are intended to assist organizations in monitoring their user database, identifying high-risk users, and implementing strategies to reduce toxicity in their platforms.

This project not only highlights the technical feasibility of using advanced machine learning techniques for toxicity detection but also underscores the societal importance of fostering healthier online interactions.

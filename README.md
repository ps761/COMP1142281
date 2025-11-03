As part of the COMP647 – Machine Learning Fundamentals course, this project explores a used car price dataset to demonstrate the practical application of machine learning techniques to a real-world predictive problem.

The course emphasizes solving industry-relevant challenges through data-driven approaches, applying various supervised and unsupervised learning algorithms to uncover meaningful insights. The goal is to identify how different car attributes — such as model, year, mileage, ownership, and fuel type — influence resale prices in the Indian used car market.

The exploratory data analysis (EDA) and modeling stages are designed to answer the key question:
“What car features most strongly influence used car prices, and how accurately can we predict resale value using machine learning?”

This investigation is structured around two main perspectives:

Feature Behavior: Understanding how attributes like car age, kilometers driven, and brand type affect value depreciation.

Market Segmentation: Exploring regional and categorical price variations using clustering (K-Means) to identify price tiers and market trends.

How to Run
Create a new conda environment (with Python 3.10)
conda create -n ml_cyber_env python=3.10

Activate the environment
conda activate ml_cyber_env

Install the required packages
pip install -r requirements.txt

Install ipykernel if needed
conda install ipykernel

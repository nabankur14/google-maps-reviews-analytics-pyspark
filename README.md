# Google Maps Reviews Analytics & Big Data Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

![Project Thumbnail](End%20-%20Thumbnail.png)

End-to-end big data analytics pipeline on 500K+ Google Maps business reviews using PySpark, NLP, ALS Collaborative Filtering (RMSE 0.9896), ARIMA time series forecasting, and seasonal decomposition — delivering actionable business intelligence on customer behavior, review trends, and personalized recommendations.

## Project Overview
This project constructs a scalable analytical engine optimized for massive user interaction data. By processing unstructured textual reviews alongside temporal checkpoints, the architecture extracts latent business vectors and optimizes decision support capabilities.

👉 [Open the notebook to explore full analysis](PySpark-Powered-google_maps_reviews_nlp_als_arima_analysis.ipynb)

## Business Problem
Modern organizations operating local branches struggle to efficiently parse hundreds of thousands of raw, multi-category consumer logs. Stakeholders and executives require centralized intelligence reporting to predict client churn, optimize customer service, and boost retention using granular trend analysis.

## Dataset
- **Source:** Google Maps Reviews Data Lake
- **Size:** 500,000+ unique customer records
- **Key features:** `user_id`, `gmap_id`, `rating`, `text`, `time`, `category`
- **Data types:** `String` identifiers, `Float` review metrics, `BIGINT` UNIX timestamps

## Methodology
### Data Understanding / Data Cleaning / Data Preprocessing
- Applied strict Spark transformations to handle null strings uniformly.
- Performed timestamp conversions translating Unix epoch counts into accessible chronological logs.

### Exploratory Data Analysis
- Modeled review frequencies to uncover peak bimodal activity ranges.
- Compiled frequency dictionaries rendering informative evaluation clusters.

### Modeling & Evaluation
- Developed Alternating Least Squares frameworks generating target distributions.
- Supported ongoing ARIMA projections smoothing variance.

## Key Results
- Evaluated foundational predictive boundaries achieving robust generalization properties.

## Business Impact
- Enables automated product recommendations targeting priority segments safely.

## Skills

### Technical Skills
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-77AC1D?style=for-the-badge&logo=seaborn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Exploratory Data Analysis](https://img.shields.io/badge/Data_Analysis-FFA500?style=for-the-badge&logo=google-analytics&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=white)

### Soft Skills
![Analytical Thinking](https://img.shields.io/badge/Analytical_Thinking-4B0082?style=for-the-badge&logo=mindmap&logoColor=white)
![Communication](https://img.shields.io/badge/Communication-25D366?style=for-the-badge&logo=google-messages&logoColor=white)
![Problem Solving](https://img.shields.io/badge/Problem_Solving-FF4500?style=for-the-badge&logo=brainly&logoColor=white)
![Attention to Detail](https://img.shields.io/badge/Attention_to_Detail-00CED1?style=for-the-badge&logo=google-search-console&logoColor=white)

## Key Learnings
- Gained core distributed computational strategies utilizing memory caches.

## Future Improvements
- Scaling deep neural structures across heavier pipelines.

## 👨💻 Author
 **Nabankur Ray** 
 
 Passionate about real-world data-driven solutions
 
 [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat&logo=github)](https://github.com/nabankur14) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/nabankur-ray-876582181/) 
 
![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=nabankur14&show_icons=true)

⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!

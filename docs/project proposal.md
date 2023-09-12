### Project Title: Automated Skills Extraction from Job postings through Machine Learning 

This project proposal is prepared for UMBC Data Science Master Degree Capstone by Dr Chaojie (Jay) Wang.

- Author Name: Avanti Dasre
- Link to the author's GitHub profile: https://github.com/ad-04
- Link to the author's LinkedIn profile: https://www.linkedin.com/in/avanti-dasre-7a3a8b152/
- Link to your PowerPoint presentation file : https://1drv.ms/p/s!AlbITO6Fex1YcBVS3BYXCHsEg3I
- Link to your YouTube video : In Progress

## Problem Statement & Background:
The primary objective of this project is to develop a classification model capable of predicting key skills using the job descriptions. This task involves natural language processing (NLP) techniques such as Bag of words, TF-IDF, Word vectors, etc to analyze unstructured text data. Importantly, a job description will contain multiple skills required for that job, hence this task involves use of multi class - multi label classification techniques.
The problem of Automated Skills Extraction plays a pivotal role in automated resume matching and candidate shortlisting in Application tracking systems and in the job recommendation system. In addition to efficient job-candidates matching, this project has other practical applications in data collection for Labour Market & Skill Gap Analysis. 

By end of this project, I hope to explore & find answers to following research questions:

- What type of data cleaning & preprocessing techniques are effective for parsing and extracting skills from unstructured text data?
-	How accurately can machine learning models predict skills required for diverse job descriptions?
- How do traditional machine learning techniques such as naive bayes and decision trees compare to deep learning architectures such as Transformers for skills extraction.
- Can the automated skills extraction process be fine-tuned for specific industries or job sectors to improve accuracy?

## Dataset

Data Sources: I primarily plan to use the dataset collected from a Singaporean job website (mycareersfuture.sg). The dataset is available in Json format.

Dataset link: https://github.com/WING-NUS/JD2Skills-BERT-XMLC/tree/main/data

Dataset Stats: 
- Number of job posts - 20,298
- Number of distinct skills - 2,548
- Number of skills with 20 or more mentions - 1,209
- Average skill tags per job post - 19.98

This dataset includes the following metadata fields on which can be do Exploratory Data Analysis

-	company_name
-	job_title
-	employment_type
-	seniority
-	job_category
- location
-	salary
-	min_experience
-	skills_required
-	requirements_and_role
-	job_requirements
-	company_info
-	posting_date
-	expiry_date
-	no_of_applications

## Phase 2: Exploratory Data Analysis

-	Analyze distribution of different target classes (skills in this case).
-	Use metadata available to analyze the data & create visualizations 
-	Text analysis such as most frequent words with help of word cloud.
-	Analyze Bi-grams/Tr-igrams extracted from the job description.

## Phase 3: Data preparation & Model Building

-	Data splitting: There will be imbalance due to the real world nature of some skills being more prevalent than others. Hence stratified sampling must be used to split the dataset into training and validation datasets.
-	Tokenize & Clean text data: Use Nltk & regular expression to preprocess/clean the text data.
-	Text Feature Extraction: Use simple techniques such as bag of words, tf-idf & word vectors.
-	Start with simple ML models using Naive Bayes, Logistic Regression & Random forests.
-	Experiment with deep learning architectures based on GRU, LSTMs and word vectors.
-	Use pretrained models such as BERT, GPT & finetune the classification layer for the accurate predictions.
- sing the trained model in a Web Application:
-	Use gradio to build a simple web application where users can provide input text and get predictions for the skills found.-

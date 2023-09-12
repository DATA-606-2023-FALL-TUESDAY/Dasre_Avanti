  ### Project Proposal

## 1. Project Title : Data Acquisition and Pre-Processing  
## Topic Movie Script Analysis matters


- Prepared for UMBC Data Science Master Degree Capstone by Dr Chaojie (Jay) Wang
- Author Name :  Avanti Dasre
- Link to GitHub profile : https://github.com/ad-04
- Link to Linkedin : https://www.linkedin.com/in/avanti-dasre-7a3a8b152/
- Link to your PowerPoint presentation file : In progress
- Link to your YouTube video : In Progress


## 2. Background 

- Movies serve as a cultural expression, capturing the essence of different societies. They hold a significant position as an art form, offering not only entertainment but also historical significance. Films act as a powerful global communication channel, bridging gaps between diverse regions. This code aims to construct a dataset that can shed light on the factors behind both unsuccessful and successful movies. Such insights can be particularly valuable for franchises like Harry Potter, Twilight, Star Wars, and Marvel, where directors can leverage the information from the summary sheet to enhance future installments of their films. Ihave choosen TWilight for my project. The movie "Twilight" was released in 2008, and it falls into the genre of American romantic fantasy. It's an adaptation of Stephenie Meyer's novel, which was published in 2005 and shares the same title. Catherine Hardwicke directed the film, and it features Kristen Stewart and Robert Pattinson in prominent roles. This movie serves as the inaugural installment in "The Twilight Saga" film series.

According to Rotten Tomatoes, which aggregated 219 reviews, "Twilight" holds a rating of 49%, with a weighted average score of 5.41/10.

For an upcoming project, I'll be working with the screenplay of the film, which is available in PDF format and spans 174 pages.
I hope to create a summary sheet which will have conversations between that characters per scene. For each movie scene and the characters, I will provide a rating. Apart from this, I will also gather the ratings and feedback provided to the movie from different critics' such as IMDB, rotten tomato, and google, decided to work on this script because of its average rating, as it will give me a good opportunity to analyze the data and produce a better dataset.



## why does it matters?

- Data acquisition and pre-processing are essential stages in movie script analysis. They ensure that the data used for analysis is accurate, well-structured, and ready for advanced natural language processing techniques. Quality data enhances the accuracy of insights derived from movie scripts, whether for academic research, industry applications, or content recommendation systems. Proper pre-processing is crucial for identifying trends, patterns, and sentiment in dialogues and scenes, ultimately benefiting scriptwriters, directors, and producers in their decision-making processes.


##  Research questions ?

- Predictive Modeling: Develop predictive models to forecast a movie's box office success or audience reception based on script features.

- Character Network Analysis: Apply network analysis to character interactions to uncover central characters, relationships, and their impact on plot dynamics.

- Genre-specific Insights: Investigate genre-specific patterns in scripts using natural language processing to understand audience preferences.

- Script Adaptation Study: Analyze script and source material data to gain insights into challenges and creative decisions made during adaptation processes.

- Content Recommendations: Integrate movie script data into content recommendation systems to enhance the accuracy of movie suggestions for viewers based on their preferences.


## 3. Data 

Describe the datasets you are using to answer your research questions.

- Data source : An open-source where vast number of scripts available. https://imsdb.com/Movie%20Scripts/Twilight%20Script.html. Apart from this, I will  use other open-sources like imbd, rotten tomato, google review.. 

- Data shape (995 rows × 2 columns)
  
- **What does each row / represent?(a patient, a school, a crime, etc.)**   (In Progress)
  - speaker,dialogs 
  

## 4. Exploratory Data Analysis (EDA)

- Perform data exploration using Jupyter Notebook
- You would focus on the target variable and the selected features and drop all other columns.
- produce summary statistics of key variables
- Create visualizations (I recommend using **Plotly Express**)
- Find out if the data require cleansing:
  - Missing values?
  - Duplicate rows? 
- Find out if the data require splitting, merging, pivoting, melting, etc.
- Find out if you need to bring in other data sources to augment your data.
  - For example, population, socioeconomic data from Census may be helpful.
- For textual data, you will pre-process (normalize, remove stopwords, tokenize) them before you can analyze them in predictive analysis/machine learning.
- Make sure the resulting dataset need to be "tidy":
  - each row represent one observation (ideally one unique entity/subject).
  - each columm represents one unique property of that entity. 

## 5. Model Training 

- What models you will be using for predictive analytics?
- How will you train the models?
  - Train vs test split (80/20, 70/30, etc.)
  - Python packages to be used (scikit-learn, NLTK, spaCy, etc.)
  - The development environments (your laptop, Google CoLab, GitHub CodeSpaces, etc.)
- How will you measure and compare the performance of the models?

## 6. Application of the Trained Models

Develop a web app for people to interact with your trained models. Potential tools for web app development:

- **Streamlit** (recommended for its simplicity and ease to learn)
- Dash
- Flask

## 7. Conclusion

- Summarize your work and its potetial application
- Point out the limitations of your work
- Lessons learned 
- Talk about future research direction

## 8. References 

List articles, blogs, and websites that you have referenced or used in your project.

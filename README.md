# DebateAnalysis
Vice Presidential and Presidential Debate Analysis using Data Science Debate Analysis using Data Science: Using YouTube Comments to find the true intent of voters
After getting mixed results from the news sources, I thought to analyze the Vice Presidential and Presidential debates using Data Science.
 The idea is to use YouTube comments as a medium to get the sentiment regarding the debate and getting insights from the data. In this analysis, we plot common phrases, common words, we also analyze sentiment and in the end for all my data science practitioners I present them a full-fledged dataset containing YouTube Comments of VP and Presidential debates.
 
Why: After getting mixed results from the news sources about the outcome of the debate, I decided to use data science to help me see the outcome of the result. With the elections around the corner, technology or to be precise analytics plays a key role in shaping our thoughts and supporting our hypothesis.
How: To Analyze YouTube Comments we use Python and various other NLP Libraries followed by some data visualization tools. We will use the wonders of the awesome data wrangling library known as Pandas and we hope to find some interesting insights.

# Creation
The dataset contains YouTube comments on the most popular/watched VP and Presidential debates. We use the YouTube Data API to get all comments (Due to the size limitation, we only get 100 comments per video). The videos have been selected through careful examination by the author, to be precise we focused on the highest number of views and the highest number of YouTube comments.

# YouTube Comments Extraction
The following function defines the video_ids we scrap and some basic extraction code. We get our data in the form of JSON, then we perform preprocessing and ultimately combine all comments followed by the sentiment score (using TextBlob) into a DataFrame.
 
 # Medium
 https://aaditkapoorthoughts.medium.com/vice-presidential-and-presidential-debate-analysis-using-data-science-61d542f0c974
 
# Interactive Notebook

Try here: https://notebooks.gesis.org/binder/jupyter/user/aaditkapoor-debateanalysis-v3axybkg/voila/render/debate_analysis.ipynb

# Dataset
www.kaggle.com/dataset/43532333d82042a1287e00672b86a2c76e76ffbc4d85569715309714635172b0

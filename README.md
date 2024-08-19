# Movies_Recommendation_System
whole project analysis ,building model ,website(api)

<img src='https://github.com/rpjinu/Movies_Recommendation_System/blob/main/image_Movie_recomendation.jpg' width='1200'>


# Movie Recommendation System

## Step 1: Data Collection
- Download movie data from the Kaggle website. \
- Analyze and gather additional data from two websites. 

## Step 2: Data Preprocessing
- Merge the two datasets into a single dataset. \
- Drop all unnecessary columns and handle any null values. 

## Step 3: Feature Extraction
- Use Abstract Syntax Trees (AST) for feature text extraction to convert strings. \
- Merge all feature columns to create tags. \
- Use NLTK's PorterStemmer to extract raw words.

## Step 4: Text Vectorization
- Convert the Tags column using `CountVectorizer`. 

## Step 5: Similarity Calculation
- Use Cosine Similarity to measure the similarity between movie tags. \
- Cosine similarity measures the cosine of the angle between two vectors in a multi-dimensional space. \
- It is commonly used to measure similarity between text documents or feature vectors in machine learning.

## Step 6: Exporting the Model
- Export the similarity model using `pickle`.

## Step 7: API Development
- Go to PyCharm and create an API using Streamlit. 

## Step 8: Deployment
- Deploy the API on Heroku.
- deploy image heroko\

<img src='https://github.com/rpjinu/Movies_Recommendation_System/blob/main/api_streamlit.jpeg' width='1200'>

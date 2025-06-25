# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : MURARI YAMINI

*INTERN ID* : CT04DF2780

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* : This project demonstrates how to create a simple but effective Sentiment analysis model using Natural Language Processing (NLP) techniques. This task focuses 

on analyzing customer reviews and classify them as positive reviews and negative reviews.

We make use of Python libraries such as NLTK (natural language tool kit), scikit-learn, pandas, and matplotlib and seaborn to handle the whole process. For training and 

testing our model, we use  the IMDb movie reviews dataset, which is available through the NLTK corpus.

The main purpose of this project is :

  download a labeled dataset with movie reviews (1000 positive and 1000 negative)
  
   preprocess the text with popular NLP algorithms

      In the preprocessing step, we:

      converted all text to lowercase,

      removed punctuation and numbers

      removed stopwords (like "the","and","is")

      lemmatized words to reduce them to their root forms (e.g., "running" → "run")
   
  use TF-IDF vectorization to transform the cleaned text into numerical features

     TF-IDF (Term Frequency–Inverse Document Frequency) helps to identify which words are important in a document compared to the whole dataset. it gives importance to 
     
     meaning full words.

     In this code ,I limited the features to important 5000 to keep model efficient
  
  use these features to train a logistic regression model

      In LogisticRegression ,model used 60% of data for traning and 40% of data for testing
  
  use the confusion matrix, classification report, and accuracy to evaluate the model
  
  use Seaborn heatmaps to visualize performance

 *RESULT* : the model acheived 80% accuracy,which is a strong performance for a basic sentiment analysis model using machine learning

*APPLICATIONS* : this model can be used to

                 product reviews on e-commerce websites like amazon,flipcart,meesho and so on

                 social media sentiment tracking

                 customer service feedback analysis

OUTPUT : ![Image](https://github.com/user-attachments/assets/60aa8a85-1f71-44db-a4b1-33a9ea1dd8f4)

![Image](https://github.com/user-attachments/assets/42c2fca7-287c-4369-99de-927f03559b7b)

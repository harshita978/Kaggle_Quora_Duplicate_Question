# Kaggle_Quora_Duplicate_Question
"Where else but Quora can a physicist help a chef with a math problem and get cooking tips in return? Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Currently, Quora uses a Random Forest model to identify duplicate questions. In this compettiion, Kagglers are challenged to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers."

https://www.kaggle.com/c/quora-question-pairs/

## Feature_Engineering 
Some basic features used are :
Length of question1
Length of question2
Difference in the two lengths
Character length of question1 without spaces
Character length of question2 without spaces
Number of words in question1
Number of words in question2
Number of common words in question1 and question2
QRatio
WRatio
Partial ratio
Partial token set ratio
Partial token sort ratio
Token set ratio
Token sort ratio
Tf-IDF and SVD features


## MODEL
My dominant model and final submission is a single XGBoost model with different features taking refrence from - 
Referenced from : Abhishek_thakur quora_duplicate_question code.

## To Run : 
Directly use jupyter notebooks as :
1. feature notebook (ipynb files)
2. xgboost notebbok

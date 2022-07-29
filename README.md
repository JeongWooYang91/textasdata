# textasdata
Natural Language Processing (Reddit mining / classification)

Assignment goal : Classify subredding using machine learning and text processing methods

Text processing methods involved : 
1. Data cleaning (stopwords, punctuations etc)
2. Tokenization

Classification methods
Dummy classifier (control variable of experiment)
Logistic regression with one-hot encoding
Support Vector Machines
Neural Net using TensorFlow

Feature engineering :
Tried adding 2 features with the following assumptions
1. Username - In reddit (and any other online communities), there are certain users that reside in the community. They could have a strong correlation (did not work)
2. Title - Again, online communities tend to converge on similar subjects. Would you see 'Total War:Warhammer 3'(PC game) in a PC subreddit title, or a PS4 subreddit?

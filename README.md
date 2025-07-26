# SENTIMENT-ANALYSIS-WITH-NLP



Sentiment Analysis – Simple Review Classifier
🔸 What I did:
I made a small project where I taught a computer how to understand if a review is positive or negative.
Basically, if someone says "I love this product", it should say it's positive.
If someone says "I hate it", it should say negative.


📦 What data I used:
I created 50 fake reviews myself.
25 were positive like “Great product!”, “Works perfectly”, etc.
25 were negative like “Waste of money”, “Doesn’t work at all”, etc.
Each review had a label: 1 for positive, 0 for negative.


🧪 What steps I followed:
Made a dataset with all 50 reviews and their sentiments.
Split the data – 70% to teach the model, 30% to test it.
Changed text to numbers using something called TF-IDF. This helps the model understand the words better.
Trained a model called Logistic Regression. It tries to learn patterns between words and sentiments.
Tested the model with the remaining reviews to see if it predicts correctly.
Checked accuracy – how many reviews it got right.


🧠 What tools I used:
Python – programming language
Pandas – to make the data table
Scikit-learn – for splitting data, vectorizing text, training, and testing
TF-IDF – to convert text to numbers
Logistic Regression – simple machine learning algorithm


🎯 What I learned:
Even a simple model can give good results if the data is clean.
TF-IDF really helps the computer focus on the important words.
It’s cool to see the model predict correctly just based on text!


🔮 What I can do next:
Try this with real reviews (like Amazon or movie reviews).
Use a bigger model like Naive Bayes or SVM.
Maybe build a simple web app to enter reviews and get predictions.




The dataset contains two main columns:
Comment → raw text written by users
Emotion → label like joy, fear, or anger
Since models work with numbers, I mapped each emotion to a numeric value so the algorithm could process it properly.
⚙️ How the Project Works
:Data Loading
 Loaded and explored the text data using Pandas.
:Text to Numbers (TF-IDF)
 Used TF-IDF Vectorizer to convert text into numerical features by measuring how important each word is in a sentence.
:Train–Test Split
 Split the dataset into training and testing data to evaluate real performance.
:Model Training
 Trained a Random Forest Classifier to learn patterns between word features and emotions.
:Pipeline
Combined TF-IDF and the ML model into a single pipeline so raw text can directly go in and predictions come out.
:Evaluation
Tested the model using a classification report to measure precision, recall, and overall accuracy
This project tells that machines don’t feel emotions, they learn patterns from words.

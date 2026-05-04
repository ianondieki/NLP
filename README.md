This project contains two simple AI models:

Sentiment Analyser: Tells if a piece of text is positive, negative, or neutral.

Question Answering: Finds answers to questions when given a passage of text.

It’s designed to help beginners explore how natural language processing (NLP) works.

📂 What’s Inside
sentiment_analyser/ → code for training and testing sentiment analysis.

question_answering/ → code for training and testing question answering.

data/ → sample datasets.

requirements.txt → list of Python packages you need.

🚀 How to Run
Install Python (3.8+ recommended).

Clone this repo:

bash
git clone https://github.com/yourusername/sentiment_qna.git
cd sentiment_qna
Install dependencies:

bash
pip install -r requirements.txt
Try the sentiment analyser:

python
from sentiment_analyser import SentimentModel
model = SentimentModel.load("saved_model/")
print(model.predict("I love this!"))
Try the question answering model:

python
from question_answering import QnAModel
context = "Paris is the capital of France."
question = "What is the capital of France?"
print(QnAModel.answer(context, question))
📊 What You’ll Learn
How text is processed for machine learning.

How models are trained and evaluated.

How to use metrics like accuracy and F1 score.

🤝 Contributing
If you’d like to improve this project, feel free to fork it and submit a pull request.

📜 License
MIT License — free to use and share.

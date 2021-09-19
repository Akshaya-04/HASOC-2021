# HASOC-2021
Automated recognition and detection of Hate Speech and Offensive language on different Online Social Networks, mainly Twitter, presents a challenge to the community of Artificial Intelligence and Machine Learning. Unfortunately, sometimes these ideas communicated via the internet are intended to promote or incite hatred or humiliation of an individual, community, or even organizations. The HASOC shared task is to attempt to automatically detect abusive language on Twitter in English and Indo-Aryan Languages like Hindi. To participate in this task and provide our input, we (team Data Pirates) presented several machine learning models for Hindi Subtasks. The datasets provided allowed the development and testing of supervised machine learning techniques. The top 2 performing models for sub-task A were Naïve Bayes and Logistic Regression with the same Macro F1 score of 0.7394. The top 2 performing models for sub-task B were Logistic Regression and CatBoost, with Macro F1 scores of 0.4828 and 0.4709, respectively. This overview intends to provide detailed understandings and to analyze the outcomes.

Sub-task A: This sub-task mainly aims at the binary classification of Hate speech and Offensive language identification and is offered for English, Hindi, and Marathi. We chose our language as Hindi for model building and evaluation. The submitted model is expected to categorize the tweets into two classes, i.e., Non- Hate Offensive (NOT) and Hate and Offensive (HOF).
1.	Non-Hate Offensive (NOT) - Said tweet does not include any Hate Speech and/or Offensive content.
2.	Hate and Offensive (HOF) - Said tweet includes Hate, Offensive, and/or Profane content.
The training dataset was labelled and annotated for both the sub-tasks. The testing dataset only included the tweet content. The model must separately predict the labels for both sub-tasks.
Sub-task B: This sub-task targets the fine-grained classification of sub-task A. Tweets marked as HOF in sub-task A are additionally categorized into three classes.
1.	(OFFN) Offensive: Tweets comprising offensive content.
2.	(HATE) Hate speech: Tweets comprising Hate speech content.
3.	(PRFN) Profane: Tweets comprising profane words


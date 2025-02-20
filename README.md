📊 Sentiment Analysis on Twitter
An NLP Project with Machine Learning

📌 Description
This project analyzes the sentiment of tweets using Natural Language Processing (NLP) techniques and Machine Learning models. Various approaches have been tested, including Naïve Bayes, Logistic Regression, and BERT/DistilBERT, to evaluate their accuracy in classifying tweets as positive or negative.

Additionally, topic modeling with LDA was explored, to extrapolate topics from the tweets.

🛠️ Technologies Used
Python Libraries: pandas, numpy, scikit-learn, torch, transformers, gensim, nltk
Machine Learning Models: Naïve Bayes, Logistic Regression, BERT, DistilBERT
Topic Modeling: LDA (Latent Dirichlet Allocation)
Visualization: matplotlib, seaborn, wordcloud, pyLDAvis
Interactive Interface: Streamlit for presenting results

🚀 Project Structure
📂 sentiment-analysis/
├── dataset/ → Contains the dataset used for analysis
├── notebooks/ → Jupyter notebooks with the code
├── streamlit_app/ → Streamlit-based interactive dashboard
├── models/ → Saved trained models (if available)
├── requirements.txt → Dependencies required to run the project
└── README.md → This file

🔥 Key Results
Naïve Bayes → Accuracy: 76.39% \\
Logistic Regression → Accuracy: 78%\\
DistilBERT (30% dataset, 1 epoch) → Accuracy: 84.71%\\
BERT (30% dataset, 1 epoch) → Accuracy: 85.24%\\
🔹 BERT achieved the highest performance, even with limited computational resources.

📊 Streamlit Dashboard
This project includes an interactive dashboard with Streamlit to visualize the results.

🔹 Running the Dashboard
Install the required dependencies:
bash
Copia
Modifica
pip install -r requirements.txt
Start Streamlit:
bash
Copia
Modifica
streamlit run streamlit_app/main.py
📝 Conclusions
LDA did not effectively extapolate topics from the tweets.
BERT demonstrated the highest accuracy, making it the best-performing model in this analysis.
The Streamlit dashboard provides an interactive way to explore results.
📌 Author
📧 Daniele Amato
💼 LinkedIn: https://www.linkedin.com/in/daniele-amato-0b2949328/

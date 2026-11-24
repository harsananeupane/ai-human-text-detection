# AI vs. Human Text Detection

A team project developed for my Algorithms course at the University of North Texas. We compared machine learning and deep learning algorithms to classify human-written and AI-generated text.

## Dataset

We used 5,000 balanced text samples from the Human ChatGPT Comparison Corpus (HC3).

- Training: 3,500 samples
- Validation: 500 samples
- Testing: 1,000 samples

Dataset source: [Human ChatGPT Comparison Corpus (HC3)](https://huggingface.co/datasets/Hello-SimpleAI/HC3) — Guo et al. (2023). Our dataset is a cleaned and sampled subset of HC3.

## Results

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 90.0% |
| Naive Bayes | 87.7% |
| Linear SVM | 91.4% |
| Alternative Logistic Regression | 92.1% |
| LSTM | 92.1% |

Our results showed that traditional machine learning models can achieve similar accuracy to deep learning models with significantly shorter training times.

## Technologies

Python, Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Matplotlib, Seaborn, Google Colab

## Concepts Covered

- Natural language processing
- Data cleaning and preprocessing
- TF-IDF vectorization
- Binary classification
- Model evaluation
- Confusion matrices and error analysis

## Team

- Harsana Neupane – Team Lead
- Alanna Thompson
- Nikesh Paudyal

## What I Learned

This project helped me understand text classification, model performance, and the trade-off between accuracy and computational efficiency.

The models are experimental and should not be used as definitive proof of text authorship.

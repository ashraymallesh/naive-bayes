# Reddit Text Classification using Bernoulli Naive Bayes

### [Project Spec](miniproject2_spec.pdf)

In this mini-project you will develop models to analyze text from the website Reddit (https://www.reddit.com/), a popular social media forum where users post and comment on content in different themed communities, or subreddits. The goal of this project is to develop a supervised classification model that can predict what community a comment came from.

- You must implement a Bernoulli Naive Bayes model (i.e., the Naive Bayes model from Lecture 5) from scratch (i.e., without using any external libraries such as SciKit learn). You are free to use any text preprocessing that you like with this model. You many want to use Laplace smoothing with your Bernoulli Naive Bayes model. You can choose the vocabulary for your model (i.e, which words you include vs. ignore), but you should provide justification for the vocabulary you use.

- You must develop a model validation pipeline (e.g., using k-fold cross validation or a held-out validation set) and report on the performance

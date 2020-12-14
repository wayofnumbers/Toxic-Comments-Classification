# Toxic Comments Classification

![Toxic comments](https://cdn-images-1.medium.com/max/2000/0*SxwidHTBf5ZSysg9.jpg)

## Overview

[Kaggle](http://www.kaggle.com) is a good place to learn and practice your Machine Learning skills. It’s also a great place to find the proper dataset for your learning projects. I need a good classification NLP dataset to practice my recently learned fast.ai lesson, and I came across the [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). The competition is held two years ago and has long concluded, but it doesn’t hurt to submit my scores and see how well I did. This is one of the things Kaggle is great for since in the real world, it will usually be much harder to know how good or bad your model is, whereas, in Kaggle, you’ll see clearly where your performance is in the Leaderboard.
This project explored the approach of using language model pre-training and transfer learning to get to the desired results with less training time.

## The Data Set

This competition is held by The [Conversation AI](https://conversationai.github.io/) team, a research initiative founded by [Jigsaw](https://jigsaw.google.com/) and Google (both a part of Alphabet). Its goal is to find out the best model that can classify multiple toxicity types in comments. The toxicity types are:
> toxic
> severe_toxic
> obscene
> threat
> insult
> indentity_hate

Comments are given in a training file train.cvs and a testing file test.csv. And you’ll need to predict a probability of each type of toxicity for each comment in test.csv. It is a multi-label NLP classification problem.

## Notebook

You can find the full **Jupyter Notebook** [here](https://github.com/wayofnumbers/Toxic-Comments-Classification/blob/main/toxic-comments-classification-fast-ai.ipynb).

If you want to give it a try, you can also find the Notebook on Kaggle where you can easily copy and run yourself(Dataset on Kaggle too):
[Kaggle Notebook](https://www.kaggle.com/lymenlee/toxic-comments-classification-fast-ai/notebook)

## Dataset
The Kaggle competition page can be found [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)

## Articles

I wrote two articles about this project on own blog, which you can find below:

[Attack Toxic Comments Kaggle Competition using Fast.ai](https://wayofnumbers.com/attack-toxic-comments-kaggle-competition-using-fast-ai)


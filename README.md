# Hacker News Posts Project
## Description
Hacker News is a website where users submit their posts mainly concerning computer science and entrepreneurship, that can be voted and commented by other users, like Reddit.

Since this project aims to practice with relatively simple data sets I will use a reduced version of the [Hacker News Posts data set](https://www.kaggle.com/hacker-news/hacker-news-posts), that instead of 300,000 rows uses only 20,000 rows obtained by removing the submissions that did not receive any comments, and then randomly sampling from the remaining submissions.

The goal of the project is to compare two types of posts:
- **Ask HN** : users submit Ask HN to ask the Hacker News community a specific question
- **Show HN** : users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting

I'll compare these two types of posts to determine:
- Which type of post between Ask HN and Show HN receive more comments on average?
- Do posts created at a certain time receive more comments on average?
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project
      </a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We use Natural language Processing to perform this Spam Detection Project. All these tasks are done through Natural Language Processing (NLP), which processes text into useful insights that can be applied to future data. In the field of artificial intelligence, NLP is one of the most complex areas of research due to the fact that text data is contextual. It needs modification to make it machine-interpretable, and requires multiple stages of processing for feature extraction.
In professional life, email is one the very important tool for communication. To have effective communication, spam filtering is one of the important feature. We will explore and understand the process of classifying emails as spam or not spam. This is called Spam Detection, and it is a binary classification problem.


<p align="center">
<img src="https://lionbridge.ai/wp-content/uploads/2020/08/2020-08-20_nlp_spam-detection.jpg"
 alt="Logo" width="500" height="300">
</p>


### Built With

To perform this task we have pre-defined libraries, by using them we can easily achieve our task.
* [NLTK](https://www.nltk.org/)
* [Sklearn](https://scikit-learn.org/stable/)
* [Bag of Words](https://machinelearningmastery.com/gentle-introduction-bag-words-model/)
* [Stemming](https://medium.com/@tusharsri/nlp-a-quick-guide-to-stemming-60f1ca5db49e#:~:text=Stemming%20is%20basically%20removing%20the%20suffix%20from%20a%20word%20and,word%20from%20original%20stem%20word.)
* [Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Any python Compiler

### Installation

1. Install packages
   ```sh
   pip install nltk
   pip install scikit-learn
   pip install pandas
   pip install numpy
   pip install matplotlib
   ```



<!-- USAGE EXAMPLES -->
## Usage

The reason to do this is simple: by detecting unsolicited and unwanted emails, we can prevent spam messages from creeping into the user’s inbox, thereby improving user experience.



<!-- ROADMAP -->
## Roadmap

In this repository I predict whether the review is good or bad.

1. In professional life, email is one the very important tool for communication. To have effective communication, spam filtering is one of the important feature.

2. The main goal of this repository is to classify spam mails. In this repository I use necessary libraries like:
* [Pandas]
* [Matplotlib]
* [Numpy]
* Natural Language Tool Kit (NLTK)
* Regular Expression
* Sklearn

3. First a fall, we import all the required libraries.
4. Then import the dataset of Emails.
5. Now, we transform our data into meaningfull data by following steps: 
* We remove all the symbols, commas, brackets etc except letters [a-zA-Z]. 
* Lower all the data.
* Now, we extract meaningfull words from the data by using Stemming (Port Stemmer), we can also use lemmatization.
* We remove stopwords (English words which does not add much meaning to a sentence) using stopwords library in NLTK.
* Now, we join all the data to make a corpus.
6. Here, we use Bag of words algorithm that is: 
* It is a way of extracting features from text for use in modeling, such as with machine learning algorithms.
* The approach is very simple and flexible, and can be used in a myriad of ways for extracting features from documents.
* A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things: 
                     * - A vocabulary of known words.
                     * - A measure of the presence of known words.
7. we also use other algorithms like TF-IDF, Word2Vec.
8. Now, we split our data into train and test using train_test_split library.
9. We split the data into 80% training data and 20% test data.
10. Now, apply Naive Bayes algorithm on this data because Naive Bayes is suitable for solving multi-class prediction problems. If its assumption of the independence of features holds true, it can perform better than other models and requires much less training data. Naive Bayes is better suited for categorical input variables than numerical variables.
11. After applying algorithm, we find the confusion matrix and accuracy using library sklearn.matrics. We got 73% accuracy by applying Naive Bayes.
12. You can develop your own model and improve accuracy by using others algorithms and tuning Hyperparameteres. Good Luck 😎





[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/aniket-yadav-2008


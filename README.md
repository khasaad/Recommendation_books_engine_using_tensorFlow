<p>This project uses this reference <a href="https://www.tensorflow.org/recommenders?hl=en">https://www.tensorflow.org/recommenders?hl=en</a> to make recommandation books for an user using <font color='red'>building deep</font> retrieval models.</p>

<h1>Introduction</h1>

<p>The Books dataset is a classic dataset from kaggle page. It contains a set of ratings given to books by a set of users, and is a workhorse of recommender system research.</p>
<p>The data can be treated in the following way:</p>
<p>It can be interpreted as expressesing which books the users read (and rated), and which they did not, and it can also be seen as expressesing how much the users liked the books they did read.</p>
<p>This is a form of explicit feedback: given that a user read a book, we can tell roughly how much they liked by looking at the rating they have given.</p>
<p>In this project, we are focusing on a retrieval system: a model that predicts a set of books from the catalogue that the user is likely to read by looking at the rating another users have given.</p>
<p>In this project, we will illustrate how to build deep retrieval models using TensorFlow Recommenders.</p>

# Implementation steps

<ol>
<li>clone the github repository:<br><code>git clone https://github.com/khasaad/Recommendation_books_engine_using_tensorFlow.git </code></li>
<li><code>pip install -r requirements.txt</code></li>
</ol>

# Conclusion

<p>The best accuracy was with one layer. We note whenever we increment one layer, the accuracy decrement, but when we add number of epochs the accuracy increment.</p>

<p>The deeper and larger models, while capable of superior performance, often require very careful tuning.</p>

<p>With appropriate tuning and sufficient data, the effort put into building larger and deeper models is in many cases well worth it: larger models can lead to substantial improvements in prediction accuracy.</p>
 

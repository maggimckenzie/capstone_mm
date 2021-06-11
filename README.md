
# **Topic Modeling with Project Gutenberg**
### ***Modeling novel-length fiction***

---

(<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ5xmYwyhgUf0KwiyuGQ1PwZyx1Tv6Nh5wulVPTiuGMscNFILH1YaOwenaV7VNt3d2EcgZuROycPm5_/embed?start=false&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>)

---

## **Origin**
Language is how humans communicate, but stories are how we make sense of the world. Stories are important, and reading is one way we consume stories. Online book stores are wonderful if you know what you want, but they lack the environment of browsing and discovery that a brick-and-mortar store offers. Project Gutenberg has an online repository of over 65,000 free e-books with, but it offers a bare-bones user experience. I conceived this project to investigate a couple of things:

Can NLP tools and methods can offer insight into topics and themes of books in a particular genre?

Is it possible to provide useful recommendations of similar books using topic modeling?

---

## **Data Source and Tools**

The [Standardized Project Gutenberg Corpus](https://github.com/pgcorpus/gutenberg) repository provides resources to retrieve all available [Project Gutenberg](https://www.gutenberg.org/) texts and to incrementally retrieve new texts as they are added. I obtained my dataset using their code. I used NLTK, spaCy, Gensim, and scikit-learn to create LDA models and analyze the results

---

## **Acknowledgments**

All the volunteers who contribute to and maintain Project Gutenberg make this wonderful resource available for readers around the world and also for researchers (and students) in need of long texts. This project would not be possible without them.

Michael Holloway and Tim Dobbins provided patient guidance and advice. Matt Parker contributed timely and helpful code snippets. Thank you all, and thank you to all my Data Science Cohort 4 classmates at Nashville Software School for a wonderful year.
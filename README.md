![alt text][logo]

[logo]: https://github.com/satushsinha/Authorship-Identification/blob/main/images/Author.png "Authorship Identification of Micro-text using Capsule Network"
# Authorship Identification of Micro-text using Capsule Network 
### Author's
+ chanchal Suman
+ Ayush Raj
+ Sriparna Saha
+ Pushpak Bhattacharyya

### Abstract

Authorship attribution is an important task, as it identifies the author of a written text from a set of suspect authors. Differentmethodologies of anonymous writing, have been discovered with the rising usage of social media. This anonymous writing leads to anincrease in malicious and suspicious activities, and anonymity makes it difficult to find the suspect. Authorship attribution helps to findthe writer of a suspect text from a set of suspects. Different social media platforms such as Twitter, Facebook, Instagram, etc. are usedregularly by the users for sharing their daily life activities. Finding the writer of micro-texts is considered the toughest task, due to theshorter length of the suspect piece of text. We present a Capsule based Convolutional Neural Network model over character n-grams for performing the authorship attribution task. Capsule with Kervolutional Neural Networks (KNNs) has also been utilized for this task.We also present different analyses of our developed system, which improves the interpretability of our developed system. Heat-mapsfor different models, illustrate the relevant text fragments for the prediction task. A standard Twitter dataset is used for evaluating theperformance of the developed systems. The experimental evaluation shows that capsule-based CNNs and capsule-based KNNsperform competitively and are able to outperform previous methods. The source codes will be publicly available after acceptance of this work.

### Dataset
We have collected tweets for so many authors then we created Dataset of two types:
+ **Dataset with varying number of Tweets**
We randomly selected 50 authors then we created Dataset as:
  + Dataset with 50 Tweets per author
  + Dataset with 100 Tweets per author
  + Dataset with 200 Tweets per author
  + Dataset with 500 Tweets per author
  + Dataset with 1000 Tweets per author

+ **Dataset with varying number of Author**
We fixed the number of tweets equal to 200 per author then created the following Dataset:
  + Dataset with 100 authors
  + Dataset with 200 authors
  + Dataset with 500 authors
  + Dataset with 1000 authors

### Models

#### Character Unigram with CNN

Character Unigram is constructed for text then it is given to the input layer of neural net.You can see the detailed layer of the neural net in the diagram below.

##### Results
**Dataset with varying number of tweets:**
|50 Tweets | 100 Tweets | 200 Tweets | 500 Tweets | 1000 Tweets |
| --- | ---- | ----| ---- |----|

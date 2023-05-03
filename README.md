# Lemmatizer-NLP-

# Libraries used.

In this file whatever work I have done in python, I have done it using libraries called nltk and WordNet Lemmatizer.

# What is lemmatizing?

![alt text](https://i.ytimg.com/vi/_iUVWtUzrhg/maxresdefault.jpg)

In simple words lemmatizing nothing but converting plural words into singular.The main purpose of this is to remove the number of unique words when we go for vectorization. Basically when we lemmatize then "horse" and "horses" are considered to be same words by the vectorizer thereby reducing our column of unique words.

# What has been performed?

In this file I have made a python function that will take a string or a sentence as an input and return the lemmatized sentence as an output. We do this to reduce our work as lemmatizer only applies to words and not sentences so if we were to lemmatize a sentence we have to go word by word so why not create a function that will perform all of this in the back end and give us the desired result.

Steps in the function.

![alt text](https://th.bing.com/th/id/R.5b6970af8261632cdb3dbb0253bfbc54?rik=bNIdYCtu%2fefkHg&riu=http%3a%2f%2fimages.clipartpanda.com%2fstep-clipart-StepsClipArt.jpg&ehk=Ce%2f5CgUhsyC4zJri32Gc5AkPYgRqaMffBRnDU25vG3U%3d&risl=&pid=ImgRaw&r=0)

1.Tokenized the sentence to convert it into words.

2.Made an empty list which will be used further to append the lemmatized words.

3.Created a for look to go word by word and lemmatize it.

4.After lemmatizing each and every word we apped it to the list

5.Finally we return the list containing our lemmatized words.

# Thank you




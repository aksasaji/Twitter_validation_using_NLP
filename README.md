# Twitter_validation_using_NLP

Preprocessing

Normalization

Normalization refers to the process of transforming data into a standard format in order to facilitate data comparison and analysis. In the context of natural language processing (NLP), normalization typically refers to the process of converting text data into a standard format. Normalization techniques in NLP include several processes such as converting text to lowercase, removing stop words, stemming, and lemmatization. The objective of normalization is to reduce the variability of text data, so that it can be more easily compared and analyzed.

Converting text to lowercase is a basic normalization technique that involves converting all the letters in a piece of text to lowercase. This is useful because it reduces the number of variations of the same word that may occur in a text corpus. For example, "Dog", "DOG", and "dog" would all be converted to "dog". Removing stop words is another common normalization technique, which involves removing common words such as "the", "a", and "an". These words do not add significant meaning to a sentence and removing them helps to reduce the dimensionality of the data.

Stemming and lemmatization are two other common normalization techniques in NLP. Stemming involves reducing words to their root form, while lemmatization involves reducing words to their base form. These techniques help to reduce the variability of words that can occur in a textcorpus, making it easier to compare and analyze the data. Normalization is an important step in the preprocessing stage of NLP, as it can significantly improve the accuracy and performance of machine learning models that use text data. By reducing the variability of text data, normalization techniques help to improve the accuracy of text classification, sentiment analysis, and other NLP tasks.

StopWords

Stopwords refer to the most commonly used words in a language that are considered to have little or no contribution to the meaning of a text. These words are usually removed from the text during the preprocessing stage of natural language processing (NLP) in order to improve the efficiency and accuracy of text analysis. Examples of stopwords in English include words like "the", "and", "of", "in", "to", "that", "is", "it", and so on. These words are so commonly used in English that they do not carry much semantic meaning, and their inclusion in text analysis can sometimes lead to noisy or misleading results.

Removing stopwords can help to reduce the dimensionality of text data and improve the accuracy of text analysis. This is particularly important for tasks like text classification, sentiment analysis, and topic modeling, where the focus is on identifying meaningful patterns and relationships in the text. However, it is important to note that the selection of stopwords can vary depending on the specific task or domain being analyzed. For example, certain domain-specific terms or jargon may be considered stopwords in one context but not in another. Therefore, it is often necessary to customize the list of stopwords for each specific use case.

In Natural Language Processing, there are several libraries and tools available that provide pre-defined lists of stopwords for different languages, including NLTK, spaCy, and Scikit-Learn. These libraries can be used to remove stopwords from text data during the preprocessing stage, and can significantly improve the accuracy and efficiency of text analysis tasks.

Machine Learing model Accuracy Score

1.Support Vector Machine:63%

2.Naive Bayes:60%

3.Random Forest:56%

4.AdoBoost:47%

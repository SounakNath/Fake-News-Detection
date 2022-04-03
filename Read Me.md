Objective : Build a Fake News Classification Model

What is Term Frequency (TF)? : Term frequency refers to the number of
times that a term t occurs in document d. That is, the number of times a
word appears in a document is its Term Frequency. A higher value means a
term appears more often than others, and so, the document is a good
match when the term is part of the search terms.

What is Inverse Document Frequency (IDF)? : The inverse document
frequency is a measure of whether a term is common or rare in a given
document corpus. It is obtained by dividing the total number of
documents by the number of documents containing the term in the corpus.
Words that occur many times a document, but also occur many times in
many others, may be irrelevant. Hence, IDF is a measure of how
significant a term is in the entire corpus.

Once these two metrics have been calculated, they can be combined
(multiplied) to get a new measure: the term frequency × the inverse
document frequency. This value reflects how important a word is with
respect to a given document in a corpus of documents. These metrics are
often used by online search engines in order to retrieve the most
relevant documents for a user query.

What is a TfidfVectorizer?: The TfidfVectorizer converts a collection of
raw documents into a matrix of TF-IDF features.

What is a PassiveAggressiveClassifier? : Passive Aggressive algorithms
are online learning algorithms. Such an algorithm remains passive for a
correct classification outcome, and turns aggressive in the event of a
miscalculation, updating and adjusting. Unlike most other algorithms, it
does not converge. Its purpose is to make updates that correct the loss,
causing very little change in the norm of the weight vector.

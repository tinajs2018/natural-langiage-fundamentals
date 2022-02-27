# natural-langiage-fundamentals
The essence of Natural Language Processing lies in making computers understand the natural language. That’s not an easy task though. Computers can understand the structured form of data like spreadsheets and the tables in the database, but human languages, texts, and voices form an unstructured category of data, and it gets difficult for the computer to understand it, and there arises the need for Natural Language Processing.

There’s a lot of natural language data out there in various forms and it would get very easy if computers can understand and process that data. We can train the models in accordance with expected output in different ways. Humans have been writing for thousands of years, there are a lot of literature pieces available, and it would be great if we make computers understand that. But the task is never going to be easy. There are various challenges floating out there like understanding the correct meaning of the sentence, correct Named-Entity Recognition(NER), correct prediction of various parts of speech, coreference resolution(the most challenging thing in my opinion).

Computers can’t truly understand the human language. If we feed enough data and train a model properly, it can distinguish and try categorizing various parts of speech(noun, verb, adjective, supporter, etc…) based on previously fed data and experiences. If it encounters a new word it tried making the nearest guess which can be embarrassingly wrong few times.

It’s very difficult for a computer to extract the exact meaning from a sentence. For example – The boy radiated fire like vibes. The boy had a very motivating personality or he actually radiated fire? As you see over here, parsing English with a computer is going to be complicated.

There are various stages involved in training a model. Solving a complex problem in Machine Learning means building a pipeline. In simple terms, it means breaking a complex problem into a number of small problems, making models for each of them and then integrating these models. A similar thing is done in NLP. We can break down the process of understanding English for a model into a number of small pieces.

It would be really great if a computer could understand that San Pedro is an island in Belize district in Central America with a population of 16, 444 and it is the second largest town in Belize. But to make the computer understand this, we need to teach computer very basic concepts of written language.

So let’s start by creating an NLP pipeline. It has various steps which will give us the desired output(maybe not in a few rare cases) at the end.
 Step #1: Sentence Segmentation
Breaking the piece of text in various sentences.

Step #2: Word Tokenization
Breaking the sentence into individual words called as tokens. We can tokenize them whenever we encounter a space, we can train a model in that way. Even punctuations are considered as individual tokens as they have some meaning.
tep #3: Predicting Parts of Speech for each token
Predicting whether the word is a noun, verb, adjective, adverb, pronoun, etc. This will help to understand what the sentence is talking about. This can be achieved by feeding the tokens( and the words around it) to a pre-trained part-of-speech classification model. This model was fed a lot of English words with various parts of speech tagged to them so that it classifies the similar words it encounters in future in various parts of speech. Again, the models don’t really understand the ‘sense’ of the words, it just classifies them on the basis of its previous experience. It’s pure statistics.

Step #4: Lemmatization
Feeding the model with the root word.
Step #5: Identifying stop words
Step 6.1: Dependency Parsing
Step 6.2: Finding Noun Phrases
Step #7: Named Entity Recognition(NER)
Step #8: Coreference Resolution:



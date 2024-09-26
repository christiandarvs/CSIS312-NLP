- Training Data
  - is a type of data used for teaching new application, model or
system to begin recognizing patters dependant on a project's
requirements
  - (in AI or ML) is slightly different, as they are labeled or
annotated
  — to find relationships, develop understanding, make decisions
and evaluate their confidence when making a prediction the better the training data, the better the model performs

- Types of annotations in NLP
  - utterances
    - refers to the smallest unit of speech or text that a speaker produces as a complete thought, typically seperated by pauses in spoken tangauage or punctuation in written.
  - for example:
    - Can I have pizza?
    - How is the weather in Dasma?

  these sentences represents single utterance
  - intent
  - entity
  
Utterance Parsing

1. Identify pauses
2. Splitting text in utterances
   - use punctuation or logical breaks to split a sentence
   - each sentence can be treated as separate utterance if it expresses a complete idea
3. Preprocessing for Machine Learning
   - tokenization is used to split text into words
4. Analyze the utterances separately for tasks like Sentiment Analysis

"The laptop is fast and efficient, but the battery life is terrible. I like the design but it is too heavy to carry around."

- The laptop is fast and efficient
- but the battery life is terrible
- I like the design but
- it is too heavy to carry around

Split (Remove punc and conjunctions)
Analyze individually

- Sentiment
  - {Positive, Negative, Neutral}
- Intent
  - Feature Appreciation
  - Disappointment

-----------------------------

[Classical Approach]
  Text Processing
    - regular ex (how to write)
    - tokenization
      - white tokenization
      - dictionary based tokenization
      - rule-based tokenization
      - regular expression tokenizer
      - spacy tokenizer
      - tokenization with textblob
    - lemmatization
    - stemming
    - stopwords

# Regular Expression

- is a sequence of characters that define a search pattern
- to find, match, and manipulate text
- 'pattern-based' matching which can be applied to search a string

matching rules:

- literal characters: matches exact characters 'abc'
- metacharacters: special symbols with specific meaning {., ^, $, [], |, \A}

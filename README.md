# Text Summarization

Text summarization is a Natural Language Processing (NLP) task that summarizes the information in large texts for quicker consumption without losing vital information.

There are two main text summarization methods:

Extractive Text Summarization – attempts to identify significant sentences and then adds them to the summary, which will contain exact sentences from the original text.
Abstractive Text Summarization – attempts to identify important sections, interpret the context and intelligently generate a summary.

- Import 'spacy' for stopwords and 'string' for punctuation.
- Tokenize the corpus. Build 'word frequency'. Make sure you have removed the stopwords.
- Determine the maximum frequency as 'word_frequencies[word]=(word_frequencies[word]/maximum_frequency).
- Tokenize the sentences. Generate the sentence_scores. Score every sentence
based on number of words.
- Import nlargest from heapq and provide 'summarized_sentences'.
- Convert sentences from spacy to strings and join all sentences.
- Provide a summary once you have converted spacy outputs to strings.
- Determine the length of the summary.
- Determine the length of the original text.

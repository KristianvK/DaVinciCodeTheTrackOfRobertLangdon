# DaVinciCodeTheTrackOfRobertLangdon

For this project, we extract information from Dan Brown's book <em>The Da Vinci Code</em>. with different natural language processing (NLP) and text mining techniques. More specifically, we aim to extract the places visited by the characters throughout the book.

After performing some coreference resolution with Lingmess and SpanBERT, we use BERT and RoBERTa for named entity recognition (NER), normalizing the output with soft TF-IDF and Levenshtein distance. Afterwards, we map characters to location and lastly perform some topic modeling comparing LDA and BERTopic. Finally, we end this [report](https://github.com/KristianvK/DaVinciCodeTheTrackOfRobertLangdon/blob/main/Da_Vinci_Code__The_Track_of_Robert_Langdon.pdf) by revealing the different sites visited by Robert Langdon throughout his quest.

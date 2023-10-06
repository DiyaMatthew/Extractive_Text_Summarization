# Extractive_Text_Summarization
Implementing extractive summarization with BERT and ROBERTa.<br><br>

This approach extracts relevant words/phrases from the input sentence. The summary is created by choosing the most important points from the text input. An extractive approach uses only sentences contained in the input text for the summary. That is, in the extractive summarization, key sentences or phrases from the source documents are extracted and grouped to generate a summary without modifying the original document.<br>
# CNN/Daily Mail Dataset
Scholarly articles, news articles and stories are used as sources for summarizing data. The summarization dataset generally consists of English-language news articles. In this project, the chosen dataset is CNN / Daily Mail Dataset from Hugging Face(Hugging face, 2015). Approximately 300k unique news articles written by CNN and Daily Mail journalists make up the CNN/Daily Mail Dataset. The present version of dataset supports both extractive and abstract summarization. It contains three data fields: id, article, and highlights. Every data field is string type. The CNN/Daily Mail dataset has three splits: train, validation, and test. 

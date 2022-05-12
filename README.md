# Text Summarizer

[Try the web application here.](http://anweasha.pythonanywhere.com/Summarize)

## Overview

Text summarization refers to the technique of shortening long pieces of text. The intention is to create a coherent and fluent summary having only the main points outlined in the document. Automatic text summarization is a common problem in machine learning and natural language processing (NLP). 

There are two main approaches to summarize text in NLP:

- **Extractive summarization**
This approach selects passages from the source text and then arranges it to form a summary. One way of thinking about this is like a highlighter underlining the important sections. The main idea is that the summarized text is a sub portion of the source text.

- **Abstractive summarization**
The abstraction technique entails paraphrasing and shortening parts of the source document. When abstraction is applied for text summarization in deep learning problems, it can overcome the grammar inconsistencies of the extractive method. The abstractive text summarization algorithms create new phrases and sentences that relay the most useful information from the original text — just like humans do.
Therefore, abstraction performs better than extraction. However, the text summarization algorithms required to do abstraction are more difficult to develop.  

In this project, I have made the use of abstractive summarization with the help of BART model, which inherits from pretrained model on Hugging Face.

## Features:
- The user can enter any text of desired length in the text area to get it summarized.
- He/she can specify the length of the desired summary.
- After getting the summary, the user can copy the text to clipboard to use it somewhere else.

<br>

> **WEB APPLICATION -** [Text Summarizer](http://anweasha.pythonanywhere.com/Summarize)
<br>

<img src="https://github.com/anweasha/Text-Summarizer/blob/main/images/image_1.png" width=700><br>
<br><img src="https://github.com/anweasha/Text-Summarizer/blob/main/images/image_2.png" width=700><br>
<br><img src="https://github.com/anweasha/Text-Summarizer/blob/main/images/image_3.png" width=700><br>
<br><img src="https://github.com/anweasha/Text-Summarizer/blob/main/images/image_4.png" width=700><br>

## Tech Stacks:
- [Hugging Face](https://huggingface.co)
- Transformers
- Natural Language Processing (NLP)
- Python

## References:
- [A Quick Introduction to Text Summarization in Machine Learning](https://medium.com/towards-data-science/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f)
- [Text Summarization using Deep Learning](https://medium.com/towards-data-science/text-summarization-using-deep-learning-6e379ed2e89c)
- [Hugging Face Model](https://huggingface.co/sshleifer/distilbart-cnn-12-6)

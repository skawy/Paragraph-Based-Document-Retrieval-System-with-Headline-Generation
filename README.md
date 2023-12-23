# Paragraph-Based-Document-Retrieval-System-with-Headline-Generation
Develop a system for retrieving relevant paragraphs based on a specified topic from multiple uploaded documents and generating headlines for each paragraph.
> It helps you to retrieve whole paragraphs related to a user-specified topic from uploaded documents.
> Automatically generate headlines for each retrieved paragraph.
> Handling various format and ways to extract paragraphs from pdfs
> Additionally you can see how can you fine tune bert model to bbc news data




## Installation

First you need to install this requirements
```sh
python -m pip install -r requirements.txt
```

## Overview of the files
There are 4 main files
1) gui.py => using pysimple gui library to make an application with ui to upload documents and to handle different document formats 
2) headline_generating.py => scribt to generate headlines using openai api with gpt-3.5-turbo model
3) bert_bbcnews_finetune.ipynb => notebook to show how to finetune bert with your data but the reasult is bert classifier object then didnot use it in encoding paragrphs
4) bert_paragraph_retrieval.ipynb => notebook to show how can you find paragraphs related to any topic in any document using bert model and cosine similarity

### Finally 
5) paragraph_retrieval_with_headline.ipynb => Shows The Full Paragraph-Based Document Retrieval System with Headline Generation System with using previous scripts to develop it



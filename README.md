# 6513-LLM-Tokenizer-Pipeline
This is the repo housing the LLM Tokenizing pipeline, along with analytics to help inform the user the nature of the data they are tokenizing. 

## Instructions to Run
* There is a single jupyter notebook file that can be uploaded to Google Colab and run as is.
* The dataset that we use to demonstrate this pipeline is the Wikipedia Articles package, which will then auto download articles (default 100) and pass it to the pipeline. There is no manual intervention required.
* You would need an environment that supports Spark and is GPU accelerated

## Structure of Project
The Jupyter Notebook has 3 sections:
1) BPE Tokenizer pipeline demo
2) HuggingFace Tokenizer demo
3) Analytical Insights from Data

The expectation is that each section will be run in order

---
Authors: Pranav Bhatt, Yash Patel, Atharv Parab

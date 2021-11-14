# Building a Question Answering (QA) System 

The following document describes a step by step process of building a QA (Question Answering) System that parses through 730 Business Insider articles from 2013 and 2014 and is capable answering the following questions:

1. **Which companies went bankrupt in month X of year Y?**
2. **What percentage of drop or increase in GDP is associated with X?**
3. **Who is the CEO of company X?**

By incorporating the scoring system of Elasticsearch, spaCy’s NER tagger, and other heuristic methods, the following QA system is successfully able to categorize queries and output relevant answers. 

The step by step process and the full code can be found [here](https://nbviewer.org/github/yunhwanchoi/BI-QA-System/blob/main/Building%20a%20QA%20System.ipynb).

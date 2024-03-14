
# Grammatical Correction

This was a project for the lecture Introduction to Transformer Models in the Winter Semester 2023 at the University Heinrich-Heine Düsseldorf.

The idea was to creating a model that corrects grammatical mistakes from beginner German learners.

# Used Tools

Text to Text Transformer - T5: https://huggingface.co/docs/transformers/model_doc/t5#performance

Source:
Exploring Transfer Learning with T5: the Text-To-Text Transfer Transformer: https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html

Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer - Cornell University https://arxiv.org/abs/1910.10683

## Preparing the Data.

There are few freely-available corpora in German with annotated correct and incorrect sentences. 

Our corpora consists of a total of 10,500 annotated sentence pairs:

- 400 of these are manually-annotated examples produced by learners of German (B1-B2).
      
- 10 100 of these are automatically annotated sentences from the German news corpora (2021).  
Source: https://wortschatz.uni-leipzig.de/de/download/German

D. Goldhahn, T. Eckart & U. Quasthoff: Building Large Monolingual Dictionaries at the Leipzig Corpora Collection: From 100 to 200 Languages In: Proceedings of the 8th International Language Resources and Evaluation,2012 

* For reasons of Privacy, it wasn't possible to publish the data because there were people's sensitive information in the data such as names, family relations, etc.

## Training

We carried out a total of 3 training sessions and 9 tests:

1) Training with automatically generated data only

2) Training with manually annotated data

3) Training with a 50/50 mix of automatically generated and manually annotated data

## Results 

You can look the results in the coding file.

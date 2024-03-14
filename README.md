# Grammatical Correction

This was a project for the lecture Introduction to Transformer Models in the Winter Semester 2023 at the University Heinrich-Heine Düsseldorf.

The idea was to create a model that corrects grammatical mistakes.

# Used Tools

Text to Text Transformer - T5: https://huggingface.co/docs/transformers/model_doc/t5#performance

Quelle:

Exploring Transfer Learning with T5: the Text-To-Text Transfer Transformer: https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html

Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer - Cornell University https://arxiv.org/abs/1910.10683

## Datenvorbereitung


Es gibt wenige frei-verfügbare Korpora in der Deutschen Sprache mit annotierten korrekten und fehlerhaften Sätzen. 

Unsere Korpora besteht insgesamt aus 10 500 annotierten Sätze-Paaren:

- 400 davon sind manuell-annotierte Beispiele, die von den Deutsch-lernenden (B1-B2) produziert wurden.
      
- 10 100 davon sind automatisch-annotierte Sätze aus der deutschen Nachrichten Korpora (2021). 
Quelle: https://wortschatz.uni-leipzig.de/de/download/German

D. Goldhahn, T. Eckart & U. Quasthoff: Building Large Monolingual Dictionaries at the Leipzig Corpora Collection: From 100 to 200 Languages In: Proceedings of the 8th International Language Resources and Evaluation,2012 

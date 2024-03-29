# Natural Language Process projects
![alt text](https://github.com/REDISKA3000/text_generation/blob/01621af44ba94468154e5eeae27971744f97e128/maxresdefault.jpg?raw=true)
This folder contains my NLP projects that solve different in diverse NLP challenges.

### Text generation
This notebook covers the basic concepts of NLP like **lemmatization**, **tokenization** by **n-gramms**, **deleting stopwords** and **punctuation** - all these steps are used to prepare for model trainig. The model consists of **GRU** blocks that are modified versions of **RNN** blocks. Actually, there more advanced models that are used to generate text, they are done in other notebooks.
### Transformer English to French
In this notebook I solve the wellknown NLP challenge called **machine translation** a subproblem of **sequence-to-sequence**. With the usage of Tensorflow I implement the intitial **Transformer** model, which is widely used in NLP for many challenges. In this case I leverage the model to translate English to French, the redult of translation one can observe in the end of the notebook within the quality-metric **Rouge**. 
### BART transfer learning
This project is mostly devoted to practicing **transfer learning** method. The idea behind it is to take already fitted model and adapt it to your own needs by "freezing" the model, except for th last linear layers, which are often substituted and trained again on a smaller dataset to make the rezult more specific, that would fit your needs. In my case I took a dataset "billsum", which is summarization of US Congressional and California state bills and, using it, trained **BART** model based on CNN news.

 




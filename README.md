# ATS_AugmentedDataset

In this repository you can find the corpus that was assembled to conduct an *Automatic Text Simplification* task for the Italian language. 
The dataset consists of two columns, the first named **Sentence_1**, corresponds to sentences in the complex format, while the second column **Sentence_2** corresponds to their simplified form. 
The corpus is composed of the union of three data sources: 

- 32,650: parallel sentences come from *PaCCSS-IT corpus*, which was originally larger but has been cleansed of redundant and mistake-containing phrases. 

- 1,241: complex-simple sentences come from the union of three other very small parallel datasets developed for the Italian language (*Terence, Teacher & SIMPITIKI*)

- 1,771: parallel sentences are the result of the translation from English to Italian of the training and development set of the *Human Simplification with Sentence Fusion Data Set* and few sentences translated by the first version of the *Wikipedia Dataset*. The API of DeepL was used for the translation.

So the dataset consists of **35,662 c-s pairs**.

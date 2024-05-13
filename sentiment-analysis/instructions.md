# Sentiment Analysis: Instructions and Operational Guidelines

This document contains the basic operational guidelines to define the prevalent sentiment in the various corpora assembled for this project. It serves as overall documentation, and it will be integrated with useful observations that emerged throughout the work. 

## Structure of the spreadsheet 

### Text Units 
Each text in this corpus has been preprocessed and split into sentences, based on punctuation and length. We have excluded all units that counted less than 15 tokens and more than 50. 

**You may change the units in the spreadsheet or add new sentences**: In general, you should try not to change the existing sentences based on arbitrary criteria. However, sometimes you will have to add new lines or change existing ones: for example, you may have to split units that include questions, or you may find that one line includes multiple sentences and it needs to be split into multiple lines. Your task is to do whatever is necessary to make the text units more consistent. 

Try not to include units of text below 15 words or above 50 words. Those are very hard to use for training. 

### Other elements of the spreadsheet
The spreadsheet is divided into the following columns: 
* Verse: you should assign the verse number/s of each sentence
* Sentence number: a simple progressive number indicating the number of each sentence. **If you add or remove sentences, remember to change this** 
* Segment: the text unit resulting from preprocessing
* Sentiment class: the sentiment class to assign
* Translation: the translation of the sentence in question, taken from any available scholarly resource (or your own)
* Relevant lexicon: **lemmas** and translations of the most relevant **adjectives** and **nouns** that helped determine the sentiment class of the sentence.      
          You should use the online readers for your respective texts to find the lemmas, POS, and translations of the words.     
          The LatinAffectus lexicon (https://github.com/CIRCSE/Latin_Sentiment_Lexicons/blob/master/LatinAffectus.tsv) may contain some of the words you are analyzing, so check if they have your word or query them here: https://lila-erc.eu/query/ and click on the heart next to the lemma. 

## Guidelines: How to Assign Emotion Polarity 

The purpose of this project is to create a dataset of Sentiment Analysis for Latin and Greek. Students perform annotation at sentence level to assign four generic sentiment classes. 

### Sentiment classes explanation

* The sentiment class of a sentence is defined based on the specific emotion that the author tries to convey, not the generic emotion conveyed by the text.
* You should consider the vocabulary used by the author and the images the language tries to evoke.
* When assigning a class, try to answer the following question: **Which of the following classes best describes how the emotions are conveyed by the poet in the sentence under analysis?**
  
1.  **positive**: the only emotions that are conveyed at lexical level and the only images that are evoked by the sentence are positive, or positive emotions are clearly prevalent.     
2.  **negative**: the only emotions that are conveyed at lexical level and the only images that are evoked by the sentence are negative, or negative emotions are clearly prevalent.      
3.  **neutral**: there are no emotions conveyed by the text.      
4.  **mixed**: lexicon and evoked images produce opposite emotions: it is not possible to find a clearly prevalent emotion.


## Literature 
In this project, we follow closely the criteria and guidelines defined by Sprugnoli et al. (2021) for the creation of Sentiment Analysis datasets for Latin poetry. 

Reference datasets: 
* The sentences from Horace's Odes annotated by Sprugnoli et Al: https://github.com/CIRCSE/Latin_Sentiment_Analysis/tree/main/data
* The LatinAffectus Lexicon: https://github.com/CIRCSE/Latin_Sentiment_Lexicons/blob/master/LatinAffectus.tsv

* Sprugnoli, R., Mambrini, F., Passarotti, M., Moretti, G. 2021. Sentiment Analysis of Latin Poetry: First Experiments on the Odes of Horace. CEUR-Workshop. Available: https://ceur-ws.org/Vol-3033/paper25.pdf
* Sprugnoli, R., Passarotti, M., Corbetta, D., Peverelli, A. 2020. Odi et Amo. Creating, Evaluating and Extending Sentiment Lexicons for Latin. Proceedings of the 12th conference on Language Resources and Evaluation. Available: https://aclanthology.org/2020.lrec-1.376/
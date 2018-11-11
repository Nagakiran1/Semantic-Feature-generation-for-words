# Semantic Feature generation for words

Semantic similarity and Feature generating to the word is very important in any language modelling or Text analysis.

Semantic Feature generation involves generating the similarity value for Main word with all other generated synonym of Main word by calculating the synonyms level of Main word, incorporating the Lexical similarity from Natural Language toolkit.

## Feature Vector Generating for Main word
-  Extract Main word Synonyms from Thesaurus Dictionary. Assigning weight for each synonym word based on the lexical similairity between synonyms words with Main word with the use Natural Language Toolkit (nltk) library in python

    Calculating the WOrd similarity between the synonyms based on 
    
    Similarity between words        =  Weight of Level (W) * Wordnet Similarity (S)</br>
                                    =  0.95 * Wordnet Similarity(nltk wordnet similarity)</br>

     - Finding the Synonyms for all Main word Synonyms defined in First level from Thesaurus Dictionary. Assigning weight for each            synonym word based on the lexical similairity between synonyms words with Main word with the use Natural Language Toolkit (nltk) library in python

        Calculating the WOrd similarity between the synonyms based on 
        
        Similarity between words  
                                    =  Weight of Level (W) * Wordnet Similarity (S) </br>
                                    =  0.95 * 0.95 * Wordnet Similarity(nltk wordnet similarity)






![alt text](https://github.com/Nagakiran1/Semantic-Feature-generation-for-words/blob/master/Wordnet_1.PNG)

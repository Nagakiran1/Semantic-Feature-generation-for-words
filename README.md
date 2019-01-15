# Semantic Feature generation for words

[Semantic similarity and Feature generating to the word is very important in any language modelling or Text analysis.](https://medium.com/datadriveninvestor/semantic-feature-generation-for-words-9f47251eb5bd)

Semantic Feature generation involves generating the similarity value for Main word with all other synonyms associated with Main word by calculating the synonym distance level by level and incorporating the Lexical similarity from Natural Language toolkit.

## Feature Vector Generating for Main word
-  Extracting Main word Synonyms from Thesaurus Dictionary. Assigning weight for each synonym word based on the lexical similairity between synonyms words with Main word with the use Natural Language Toolkit (nltk) library in python

    Calculating the WOrd similarity between the synonyms based on 
    
    &emsp;&emsp;&emsp;Similarity between words &emsp;&emsp;&emsp;&emsp;      =  &emsp;Weight of Level (W) &nbsp; * &nbsp; Wordnet Similarity (S)</br>
          &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;  = &emsp; 0.95 &nbsp;* &nbsp;Wordnet Similarity(nltk wordnet similarity)</br>

     - 2nd Level Finding the Synonyms for all Main word Synonyms defined in First level from Thesaurus Dictionary. Assigning weight for each            synonym word based on the lexical similairity between synonyms words with Main word with the use Natural Language Toolkit (nltk) library in python

        Calculating the WOrd similarity between the synonyms based on 
        
        &emsp;&emsp;&emsp;Similarity between words&emsp;&emsp;&emsp;&emsp;&emsp;                        =&emsp; Weight of Level (W)&nbsp; * &nbsp;Wordnet Similarity (S) </br>
           &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;                         =  &nbsp;0.95 * 0.95 * Wordnet Similarity(nltk wordnet similarity)
           - </br>
            - </br>
              - </br> 
                - </br>
                    - </br>
                        -  </br>
                            - </br>




       
     - Nth Level Finding the Synonyms for all Main word Synonyms defined in First level from Thesaurus Dictionary. Assigning weight for each synonym word based on the lexical similairity between synonyms words with Main word with the use Natural Language Toolkit (nltk) library in python
     
     
        Calculating the WOrd similarity between the synonyms based on 
        
        &emsp;&emsp;&emsp;Similarity between words&emsp;&emsp;&emsp;&emsp;&emsp;                        =&emsp; Weight of Level (W)&nbsp; * &nbsp;Wordnet Similarity (S) </br>
           &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;                         =  &nbsp;0.95 ^ N * Wordnet Similarity(nltk wordnet similarity)




![alt text](https://github.com/Nagakiran1/Semantic-Feature-generation-for-words/blob/master/Wordnet_1.PNG)

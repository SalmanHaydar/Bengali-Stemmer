# Bengali-Stemmer

Language is ambigious. A simple word might have lots of form f.e. the word "give" can be "given", "gave". But both words has a common root which is "give".
So, in NLP when we represnt sentence in a vector space it helps to reduce the ambiguity if we only represnt each word with it's root only.
This process is called Stemming. To know more please follow this Wikipedia link https://en.wikipedia.org/wiki/Stemming .

But for Bangla it is not easier to implement stemmer. Because, While Bengali has 49 letters (to be more specific 11 vowels and 38 consonants) 
in its alphabet, there are also 18 potential diacritics, or accents. This means that there are many more graphemes, 
or the smallest units in a written language. The added complexity results in ~13,000 different grapheme variations 
(compared to English’s 250 graphemic units).

So, to implement the stemmer for Bangla I have tried different approach like seq2seq, SVM, etc. Please go through the "REVE TASK.ipynb" file.

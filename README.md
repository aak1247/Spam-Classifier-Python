# This is a spam classifier programmed with python

## technology
- python
- naive bayes classifier
- statics knowledge

## the rationale of naive bayes classifier

>wait for it


## the procedure of this program

1. read the email files from the disk.
2. then filter the emails the ones that don't have any meaningful word.
3. deal with emails text, return the text after the first blank line.
4. do the text mining with the string got from last step:
    1. divide the text to seperate words
    2. count the word and map the text to (key,value) pairs
5. build tdm(term document matrix), the tdm(i,j)=k means that the appearance of word i in document j, it is to say that a single line is corresponding to a single word and a single column corresponds to a single document.
6. then calculate the prior probability and conditional probability
7. then the model is built, for other data, just calculate the posterior probability, and choose the biggest one as result.
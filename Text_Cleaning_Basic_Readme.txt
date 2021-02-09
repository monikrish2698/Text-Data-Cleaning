Readme

Usually text data consumes more time in cleaning. The nature of text data is fragile 
which makes it prone to errors. Working with text data is tiring and also different problems 
will require different analysis to be perfomed. Not all the texts need to be cleaned in the
same manner. Some needs extra cleaning and some don't.
This Jupyter file explains how basic cleaning can be performed on text data. These data cleaning
methods are usually used in all kinds of text analysis.
In my scenario I was given a task to clean text files which has more than 1 billion rows in each.
Since the problem revolved around text analytics there were some basic cleaning that needed to be
done. So the cleaning goes like this:
- I read the files
- I have created 4 functions (basic clean, data clean, lemmatize, Stemming)
- I call the basic clean which helps me to remove null values and drop duplicates from the
defined set of parameters
- I call the data clean function to convert the texts to lower, remove special characters,
remove digits, tokenize the words, remove stopwords, lemmatize and stem the text

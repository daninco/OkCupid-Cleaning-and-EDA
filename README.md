# OkCupid Cleaning and EDA

This dataset was picked on the name alone to do an initial clean and EDA.
https://www.kaggle.com/datasets/yashsrivastava51213/okcupid-profiles-dataset 
The dataset is completly unfamiliar to me - I want to practice familiarising myself with the set and seeing what I can learn about it, to see what further investigation can stem from it. 

## Inital impression
Looks to be a suitably challenging dataset to learn with. Lots of different data types, from integers to essay entries. Large enough to have to learn to manipulate and navigate large sets

## During
Many columns to check through and understand. Some are quick, such as 'status' - others need more practice with such as numerical ones like height to more easily sort the values for finding erroneous values

Tried to export some .info to make a tracker in excel to see items all at once to compare but that now seems less useful

Keep going checking through the variables for now


## The Essays - Language processing
I have installed and run NLTK 
Starting with 1 essay (essay 0[0]) I have:
* removed punctuation
* tokeninzed 
* removed the stopwords

I created a visualization for all the essays.

Next is to:
* tune the removal of stopwords and multiple versions of words (run, runner, running, runs, ran etc.)
* find out how to pull figures about the word use - how can I get the raw numbers and make a histogram of the 20 most used words?
    - Created a dictionary of word frequencies to aid this


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

I created a visualization for the one essay.
Next I have been trying to do that for all the essays in one varaible (i.e. all the essay0 entries) but having issues removing the stopwords (I think I am trying to be too slick with the code and should do it longer but clearer)
Next is either trying to scale up to all the essays for one profile 
OR if I manage to do all the essays for one essay varaible, finally scale up to all essays for all profiles.
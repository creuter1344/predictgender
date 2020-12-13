# Project Title

Gender Prediction from description text

## Summary

The goal of this project is to set up a python script making it possible to detect and predict the gender of 10 to 12 year old children by analyzing the text they wrote about what they know of AI


## Background

For a general discussion about chances and risks of AI in our society, it is important, that education about AI starts early. Often children (and even adults) have wrong beliefs about AI. In this project, 10 to 12 year old children are writing a text about what they think AI is and what they know about is.
The question this projet wants to analyze is, if these descriptions have special aspects depending on the gender of the pupils and if it is possible to set up an AI which can predict from a given description the gender of the author of this text.

## How is it used?

In a first step, about 100 children in different classes around the country are asked to write a small description about what they think AI is.
Then all these handwritten text are typed in a computer and analyzed in order to check, if gender-specific elements can be detected and used for gender-prediction of further descriptions.

From the training data (descriptions from the 100 children) are created bag of words. Afterwards this bag-of-words representation is improved by tf-idf to get the weight of occurencies of characteristic word, eventually allowing to predict the gender.


## Data sources and AI methods

I will collect data by asking teachers of 10 to 12 year old children to write a small description about what AI means for them.

## Challenges

It is possible, that there will be no gender-characteristic elements in the descriptions, so that a gender-prediction may not be possible.

## What next?

If gender-prediction will be possible, the project could be enlarged by extending it for other ages.

## Acknowledgments

Thanks to the Elements of AI: Building AI course that really inspired me.

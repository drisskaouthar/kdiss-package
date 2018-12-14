# kdiss-package

## Introduction

In this multiple data sources , we'll have a look at whether countries whose governments adopt open policies with respect to data sharing are the same countries that score highly on the world happiness index. Let's hypothesize that the two are positively correlated.The two datasets shared on Kaggle . The Global Open Data Index is an annual effort to measure the state of open government data around the world. The crowdsourced survey is designed to assess the openness of specific government datasets according to the Open Definition.**Sustainable Development Solutions Network's [World Happiness Report].

The World Happiness Report is a landmark survey of the state of global happiness. The World Happiness Report 2016 Update, which ranks 156 countries by their happiness levels, was released in Rome in advance of UN World Happiness Day, March 20th. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness. They reflect a new worldwide demand for more attention to happiness as a criteria for government policy.

## Reading in Multiple Sources

It's pretty straightforward to read in multiple data sources. 

So, the code below reads in the data sources and joins them together by country name. There are probably some country names that don't exactly match ! So it 's a new challenge to find a solution for that.

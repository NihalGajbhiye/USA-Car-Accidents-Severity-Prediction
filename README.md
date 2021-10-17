# USA-Car-Accidents-Severity-Prediction

## Motivation

The economic and societal impact of traffic accidents cost U.S. citizens hundreds of billions of dollars every year. And a large part of losses is caused by a small number of serious accidents. Reducing traffic accidents, especially serious accidents, is nevertheless always an important challenge. The proactive approach, one of the two main approaches for dealing with traffic safety problems, focuses on preventing potential unsafe road conditions from occurring in the first place. For the effective implementation of this approach, accident prediction and severity prediciton are critical. If we can identify the patterns of how these serious accidents happen and the key factors, we might be able to implement well-informed actions and better allocate financial and human resources.

## Objectives¶
The first objective of this project is to recognize key factors affecting the accident severity. The second one is to develop a model that can accurately predict accident severity. To be specific, for a given accident, without any detailed information about itself, like driver attributes or vehicle type, this model is supposed to be able to predict the likelihood of this accident being a severe one. The accident could be the one that just happened and still lack of detailed information, or a potential one predicted by other models. Therefore, with the sophisticated real-time traffic accident prediction solution developed by the creators of the same dataset used in this project, this model might be able to further predict severe accidents in real-time.

## Process
Data cleaning was first performed to detect and handle corrupt or missing records. EDA (Exploratory Data Analysis) and feature engineering were then done over most features. Finally, Logistic regression, Decision Tree, and Random Forest Classifier were used to develop the predictive model.

It is worth noting that the severity in this project is "an indication of the effect the accident has on traffic", rather than the injury severity that has already been thoroughly studied by many articles. Another thing is that the final model is dependent on only a small range of data attributes that are easily achievable for all regions in the United States and before the accident really happened.

## Key Findings
* California is the state with the highest number of accidents, then we have Texas and Florida.
* Most of the accidents occured near a traffic signal, expecially where a junction or a crossing was present.
* Distance of the accident is more or less proportional to the severity, and accidents with severity 4 have the longest distance.
* Most frequent cases of the weather condition is clear.
* Days with the most accidents are working days, while in the weekend we have a frequency of at least 2/3 less.
* An accident is much less likely to be severe if it happens near traffic signal while more likely if near junction.

## Dataset Overview
This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2020, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 1.5 million accident records in this dataset. Check here to learn more about this dataset.

Link for kaggle dataset: https://www.kaggle.com/sobhanmoosavi/us-accidents

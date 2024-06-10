# Effect of Community Events on Online ISIS Sympathizer Activity.
> By Omar Romero Godoy and Logan De La Torre


## Introduction

> For our project, we looked at tweets from Islamic State extremist supporters from 2014 to 2016. Our research question is "How do counter-extremism efforts influence the evolution of extremist rhetoric on social media platforms?" The dataset we used is from Fifth tribe, and stores tweets from ISIS 'fanboys' from January 2015 to June 2016. We also got motivation from Countering Violent Extremism and Radical Rhetoric paper by Tamarr Mitts.


> For our research, we are utilizing word embeddings with the hope to have vector representations of the text data. We will then also use LDA topic clustering to identify and compare the main topics that IS members discuss before and after counter-extremism efforts.  For context, counter-extremism efforts were events held by the US government to lower the potential threats of Islamic State supporters.
 
## Hypothesis: 

> We believe that counter-extremism efforts will result in ISIS sympathizers changing their tweets to more broad and less ISIS-related tweets.

## Methods

> For our methods, we used an LDA approach to get the top words from five topics for 2015 and 2016. We used five topics because it gave us the average highest coherence score.
> Our second method was word embeddings using Word2Vec. We looked for words similar to: 1) Isis 2) Syria 3) Attack 4) Allah

## Data Preprocessing

> Another important note is that we subsetted the dataset into two smaller ones. One for the tweets from 2015, and another one for the tweets from 2016. These were named df_2015 and df_2016 on the code.
> To clean up the dataset, we decided to remove stop words, make all the words lowercase, remove numbers, remove 'http' from all tweets, and then turn it into  document term matrices. 

## Results/Graphs/Visual Representation for LDA Analysis

> Below is our results from the LDA analysis
<img width="347" alt="image" src="https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/6cc304cc-3cc7-43ce-822c-16c625fb86a1">

> We also did a time series that shows how many tweets each topic had over the span from January 2015 to May 2016. Below are the results we got for the time series.
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/28e7e695-8923-4a64-a4f9-3835e78ad66a)

## Results/Graphs/Visual Representation for Word Embedding
> For our word embedding, we decided first to show the results for the words with the highest scores, and then make a word cloud for each topic and the most popular words for 2015 and 2016.

> Below is our results from the word embedding
<img width="1142" alt="image" src="https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/d8d7ffc0-3b4f-4e79-9efb-ccb805ffc85b">

> We ran a word cloud for the word embedding. Below is the results we got from the word embedding for 2015 tweets.
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/8d14fc5b-5c65-4965-a764-75f7bb7458d4)
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/f58a6206-e199-4490-a071-c509b421f123)
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/b5ce0c35-e267-46a8-92db-9aa5f3f56d77)

> Below are the word clouds from 2016 tweets.
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/d1f0b6a4-dfc3-4a32-bf30-6d0228eb3e5b)
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/66de9b02-178d-4f7f-a4e0-b657f702ba82)
![image](https://github.com/Ldelatorre81/Poli_179_final_project/assets/169123981/a9bc4675-e54b-4a26-a23e-142b130f8cf7)

## Conclusion and Findings

> For the LDA analysis, our findings show that while Propaganda, information sharing (https, rt), geographical focus, and religious discourse stayed fairly similar for both years, we saw a change in how ISIS sympathizers started to switch to a more specific discussion about the military, breaking news, and violent events.

> For the word embeddings, our findings show that ISIS sympathizers switched to more particular tweets. These include particular attacks, military movements, and other terrorist groups. Before the tweets were more ideological.

> Thus, our overall conclusion is that the counter extremism events did end up changing how ISIS sympathizers use social media. They started being more strategic with their tweets and tweeting more around Isis on tactical & military aspects rather than ideology like before the events.
> 
## Key Links 

Step-by-step instructions on how to install and set up your project. Include any prerequisites or dependencies.

```bash
# Link to our github
git clone (https://github.com/Ldelatorre81/Poli_179_final_project.git)

# Link to the dataset we used:
(https://www.kaggle.com/datasets/fifthtribe/how-isis-uses-twitter)





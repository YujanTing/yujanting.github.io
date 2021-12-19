---
title: "Precisely Detecting Vespa Mandarinia Among Hornets"
excerpt: "Predict the spread of the Asian giant hornets by developing a Spread of Hornets Forecast Model, Embedding Classification Model, and Learning Classification Model. <br/><img src='/images/word_cloud.png'>"
collection: portfolio
---
To view the full paper [here](http://lizeman.github.io/files/MCM_2021.pdf)


Summary
======


The Vespa mandarinia, also called the Asian giant hornets, originated from Japan, was found in North America. People are worried about their harm to the ecological balance due to their damage to the honeybees. The government is in hurry with solving the problems by the reports from websites and hotlines created by them.

First, we would like to predict the spread of the Asian giant hornets. Given the dataset 2021MCM_ProblemC_DataSet.xlsx, we develop a Spread of Hornets Forecast Model using several field information, including Global ID, Date, Lab Comments and Status, Notes, and latitude and longitude. Before deciding the model, we take into account the lack of positive cases and assume the migration of the pest as random. A 30-km range is considered to be nest-established range for the hornets to improve our equation and model. Secondly, we begin the pure text analysis from people’s reports. We eliminate the meaningless words, such as ‘I,’ ‘see,’ from the text to search the keywords more precisely. Then, we established the Word Embedding Classification Model to extract the frequency of words from the reports. To increase the accuracy and efficiency of computing, we use this word embedding model to convert words in text version into numerical vectors. By processing through all the ‘vectors,’ we can get the keywords of the Asian giant hornet classification and the likelihood of mistaken classification to other hornets. Thirdly, because of the limited positive data set, we use Deep Learning Classification Model to further improve the solution of same classification problem as Word Embedding Model. By processing the image with actions such as flipping or rotation, we can augment the images and accelerate the previous models. In addition, to prioritize the investigation of the reports, we combine the previous three models as a weighted equation and get a final score from it. By having a numerical result, the government can visually determine the priority of the positive cases. 

Furthermore, as more cases are reported in the future, our models can be optimized. The three models are closely related and supported each other. By getting more positive reports, we can enlarge the positive data set by Classification Models and get more precise prediction of hornets’ spreading. Moreover, we also predict how the situation that the Asian giant hornets are eradicated will be like, so that the government can easily realize the success of eradication. Finally, we wrote a Memorandum to report the whole investigating process and the results.

Remark: To avoid copyright issues, we draw all the graphs on our own.

Keywords: Spread of Hornets; Spread of Hornets Forecast Model; Word Embedding Classification Model; Deep Learning Classification model; Classification

Equally contributed and credited to Yujan Ting, Caixin Tong. 

![Our hand-drawing Image of Wasp](http://lizeman.github.io/images/wasp.png)

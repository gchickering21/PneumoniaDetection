## Initial project proposal

It has been estimated that roughly 80% of healthcare data is unstructured data, which can come in the form of videos, sensor data, images, or text. Although hospitals and researchers used to have a hard time extracting insights from this type of data, with the recent advances that have been made in data science and handling big data, this has 
created new application areas within the healthcare industry in sectors such as genomics, drug trials, predicting patient health, and medical imagery. Medical imaging research in particular has made significant progress by the advances that have been made in artificial intelligence and machine learning and it is the area that I hope to base my project around. For my project I am hoping to explore the areas of medical imagery and image anomaly detection through the use of different machine learning models. My goal for this project is to combine areas of using a large medical imagery dataset to then perform image analysis through the use of different machine learning methods such as neural networks, support vector machines, and deep learning to train and test models to find out which techniques work best in detecting anomalies within the images. 
	The dataset I hope to work with comes from the Open Access Series of Imaging Studies (OASIS) project that provides an open source dataset of neuroimaging datasets of the brain. This data contains over 1000 participants from different projects over the past 30 years. From the roughly 1000 participants, 609 of them are cognitively normal adults and 489 of the individuals are at some stage of cognitive decline, with the patient’s ages ranging from 42-95 years. This data will allow me to answer questions such as how does one handle large datasets in R? How does one handle and perform analysis on unstructured data such as images? How does one perform image analysis? And finally, what are the best machine learning techniques to perform and optimize image detection?

## Proposed Tasks: 
Describe 2-4 tasks that will allow you to demonstrate your ability to communicatestatistical ideas, perform analysis, and use a new statistical technique to address a question of interest to you. Your proposal should clearly identify how your proposed tasks build upon your current knowledge but not replicate prior academic work. (To be specific, if you have studied your proposed method previously, this should be noted in detail on your proposal as the goal is to identify a new statistical approach.)

The approach I would take towards tackling this issue would be to first learn how to work with and handle a large image dataset in R. By using a publicly available dataset such as OASIS that contains neuroimaging datasets of the brain, the first step in the project would involve learning how to work with unstructured brain imagery and getting it into a form that I can perform analysis on. The OASIS-3 dataset is a retrospective compilation of cognitive imagery data for over 1000 participants that were collected across several projects. Since this is a very large medical imagery dataset, another important factor will be learning how to deal with big data in R, and potentially incorporating and learning about other software such as Hadoop or Spark to handle big data would be another key feature. Once I learn about how to work with unstructured data, I hope to build off work I have done in my Multivariate Data Analysis and Machine Learning courses and apply new machine learning techniques that I am not currently familiar with. A couple of these potential techniques are neural networks or deep learning, two techniques I do not currently know anything about and would be brand new to me. Through this final stage of the project I hope to learn about different techniques that would optimize these algorithms and find ways to improve image anomaly detection beyond the standard models.
Through this process the key areas I would hope to learn about is dealing with unstructured data, dealing with large datasets and Big Data, image analysis, and then finally deep learning and neural networks and finding ways to optimize these different techniques.


## Feedback

Graham, I like how this is shaping up.  This is an interesting and compelling project that should be very cool.

I'm wondering whether you could explore use of Spark with Pipeline models (see https://spark.rstudio.com/guides/pipelines/) as the basis for your project.

This would allow you to explore some innovative technologies and demonstrate your mastery of the project material.  (This would also complement and not overlap work that you are doing in your Machine Learning course.)

Can you please resubmit a revised project proposal (in file revised_project.md) that addresses this suggestion?

I'll need the revised proposal by noon on Sunday in order to review it.
(Please close the issue that I've created when you are ready for me to take a look.)

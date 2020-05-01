# ImageClassDash

### Team Project for Duke University's IDS 690/ECE-590
### Data Analysis at Scale in the Cloud

#### Team Members: William Huang, Joe Littell ,Frank Xu, and Allison Young

This project uses the **MobileNet** image classification model in conjunction with **Plotly Dash**, which is built on Flask,
to conduct a single image classification. The application itself uses **Google's App Engine** to *deploy* 
and *scale* the project to accept up to *1000 requests per second.* A test was conducted using **Locus** to ensure 
its elasticity.

The application is located here: **http://35.225.174.151:8888/**

The user is expected to upload a single image of file format .png, .tif, or .jpg. The MobleNet image classification model
will resize the image and give it's predicted classification along with it's confidence in that prediction. 

A demo video of the project is located here : **Place Holder**

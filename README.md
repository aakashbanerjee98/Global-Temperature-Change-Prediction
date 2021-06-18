# Global-Temperature-Change-Prediction

A basic GitHub repository example for new [Call for Code](https://developer.ibm.com/callforcode/) projects and those that join the Call for Code with The Linux Foundation deployment initiative. Not all sections or files are required. You can make this as simple or as in-depth as you need. And don't forget to [register for Call for Code 2021](https://developer.ibm.com/callforcode/get-started/)!


## Contents

- [Global-Temperature-Change-Prediction](#submission-or-project-name)
  - [Contents](#contents)
  - [Short description](#short-description)
  - [Long description](#long-description)
  - [Demo video](#demo-video)
  - [Project roadmap](#project-roadmap)
  - [Built with](#built-with)
  - [Version](#version)
  - [Authors](#authors)
  - [Acknowledgments](#acknowledgments)

## Short description
Predicting the temperature for next 10 years from the previous 116 years data using LSTM model (3 Layers)


## Long description

The phrase Sustainability is used to explain many distinctive strategies for enhancing our existence. The biggest threat to environmental sustainability is climate change. Climate movement gives a tremendous possibility to liberate large economic and social advantages that can assist us obtain the Sustainable Development Goals. SDG aims to “take immediate action to fight climate change and its impact”, while acknowledging that we are making a model to predict the Global Temperature with the aim that we can take the necessary precautions to minimize weather-associated risks.

 - We take the monthly temperature from 1880 to 2020 dataset. We then clean our dataset and add a column for average annual temperature for the said years.
 - We will then proceed by splitting the training and testing set in a 90:10 ratio.
 - We would need to create a collection of training data by which the x-values will be a 116-year windowed data and the corresponding y-value as the subsequent temperature change data in the next 10 years.
- We have :
  - LSTM : the 116 units represent the 116-year windowed datasets while the returned value specifies the input of the next layer.
  - Dropout(p=0.2): for regularizing effects and preventing the training set’s over-fitting.

- The model has been trained for 500 epochs. So we get the predicted temperature helping us to determine how the global temperature is going to change and what essential precautions or steps we should take to save the environment.

We are building a Global Temperature Prediction model which can efficiently estimate the average Global temperature of the next 10 years using 116-year participation records across the world. Although warming has no longer been uniform across the world, the upward fashion inside the globally averaged temperature shows that more regions are warming than cooling. However, the hypothesis of working with the global average temperature is convenient for monitoring the changes in Earth's energy. 
The Global Temperature Prediction model can determine that Earth’s global average temperature will rise day by day, but the change in the climate depends on the decisions we make about fossil fuel and land use. If we keep emitting as much as, or even more, greenhouse gases, then this will cause immeasurably more warming during the 21st Century than we have seen in the 20th Century. Despite the COVID-19 lockdown, according to NOAA's 2020 Annual Climate Report the integrated land and ocean temperature has increased at an average rate of 0.08 degrees Celsius in every 10 years since 1880; however, the average rate of rising since 1981 (0.18°C) has been more than twice that rate. Here through our project we are predicting the change of temperature for the next 10 years so that we can take preventive measures to avoid serious consequences of climate change.
We perceive that climate change is already occurring and additionally warming is unavoidable. If we hope to limit the negative impacts of climate change, we must prepare by identifying vulnerabilities and planning accordingly. Temperature predictions help us to prepare ourselves for climate change.




## Demo video

[![Watch the video](https://github.com/Call-for-Code/Liquid-Prep/blob/master/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)


## Future Scope

Our submission is the implementation of data science using deep learning to predict the Global average temperature for the next 10 years. We are in the initial stages of building a project that will help us to quantify and analyse the degree of environmental sustainability that we desire to achieve. Our submission is moderately stable.

For further development of our project we aspire to take real time data and predict the outcome for following years. Our model helps to analyse the environmental sustainability for global temperature. There is also the aspect of predicting rainfall and other natural phenomena which we intend to incorporate in the future. We also want to also include aspects of social sustainability by including models to promote health and diversity. Moreover, environmental sustainability using stock prediction using machine learning will also be part of our entire project. All of this will be done with the goal in mind to achieve sustainability. 


## Project roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/roadmap.jpg)



## Built with

- [IBM Watson Studio](https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/f48c69b9-4027-4bd2-9c97-74cc86a8e7f0/view?access_token=2dbef31a093f9e95b7be5f3e85bd1722b3057797bab71d419917d921d0c87771) 



## Version

This version 1.0

## Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)



## Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).

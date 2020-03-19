[< back](../Lab2.md#The-Plan-for-the-Day)

# Lab 2.2: Working with Cognitve Speech Services

In this session, we will take a closer look at how to integrate pretrained models into your data pipelines and applications.

>*By using the Microsoft Cognitive Services Speech SDK in these samples, you acknowledge its license. See [Speech SDK license agreement](https://docs.microsoft.com/azure/cognitive-services/speech-service/license).*

## Pre-requisites
We assume that you have provisioned an instance of the Azure Cognitive Services <u>in your subscription</u>. If you don't have one yet, please go back to [this section](../hands-on-session1/lab2-1-guide.md#2-provision-your-own-cognitive-services-instances) from the morning's lab.

This track does not assume prior coding knowledge - please don't hesitate to ask questions if anything is unclear.

Make sure that you have the files in the 'hands-on-session2' folder availalbe locally and can navigate to the sample folders on the command line - either by cloning the entire AIForGoodCurriculum repo or by downloading individual files and folders from the Github web interface. 

## 1. Transcribe speech from your microphone with a python console app
[![Generic badge](https://img.shields.io/badge/mode-python-BLUE.svg)](https://shields.io/)

#### Lab objectives
- Be set up to work with python on your local machine
- Introduction to the python cognitive services speech SDK to integrate cognitive services into python applications.

> -> go to [instructions](python_sample/README.md)


## 2. Convert written text to speech with a node.js console app
[![Generic badge](https://img.shields.io/badge/mode-nodejs-GREEN.svg)](https://shields.io/)

#### Lab objectives
- Learn how to integrate cognitive services into node.js applications. Node.js is a common implementation for building custom backends (APIs) for web applications. 

> -> go to [instructions](node_sample_tts/README.md)


## 3. Translate text within a Jupyter Notebook
[![Generic badge](https://img.shields.io/badge/mode-python-BLUE.svg)](https://shields.io/)

### Lab objectives
- Get to know the Azure Cognitive Translation Service
- Work with jupyter notebooks for data science workflows and prototying on Azure

> -> go to [instructions](nb_sample/README.md)


## 4. Integrate the speech services from a web client with javascript
[![Generic badge](https://img.shields.io/badge/mode-javascript-YELLOW.svg)](https://shields.io/)

#### Lab objectives
- Work with the speech sdk for frontend javascript
- Build a basic web application that interacts with your cognitive services

> -> go to [instructions](js_sample_stt/README.md)


<hr>

## Give Session Feedback
> 💬 Please fill out the session feedback: http://bit.ly/AI4GFeedback 💬

<hr>


## Go Further:
[![Generic badge](https://img.shields.io/badge/mode-python-BLUE.svg)](https://shields.io/)

This lab extends the python console app you built in 1. to explore more of the Cognitve Speech capabilities:
https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/samples/python/console


[![Generic badge](https://img.shields.io/badge/mode-nodejs-GREEN.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/mode-javascript-YELLOW.svg)](https://shields.io/)

If you have some experince with web development, you may want to see if you can integrate your Cognitive Service into a web application deployed to the Azure App Service. 
This tutorial is a great starting point, implementing both a backend and a frontend. 
https://github.com/microsoft/Windows-tutorials-web/tree/master/Single-Page-App-with-REST-API 

> 💡 ***Hint:*** *You can either use what you learnt in `3.` above and integrate directly from the front-end (your code will mostly go into the `public/javascripts/scripts.js` file in the app template), or you can take some ideas from `2.` above for even better practice to implement the Cognitive Services integration in the backend.*


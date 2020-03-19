[< back](../lab2-2-guide.md)

*Note: This sample is adapted from https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/samples/js/browser*

## Introduction

This sample demonstrates how to recognize speech with the Speech SDK for JavaScript on a web browser, like Microsoft Edge, or Chrome.
See [this article](https://docs.microsoft.com/azure/cognitive-services/speech-service/quickstart-js-browser) for introductory information on the Speech SDK for JavaScript.


## 1. Configure

* Ensure that the [js_sample_stt](../js_sample_stt) folder from this repo is available on your local machine.
* Note: the sdk is already present in the js_sample_stt folder. If you need to download it for your own projects, you can get it here: [Speech SDK for JavaScript .zip package](https://aka.ms/csspeech/jsbrowserpackage).

## 2. Run

To be able to properly access the microphone, it is best to run the app on a web server. 
We can spin up a simple one with python:

Within the `js_sample_stt` folder on your machine, run the following:
```py
# for python 2
python -m http.server

# for python 3
python -m SimpleHTTPServer
```
## 3. Explore the capabilities in your browser
Navigate to `http://localhost:8000` in your browser, where the index.html file will be served. 

Remember to set both your key and your region in the relevant fields. 

>⚠️ Note that we have not configured the Azure Language Understanding Intelligent Service (LUIS), and so intent recognition will not be available in your app. We will cover LUIS in later labs, but feel free to explore further in the references below.


[Next >](../lab2-2-guide.md#give-session-feedback)

<hr>

### References
* [Full instructions for this sample](https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/samples/js/browser)
* [JavaScript quickstart article on the SDK documentation site](https://docs.microsoft.com/azure/cognitive-services/speech-service/quickstart-js-browser)
* [Speech SDK API reference for JavaScript](https://aka.ms/csspeech/javascriptref)

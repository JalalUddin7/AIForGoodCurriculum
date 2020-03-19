[< back](../lab2-2-guide.md)

*This sample is adapted from https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/quickstart/python/*

<hr>

## Introduction
This sample code demonstrates how to integrate the transcription of a spoken phrase into a simple python console application.

We will run this speech-to-text sample locally to avoid complexities around connecting a VM to your microphone. (Note that the Windows Subssystem for Linux (WSL) also does not have access to your microphone by default, so we recommend running this in your native environment)

To do this, steps 1-2 below help you set up conda to manage consistent python environments on your machine. If you're happy to install the azure speech sdk into your system's python, or you are already familiar with conda, you can skip these steps and go straight to step 3.

### Lab objectives
- Be set up to work with python on your local machine
- Introduction to the python cognitive services speech SDK to integrate cognitive services into python applications.

### Steps

1. Install Miniconda3 from [here](https://docs.conda.io/en/latest/miniconda.html) if you don't already have it. (See also [here](../../additional_material/lab2-tips_and_tricks.md#Working-with-Conda) for more detailed help)

   Then:
   - On Windows, launch the anaconda prompt from your start menu.
   - On Linux, type `conda activate` at your command prompt.

   You should see the annotation `(base)` at the beginning of your command prompt, indicating that you are in the base python environment managed by conda. 


2. Create a generic python environment called 'aifg' and activate it.
   ```
   conda create --name aifg python=3.7
   conda activate aifg
   ```
   You should now see `(aifg)` in front of your prompt to indicate which environment you are in. 

   Note: at this point, you can optionally [switch into VScode](link).


3. Install the Azure Cognitive Services speech SDK using pip
    ```
    pip install azure-cognitiveservices-speech
    ```

4. Update the `stt_local.py` script with your cognitive service API key and service region (e.g. `uksouth`).

   ```py
   # line 9: 
   speech_key, service_region = "YourSubscriptionKey", "uksouth"
   ```

5. Execute the script from the command line, and speak when prompted.
   ```
   python stt_local.py
   ```

   The script will record any spoken phrase until a significant pause is reached, and will then output the transcription to your console.


[Next >](../lab2-2-guide.md#2-convert-written-text-to-speech-with-a-nodejs-console-app)

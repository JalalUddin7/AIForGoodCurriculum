[< back](../lab2-2-guide.md)

*This sample is adapted from https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/cognitive-services/Speech-Service/quickstart-nodejs-text-to-speech.md*

## Introduction

This sample code demonstrates how to integrate a speech-to-text transformation into a simple node.js console application. It takes typed text and creates an audio file with the converted output.

### Lab objectives
- Learn how to integrate cognitive services into node.js applications. Node.js is a common implementation for building custom backends (APIs) for web applications. 

### Steps
1. Ensure node and npm are available on your system.

    **Install node on Windows:**

    - Install from https://blog.teamtreehouse.com/install-node-js-npm-windows.
    - Opt for the long-term-support (LTS) version.
    - Restart your machine.
    
    **Install node on Linux:**
    - Follow the steps here: https://www.ostechnix.com/install-node-js-linux/
    - We recommend following method 1. and installing with nvm.
    
    - Install the latest LTS version. 
        ```bash
        nvm install lts/*
        ```

2. Open your command line tool or VScode terminal and verify your installation.
    ```js
    node -v
    // -> v12.16.1
    ```

3. Make sure the `node_sample_tts` folder in this repo is available on your system, and navigate to in your command line tool.

    Install the dependencies with the following command:
    ```bash
    npm install
    ```

4. Save your Azure Cognitive Services key in an environment variable.

    Linux:
    ```bash
    export SPEECH_SERVICE_KEY='Your_Cognitive_Services_Key'
    ```

    Windows (tested in Powershell):
    ```ps
    $env:SPEECH_SERVICE_KEY = 'Your_Cognitive_Services_Key'
    ```

    ⚠️*Note - the script assumes your region is `uksouth`. If your Cognitive Services instance is elsewhere, you need to edit the `tts.js` file to update two endpoint urls.*

5. Run the console app:
    ```
    node tts.js
    ```
    The app will prompt you to enter text to be transformed to speech, and will store the output in a .wav file in the same folder.

For additional configuration options, see the full notes for this sample [here](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/cognitive-services/Speech-Service/quickstart-nodejs-text-to-speech.md). 

[Next >](../lab2-2-guide.md#3-translate-text-within-a-jupyter-notebook)

<p align="center">
  <a href="" rel="noopener">
 <img height=125px src="./meeting-minutes.png" alt="Meeting-Minutes"></a>
</p>
<h1 align="center">Meeting Minutes App</h1>

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<h4> <strong>Meeting Minutes App</strong> can be used to record the audio of a meeting, convert speech-to-text, and store the transcript for future reference. It also supports speaker diarization, text summarization, and has in-app calendar integration.</h4>

</div>

-----------------------------------------
### Features

- `Record audio and create transcript notes` : Hit the Record icon to record audio, and the app will start listening. When done, hit the same button again, and text is generated. IBM Watson Speech to Text API is used for real-time and accurate transcription.
- `Edit text after recording` : The generated text can be edited to correct spelling or grammatical errors, or to add some text to the note before saving it.
- `Text summarization` : View a summary of the text in case of longer audios. A bag-of-words model is used for keyword extraction and text summarization.
- `Calendar integration` : In-built calendar to save important dates and reminders.
- `Save the notes` : Store the text in a txt file for future reference.
- `Load a saved note` : Load a previously saved file along with its summary within the app itself.

------------------------------------------
### Demo
<p align="center">
    <img width=300px height=533px src="./Demo.gif">
</p>


------------------------------------------
### Installation
* For Usage
    * Download the [`Meeting-Minutes.apk`](./Meeting-Minutes.apk) and install it on your device. 
    * Grant the required permission to the app (To record audio).
  
* For Development
    * Clone the repo
    ```sh
        $ git clone https://github.com/mihir-m-gandhi/Meeting-Minutes-App
    ```
    * Open `Code` folder in Android Studio.

------------------------------------------
### Note
- This project was done in less than `24 hours with minimal pre-preparation` at KJSCE hackathon 2018.

------------------------------------------
### Contributors

Mihir Gandhi - [mihir-m-gandhi](https://github.com/mihir-m-gandhi)

Siddharth Umachandar - [siddharth9805](https://github.com/siddharth9805/)

Amit Bhujbal - [amit99](https://github.com/amit-99)

Shivam Mahajan 


------------------------------------------
### License
This project is licensed under the MIT - see the [LICENSE](./LICENSE) file for details.

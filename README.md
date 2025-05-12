# VibeDub

Dubs the video in another language — automatically and efficiently.
VibeDub uses the Deepgram API to transcribe audio from your video with high accuracy, then leverages Google Translate to convert that transcription into your target language. The result is a newly dubbed video, complete with synced audio and translated speech — all in a few steps.
***
<br><br>
Check out the [Assets folder](./assets/) for Demo videos. 

# 👀 Why VibeDub?

<font align="left" size="3">
  - Sometimes, we need to quickly dub a video in another language.
  - VibeDub automatically generates subtitles, translates it to another language and then adds it to the video.
</font>

<br>

# Usage

Using is very easy, just follow the steps below:

Clone the repository:

```bash
git clone https://github.com/subhm2004/VibeDub.git
```
## Install the dependencies:

```bash
pip install -r requirements.txt
```
## Create a .env file
Create a .env file in the root of your project and add the following line to it:

```bash
DEEPGRAM_KEY=your_deepgram_api_key_here
```

## Run `src/main.py`

Make sure to change the path to your video, and feel free to configure as you want.
```bash
python ./src/main.py
```
## Made with ❤️ by Shubham Malik

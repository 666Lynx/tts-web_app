# tts-web_app ✦✦
TTS web app using gemini and browsers native speech synthesis api


Welcome to the TTS Web App Repository. this repo was made to upload code for Web app used to make audio files from text.

### Goal ✦✦
The Goal of this project was to generate Good Quality Audiobook for Light Novel which I often enjoy.

## How it works ✦✦
### for tts_local.html
- Uses the browsers native speech synthesis api to generate TTS fast.
- works offline
- lightweight


### for tts_with_gemini-api.html
- Uses Google's gemini-2.5-flash-preview-tts by making real time API calls to generate high quality audio file
- Requires Internet
- Divides the text input to chunks of 200 charecters at sentence breaks.
- after converting each chunks to speech. the files are stitched together in a single file.


## How to Use ✦✦
### for tts_local.html
Just copy the code and open the file in browser



### for tts_with_gemini-api.html
save the file and add your gemini api key at line 77. Then open it in browser

**Option to download .wav file is available**

Enjoy and have fun ✦

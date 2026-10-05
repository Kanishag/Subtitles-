# Auto Subtitle Generator

Generate subtitles from a video using OpenAI Whisper and ffmpeg. Runs on Google Colab, so it works even from a phone.

## Features
- Speech-to-text subtitles with Whisper
- `.srt` export and subtitles burned into the video
- Language selection and translate-to-English
- Adjustable subtitle font size
- Gradio web UI
- Model comparison (tiny / base / small): speed and WER

## How to run
1. Open `auto_subtitle.ipynb` in Google Colab
2. Runtime → Change runtime type → T4 GPU
3. Run the cells in order
4. For the web UI, run the last cell and open the public link

## Results
| Model | Time (sec) | WER |
|-------|-----------|-----|
| tiny  |           |     |
| base  |           |     |
| small |           |     |

## Credits
Transcription by [OpenAI Whisper](https://github.com/openai/whisper).

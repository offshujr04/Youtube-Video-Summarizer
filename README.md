# Youtube-Video-Summarizer
The YouTube Video Summarizer is an AI-based tool that extracts key moments from YouTube videos and compiles them into a concise summary. The project automates the process of downloading a YouTube video, transcribing its audio, identifying important sentences, and creating a summarized video containing only the most crucial content.

# Link to access the ipynb file: https://colab.research.google.com/drive/1wDrbPaKeHO19aVJf1KbRu-wny2bK-UlY

# Features

YouTube Video Downloading: Uses yt-dlp to download videos.

Audio Transcription: Converts speech to text using OpenAI's Whisper model.

Text Summarization: Identifies key sentences with TF-IDF and NLTK.

Video Clipping: Extracts relevant segments using FFmpeg.

Summary Video Generation: Combines selected clips into a final summary video.

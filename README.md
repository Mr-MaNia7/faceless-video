# Image to Video Generator

Image to Video Generator is a project that leverages the power of AI to create talking face videos based on just a topic. Using sadtalker for face animation, gTTS for AI voice and OpenAI's language model to generate scripts, this project provides an end-to-end solution for generating personalized videos.

# Text to Video Generator

Generate video from text using AI is a project that:

- Use openai to generate a video script from a topic
- Use edgetts to pick a voice and create a audio based on the above generated script
- Use whisper and get timed captions for the above audio
- Now generate visual keywords for the video script using openai api
- Fetch videos based on the above visual keywords using pexels api
- Stick together the videos, audio and captions using Moviepy

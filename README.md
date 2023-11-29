# gpt4-vision

I updated OpenAI's ["Processing and narrating a video with GPT's visual capabilities and the TTS API"](https://cookbook.openai.com/examples/gpt_with_vision_for_video_understanding) cookbook to include: 

- [Pytube](https://pytube.io/en/latest/) library, which makes it easy to download videos from Youtube
- Ability to slice video into shorter sections, due to OpenAI's current 10,000 token per minute limit (during preview)
- Template with parameters for creating a better prompt to match the video
- Edited mp3 creation from TTS response in order to be able to save audio
- Code for overlaying and combining new audio on top of video and saving it as mp4

Feel free to fork and create your own projects. Hope this is useful and always open to hearing feedback and ideas.

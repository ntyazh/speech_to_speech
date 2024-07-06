# speech_to_speech

The pipeline consists of three parts:
1. ASR of a russian text with Whisper
2. ru-to-en translation 
3. TTS (+ voice cloning) of the en translation with [OpenVoice](https://github.com/myshell-ai/OpenVoice)

Moreover, the original voice in russian is cloned with , so the translation in english is read with the same voice (you can check it with files "voice_ru.m4a" and "voice_en.wav".
   

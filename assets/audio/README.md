# Audio Files for Tutorial Sections

This directory contains audio narrations for each section of the tutorial.

## Required Audio Files

Place the following MP3 files in this directory:

1. **introduction.mp3** - Narration for the Introduction section
2. **datasets.mp3** - Narration for the Datasets section
3. **architecture.mp3** - Narration for the Architecture section
4. **performance.mp3** - Narration for the Performance section
5. **limitations.mp3** - Narration for the Limitations section
6. **quiz.mp3** - Narration for the Quiz section
7. **bibliography.mp3** - Narration for the Bibliography section

## Audio Specifications

- **Format:** MP3
- **Bitrate:** 128 kbps or higher recommended
- **Sample Rate:** 44.1 kHz
- **Channels:** Mono or Stereo

## Creating Audio Files

You can create these audio files using:

1. **Text-to-Speech Services:**
   - Google Cloud Text-to-Speech
   - Amazon Polly
   - Microsoft Azure Speech
   - ElevenLabs (high quality)

2. **Recording:**
   - Record your own voice reading the section content
   - Use a good quality microphone
   - Edit and normalize audio levels

3. **Recommended TTS Voice:**
   - Use a clear, professional voice
   - Moderate speaking pace (around 150-160 words per minute)
   - Natural intonation

## Example Script for Introduction

```
Independent outfit selection is central to autonomy, confidence, and social participation. 
For blind and low-vision individuals, however, the task of choosing clothing that matches 
in color, pattern, or style can be frustrating and often requires assistance. Accessible 
fashion matching seeks to bridge this gap using computer vision and interactive feedback.

[Continue with rest of introduction text...]
```

## Testing

After adding audio files, test the player by:

1. Opening index.html in a browser
2. Clicking the play button in the bottom-left corner
3. Verifying audio plays for each section
4. Testing seek, pause, and volume controls
5. Switching sections to ensure audio updates correctly

## Fallback

If audio files are not present, the player will show but won't play audio. Users can still navigate sections normally.


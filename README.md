# sao-silence-remover

This Python script cleans generated audio files by trimming silence and applying fade-ins/outs, designed for live improvisation workflows. I made this script for the paper "Live Improvisation with Fine-Tuned Generative AI" in proceedings of NIME2025.

For more please go to: www.misaghazimi.com/research/sao_improv

## Features

- **Stereo & Mono Support:** Loads stereo (or mono) audio.
- **Silence Trimming:** Removes leading and trailing silence based on a configurable threshold.
- **Fading:** Applies short fade-in and fade-out effects per channel.
- **Silent File Handling:** Skips saving if the entire file is silent, logging the event instead.

## Usage

1. **Update Paths:** Modify the input and output paths in the script.
2. **Run the Script:** Execute the script using your Python interpreter.  
   Example:
   ````bash
   python clean_audio_file_stereo.py```
   ````

## Dependencies

    •	NumPy
    •	librosa
    •	SoundFile

Install dependencies via pip:

```bash
pip install numpy librosa soundfile
```

## License

This project is licensed under the MIT License. Youa're welcome to use it!

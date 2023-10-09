# PodcastAudioClipper

PodcastAudioClipper is a powerful tool encapsulated in a Jupyter Notebook that takes audio podcasts, transcribes them to text using Wisper, and extracts key topic segments into individual audio clips of up to 5 minutes. The clips are titled based on the key topics identified within the segment, making it a breeze to sort through and share the highlights of your favorite podcasts.

## Features

- **Automatic Transcription**: Transcribes audio podcasts to text using Wisper.
- **Key Topic Identification**: Utilizes KeyBERT for extracting key topics from the transcribed text.
- **Audio Segment Extraction**: Extracts and saves individual audio clips based on identified key topics.
- **Descriptive Titling**: Automatically generates descriptive titles for each clip based on key topics.
- **Silence-based Splitting**: Splits audio on silence, ensuring natural segmentation using PyDub.

## Dependencies

- os
- [KeyBERT](https://github.com/MaartenGr/KeyBERT)
- [Wisper](https://www.example.com) (Replace with the actual URL if available)
- urllib.request
- [PyDub](https://pydub.com/)

## Installation

Ensure you have the necessary libraries installed. You can install the required libraries using pip:

```bash
pip install keybert whisper pydub
```


## Usage
Open the podcastaudioclipper.ipynb file in a Jupyter Notebook environment.
Follow the instructions within the notebook to process your audio files.
Contributing
Feel free to fork the project, create a feature branch, and open a Pull Request if you have contributions you'd like to make.

## License
Provide information about your license or include a link to the LICENSE file.

## Contact
Your Name - your_email@example.com

Project Link: https://github.com/alejandrocordon/PodcastAudioClipper

## Acknowledgments
Thanks to the creators of KeyBERT, Wisper, and PyDub for their amazing libraries that made this project possible.

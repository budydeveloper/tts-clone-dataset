
# 🎙️ My Voice Dataset for TTS Cloning

This repository contains a set of `.wav` audio files of my voice, recorded and processed for use in text-to-speech (TTS) cloning projects. The recordings were made using Audacity, with efforts to clean the sound and improve audio quality.

## 📁 Repository Structure

- **audio/**: Folder containing sequentially numbered `.wav` audio files (`001.wav`, `002.wav`, etc.), each representing a phrase or short text.
- **metadata.list**: File associating each audio file with its corresponding text transcription. The file structure is as follows:
  ```
  <file_name>.wav | <language> | <transcription>
  ```
  Example:
  ```
  001.wav | ES | Artificial intelligence will change the world.
  ```

## 🎯 Purpose

The purpose of this dataset is to provide high-quality voice samples for training or evaluating custom TTS models using my voice to generate audio from text.

## ⚙️ Technical Specifications

- **Audio format**: `.wav`
- **Sample rate**: 44.1 kHz
- **Quality**: Audio has been processed and cleaned in Audacity to reduce background noise and enhance voice clarity.
- **Language**: Spanish (ES)

## 🛠️ Dataset Usage

This dataset can be used to:
- Train voice cloning models that replicate my voice from text input.
- Develop custom text-to-speech applications requiring a specific voice.
- Experiment with audio processing techniques and voice cloning.

## 🔧 Requirements

To play or process the audio files, it's recommended to use audio editing software like Audacity, or audio processing libraries in Python, such as `librosa` or `pydub`.

## ⚠️ Notes

- Ensure compliance with the dataset's terms of use if you plan to share or use the audio publicly.
- This repository does not include TTS tools or models, only the reference audio files and their transcriptions.

## 📞 Contact

For any inquiries about using this dataset, feel free to reach out via my social media or the email listed on my GitHub profile.

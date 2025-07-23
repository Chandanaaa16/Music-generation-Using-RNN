# 🎶 Music Generation using RNN

A deep learning project that generates music sequences using Recurrent Neural Networks (RNNs). The model is trained on musical data and learns to predict the next note in a sequence, enabling it to compose entirely new melodies.

## 📌 Overview
This project explores how RNNs (particularly LSTM networks) can be used to understand the structure and flow of music. The model is trained on MIDI data, learns patterns of musical sequences, and can generate original compositions note by note.

🎧 Built and tested on **Google Colab** for optimal performance using free GPU resources.

## 🎯 Features
- Sequence modeling using LSTM layers
- Trained on MIDI dataset (e.g., classical, jazz, or custom)
- Converts generated predictions back into MIDI format
- Real-time music playback in Colab
- Easy to modify for different genres or datasets

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - TensorFlow / Keras
  - NumPy, Music21
  - PrettyMIDI (optional)
  - Google Colab (runtime)

## 📁 Installation

This project is designed to run best on Google Colab.

### 🔗 Run on Colab


### Optional Local Setup:
```bash
git clone https://github.com/Chandanaaa16/music-generation-rnn
cd music-generation-rnn
pip install tensorflow numpy music21

# 🎵 Music to Visual Cues – AI-Generated Music Visualization

This project explores how artificial intelligence can translate music into visual representations by analyzing auditory features such as rhythm, melody, and harmony. The system leverages **Gemini Pro** (a multimodal large language model) to extract emotional descriptors from music, which are then used as prompts for **Stable Diffusion** to generate expressive visuals.

## ✨ Overview

* **Goal**: Investigate how AI can communicate the mood of a song visually.
* **Approach**: Use audio feature extraction → AI-based emotion description → text-to-image generation.
* **Use Cases**: Accessibility, digital art, synesthetic experiences, HCI, creative tools.

## 🧠 How It Works

### 1. Audio Feature Extraction

* Tempo (BPM)
* Zero-Crossing Rate (ZCR)
* Mel-Frequency Cepstral Coefficients (MFCC)

### 2. Emotion Recognition

* Audio features are processed by Gemini Pro to describe the mood in 4 adjectives/nouns.

### 3. Visual Generation

* Mood descriptions are turned into prompts for Stable Diffusion.
* Tested styles: Abstract, Album Cover, Diffuse Clouds, Imaginary Place.

### 4. Two Modes of Generation

* **Automatic**: Fully AI-driven (song → mood → image).
* **Semi-Automatic**: Allows user to refine AI’s mood description before generating the image.

## 🧪 User Testing

* **Participants**: 23 users from different backgrounds.
* **Findings**:

  * Casual listeners preferred **Album Cover** style.
  * Artistic users leaned toward **Abstract** or **Imaginary Place**.
  * Structured visuals felt more intuitive to most users.

## 📊 Results

* Blues and Pop genres showed distinct mood features.
* Classical music benefited most from semi-automatic refinement.
* Album-style visuals were the most preferred overall.

## 📍 Tech Stack

* Python 3 (Google Colab)
* [Librosa](https://librosa.org/) (audio analysis)
* Gemini Pro (LLM for mood extraction)
* Stable Diffusion (image generation)

## 🔮 Future Work

* Expand music genres and styles
* Include more diverse users (e.g., D/deaf communities)
* Enable real-time visualizations
* Explore accessibility features

## 👥 Authors

* **Yogie Permana**
* **Sabika Amalina**
* **Natalia Sempere**

---

Would you like a matching preview GIF or project thumbnail for the repo?


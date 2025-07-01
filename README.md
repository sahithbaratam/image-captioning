# image-captioning
"Image Captioning with BLIP-1, grammar correction, translation and English voice narration via Gradio.
# 🖼️ AI Image Captioning with Voice Narration

This mini project uses the **BLIP-1** model to generate intelligent captions from images.  
It enhances those captions with grammar correction, translates them to other languages, and plays the caption aloud using Text-to-Speech.

## 🔧 Features

- 🤖 **BLIP-1 Captioning** (`Salesforce/blip-image-captioning-base`)
- 🧹 **Grammar Polishing** with T5 Paraphraser
- 🌐 **Translation** to:
  - Telugu
  - Hindi
  - French
  - Spanish
- 🔊 **Voice Narration (English)** using `gTTS`
- 🖥️ Clean **Gradio UI**

## 🚀 Demo

| Upload Image | Choose Language | Output |
|--------------|------------------|--------|
| ✅ JPG/PNG   | ✅ Telugu, Hindi, French, Spanish | 📜 Caption + 🎧 Voice |

## 📦 Requirements

Install all dependencies with:

```bash
pip install -r requirements.txt

# AI-Powered Video Player with Real-Time Subtitle Generation

An intelligent desktop video player that generates, translates, and enhances subtitles in real time using AI. Designed for immersive video consumption, language learning, and AI-assisted media understanding.

---

## 🎬 Demo

Real-time subtitle generation, dual-language subtitles, and contextual AI translation while playing any local or online video.

*(Demo video coming soon)*

---

## 🚀 Why This Project?

Traditional media players focus only on playback. This project goes further by understanding video content in real time using:

* **Automatic Speech Recognition (ASR):** Converts audio to text instantly.
* **Large Language Models (LLMs):** Powers high-quality, nuanced translations.
* **Context-Aware Translation:** Understands the scene, not just individual words.
* **OCR-Based Extraction:** Reads hardcoded subtitles from the video frames.

The result is a smart video player that dynamically adapts subtitles and makes video content more accessible and understandable.

---

## ✨ Key Features

### 🎯 Intelligent Subtitles
* **Dual Subtitles:** Display both your learning language and native language.
* **Real-Time ASR:** Generate subtitles on-the-fly from any audio source.
* **Contextual Translation:** Uses LLMs to ensure translations make sense in context.
* **Subtitle Seeking:** Click on subtitles to navigate instantly to that moment in the video.

### 🧠 AI & Language Capabilities
* **Whisper Engines:** Supports various Whisper models for speech-to-text.
* **Hybrid Translation:** Use local models for privacy or cloud APIs for power.
* **Word Lookup:** Instant translation and lookup for specific words.

### 🖼️ OCR & Accessibility
* **Bitmap to Text:** Converts image-based subtitles to selectable text.
* **Hardcode Support:** Works even on videos where subtitles are part of the image.
* **Subtitle Sidebar:** A dedicated panel to search and review the transcript.

### 🌐 Online Video Support
* **URL Streaming:** Stream and analyze online videos directly via URL.
* **Live Processing:** Apply AI features to streamed content in real time.

### 🎛️ Customization
* **Modern UI:** Dark-themed interface designed for focus.
* **Full Control:** Customizable shortcuts, subtitle positioning, and font sizes.
* **Backend Flexibility:** Swap between different ASR and translation providers.

---
## ✅ System Requirements

### Operating System
* **Windows 10** (x64, version 1903 or later)
* **Windows 11** (x64)

### Runtime Dependencies
* **.NET Desktop Runtime 9**
* **Microsoft Visual C++ Redistributable** (2022 or later)
    * ⚠️ *Note: Without the Redistributable, ASR and OCR features may crash.*

### GPU Acceleration (Optional)
* **NVIDIA CUDA** supported.
* **CUDA 12.8** recommended for RTX 50xx GPUs.

---

## ⚙️ Getting Started

1.  **Download:** Get the latest build from the repository.
2.  **Launch:** Run the application executable.
3.  **Configure ASR:** * Navigate to `Settings` → `Subtitles` → `ASR`.
    * Download a Whisper model and choose your acceleration (CPU, CUDA, or Vulkan).
4.  **Configure Translation:** Set your target language and preferred backend.
5.  **Play:** Drag and drop a file or paste a URL to begin.

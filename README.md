# 🎬 AI Text-to-Video Generator (No API Key)

This project generates **10-second high-quality videos** from text prompts using open-source AI models. It is designed to run in **Google Colab** or any local system with a powerful NVIDIA GPU.

## 🚀 Features
- **No API Key Required**: Uses the open-source `damo-vilab` ModelScope model.
- **10-Second Clips**: Automatically generates and stitches multiple 2-second segments.
- **High Quality**: Includes negative prompting to reduce blur and artifacts.
- **Local/Cloud Ready**: Works in VS Code or Google Colab.
## 📺 Sample Gallery

Check out the AI video generation in action:

[![Watch the Demo](https://github.com/Soumyo2025/BCT/blob/main/path_to_a_screenshot.jpg?raw=true)](https://github.com/user-attachments/assets/611a263e-df80-420a-988d-af7cf28d5799)

*Click the image above to play the video.*

## 🛠️ Installation
If running locally, you will need:
```bash
pip install torch diffusers transformers accelerate moviepy



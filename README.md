# 🎬 AI Text-to-Video Generator (No API Key)

This project generates **10-second high-quality videos** from text prompts using open-source AI models. It is designed to run in **Google Colab** or any local system with a powerful NVIDIA GPU.

## 🚀 Features
- **No API Key Required**: Uses the open-source `damo-vilab` ModelScope model.
- **10-Second Clips**: Automatically generates and stitches multiple 2-second segments.
- **High Quality**: Includes negative prompting to reduce blur and artifacts.
- **Local/Cloud Ready**: Works in VS Code or Google Colab.

## 🛠️ Installation
If running locally, you will need:
```bash
pip install torch diffusers transformers accelerate moviepy


## 📺 Sample Gallery

Check out what this AI can generate:

<video src="https://github.com/Soumyo2025/BCT/blob/main/final_hq_video.mp4?raw=true" width="100%" controls>
</video>

---
*Generated using ModelScope and MoviePy*

# IMAGENE
AI Comic Crafter: Transforming Text into Visual Storytelling
## About the Project:
IMAGENE, the ComicCrafter AI, is a generative AI based comic generator running locally on edge devices that generates a comic style story based on user-provided prompt. It utilized Hugging Face’s transformer and Stable Diffusion XL. . 
## Features:
- **Fully AI-Generated Stories:** Users provide a prompt, and the AI autonomously creates a complete comic storyline.
* **AI-Generated Illustrations:** Stable Diffusion XL generates comic panels that match the AI-created story.
+ **Panel Selection Interactivity:** While the AI generates the full comic, users can select and refine specific panels for better alignment with their vision.

## Built with:
### Libraries-
torch,
matplotlib,
numpy,
cv2 (OpenCV),
transformers,
diffusers,
PIL (Pillow),
gradio,
llama-cpp-python,
accelerate,
safetensors,
torchvision
### Packages-
llama-cpp-python,
torch,
diffusers,
transformers,
accelerate,
safetensors,
matplotlib,
Pillow,
gradio,
torchvision,
numpy,
opencv-python
### Platform-
google.colab.drive
## Steps to run the project:
1. Prompt to Script
LLaMA 2 extends brief prompts into coherent storylines with stable characters and natural dialogue, optimized with Transformers, Accelerate, and BitsandBytes.

2. Script to Scenes
A BERT summarizer and T5 detect pivotal scenes and pull narration/dialogues, automatically structuring them into comic panels.

3. Scenes to Art
Stable Diffusion XL and ControlNet produce comic-style artwork; DreamBooth, GFPGAN, and OpenCV enhance character consistency, backgrounds, and lighting.

4. Assembly & Layout
Text and imagery are blended together into comic strips through live preview with Gradio and narrative-visual consistency being provided by CLIP.

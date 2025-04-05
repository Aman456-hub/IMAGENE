# IMAGENE - AI Comic Crafter
**Transforming Text into Visual Storytelling**

![Project Banner](https://github.com/user-attachments/assets/43d8804f-cead-438e-93d5-2b43dba4d9ba)

## 🌟 About the Project
IMAGENE, the ComicCrafter AI, is a generative AI-based comic generator designed to run locally on edge devices. It seamlessly transforms user-provided prompts into captivating comic-style stories using cutting-edge technologies like Hugging Face’s Transformer and Stable Diffusion XL. It utilizes LLaMA and Stable Diffusion to generate comic panels with text bubbles from user prompts, using cloud-based processing to deliver AI-powered visual storytelling from textual input.

## ✨ Features
- **AI-Generated Stories:** Users input a prompt, and the AI autonomously crafts a complete comic storyline.
- **Dynamic Illustrations:** Stable Diffusion XL generates vibrant comic panels aligned with the story.
- **Interactive Panel Selection:** Users can choose and fine-tune specific panels to ensure the visual narrative matches their vision.

## 🛠️ Built With
### Libraries
- torch
- matplotlib
- numpy
- cv2 (OpenCV)
- transformers
- diffusers
- PIL (Pillow)
- gradio
- llama-cpp-python
- accelerate
- safetensors
- torchvision

### Packages
- llama-cpp-python
- torch
- diffusers
- transformers
- accelerate
- safetensors
- matplotlib
- Pillow
- gradio
- torchvision
- numpy
- opencv-python

### Platform
- Google Colab Drive

## 🚀 Getting Started
### Steps to Run the Project
1. **Download the repository** and open it in Google Colab.

2. **Make a copy** of the three fine tuned Llama models, from the link provided below, in your google drive.\
**fine_tuned_tiny_stories_model**\
https://drive.google.com/drive/folders/1gE-VXTw-joTB9F25CYHkShDzXvYHUXZ4?usp=drive_link \
**llama-2-7b.Q3_K_S.gguf**\
https://drive.google.com/file/d/1KI6DCFuQDJvlNnIvO7jyq9ru8hndoDGm/view?usp=drive_link \
**Copy of InkoloRA.safetensors**\
https://drive.google.com/file/d/1I84d9uqjwNqQm1ENey6A33HMMIu2wyYC/view?usp=drive_link

3. **Run the .py or .ipynb file** in your collab, provided in the repository.

4. **Select a template** from the drop-down menu.

   ![Template Selection](https://github.com/user-attachments/assets/b5b7c251-9a97-46b4-97a6-f9a4b4e8dedf)

5. **Enter the prompt** for which the story is to be generated in the Story Prompt field.

   ![Story Prompt](https://github.com/user-attachments/assets/7f55fd1d-225e-49c4-b50a-8f38b240c89d)

6. **Choose the number of panels** to be generated.

   ![Number of Panels](https://github.com/user-attachments/assets/e4b9bef4-7dc9-4049-b765-4427732993d3)

7. **Select the art style** for the comic images.

   ![Art Style](https://github.com/user-attachments/assets/345398e3-f9cb-4e79-a08e-3e5f2c2603e3)

8. **Click 'Generate Comic'** to bring your story to life!

## 🌈 Example Output
**User Input:** "Write a story about Spiderman fighting thieves."

**AI-Generated Story Sample:**
![Story Panel 1](https://github.com/user-attachments/assets/7079c66c-2598-4f80-9c2c-b3f12835388d)
![Story Panel 2](https://github.com/user-attachments/assets/bd3112bd-5d22-449a-905d-adc467850764)
![Story Panel 3](https://github.com/user-attachments/assets/fef11de3-31da-488b-94d1-ca2de11f4a73)

## 💪 Challenges & Learnings
- **Fine-Tuning Issues:** Adjusting model parameters for improved coherence.
- **Model Integration:** Ensuring seamless communication between LLaMA 2 and Stable Diffusion XL.
- **Style Consistency:** Maintaining uniform character design across panels.

## 🚧 Future Improvements
- **User-Defined Art Styles:** Allowing users to choose from different artistic styles.
- **Enhanced Image Consistency:** Refining techniques for uniformity in character design.
- **Optimized Model Performance:** Further improving fine-tuning strategies for higher accuracy.

## 📝 Conclusion
ComicCrafter AI showcases the potential of AI-driven storytelling, transforming text prompts into structured, visually cohesive comics. This project demonstrates the power of deep learning and generative AI in creative content generation.

## 🙏 Author
Aman Chhimwal\
Shashwat Bhardwaj\
Sana Bansal\
Vaibhavi Sengar\
Akshat Sharma\
Anshika Madan\
Shaurya Bhaskar

### Mentor
Prof. Meghavi Rana


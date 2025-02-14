# Image Generator using ComfyUI & Stable Diffusion

## 📌 Overview
This project utilizes **ComfyUI** and **Stable Diffusion** to generate AI-powered images based on text prompts.  
It provides a powerful yet simple way to generate high-quality images directly from the console.

## 🛠️ Setup & Installation
Follow Below steps to set up the project on your local machine:

1. **Download & Install ComfyUI**
   - Download ComfyUI from the official [GitHub repository](https://github.com/comfyanonymous/ComfyUI).
   - Extract the files and navigate to the `ComfyUI` folder.

2. **Download Stable Diffusion Model**
   - Get a Stable Diffusion `.safetensors` model from [Hugging Face](https://huggingface.co/stabilityai) or another source.
   - Place it inside the `ComfyUI/models/checkpoints/` directory.

3. **Run ComfyUI**
   - Navigate to the ComfyUI directory.
   - Run the following command to start the server:
     ```
     python main.py
     ```
   - Once running, access the UI at:
     ```
     http://127.0.0.1:8188
     ```

## 🚀 Generating Images
1. Open the ComfyUI interface.
2. Enter your desired prompt in the text box.
3. Click the **Generate** button to create an image.
4. The generated images will be saved in the output directory.

## ⚒️ Workflow 
  ![Screenshot 2025-02-13 212635](https://github.com/user-attachments/assets/c05ae925-3e15-4a63-b711-ace0e462e64e)

## 🖼️ Sample Prompts
Prompt 1: “A car with neon lights driving on a rainy road in a vibrant cyberpunk city at night.”
![image](https://github.com/user-attachments/assets/2c8c9ef7-29cb-49c8-b604-eba3c37b553b)
                

Prompt 2: “A breathtaking fantasy landscape with floating islands, glowing waterfalls, mystical creatures, and a vibrant, colorful sky.”
![image](https://github.com/user-attachments/assets/9a540e24-9a16-4a9b-9e57-375726a53a4a)
                  

Prompt 3: “A serene lake surrounded by green mountains during sunrise, with mist floating on the water.”
![image](https://github.com/user-attachments/assets/11b5646b-549e-48bb-91d2-d01f2ad6d9ee)
                  

Prompt 4: “Epic battle warrior in futuristic armor, wielding a massive sword, standing on a battlefield with fire and smoke.
![image](https://github.com/user-attachments/assets/801a797f-664b-4da2-984a-e745b0c14fbd)
              

Prompt 5: “Futuristic cyberpunk city at night, neon lights, towering skyscrapers, flying cars, bustling streets, holograms, and rain.”
![image](https://github.com/user-attachments/assets/eac13694-da34-4051-9baa-1808d00a3256)


## 📌 Features
- Text-to-Image generation using Stable Diffusion.
- Easy setup with ComfyUI.
- Customizable model support.
- Works locally without an internet connection.

---
### 🔗 Useful Links
- [ComfyUI GitHub](https://github.com/comfyanonymous/ComfyUI)
- [Stable Diffusion Models](https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)

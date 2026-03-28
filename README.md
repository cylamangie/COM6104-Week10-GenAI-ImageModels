# COM6104-Week10-GenAI-ImageModels
COM6104 Week 10 lab — Exploring generative AI image models (Qwen Image, Stable Diffusion 3.5, FLUX.2) with HuggingFace Diffusers. Includes setup, sample prompts, and outputs.

# Generative AI Image Models – Week 10

## 📌 Overview
This project explores **three generative AI image models** using HuggingFace Diffusers:
- **Qwen Image (DiT-based)**
- **Stable Diffusion 3.5 Medium**
- **FLUX.2 Klein 4B**

Each model is implemented in its own notebook, with a sample prompt generating an image of *“a cat holding a sign that says hello world.”*

> 📝 **Note**: This is the **tenth lab assignment** for **COM6104 – Topics in Data Science and Artificial Intelligence**.

---

## 🎯 Motivation
Generative AI models can create high-quality images from text prompts.  
This lab highlights:
- How to load and configure large diffusion models.  
- How to manage GPU/VRAM requirements with offloading.  
- How to generate and display images with HuggingFace Diffusers.  
- How to experiment with creative prompts.

---

## ⚙️ Files
- **`qwen.ipynb`** → Qwen Image (DiT-based, 4-bit).  
- **`sd.ipynb`** → Stable Diffusion 3.5 Medium.  
- **`flux.ipynb`** → FLUX.2 Klein 4B.  

---

## 📊 Key Steps
1. **Install dependencies**: `diffusers`, `torch`, `transformers`, `huggingface-hub`.  
2. **Load models**:  
   - Qwen Image (DiT-based, 4-bit).  
   - Stable Diffusion 3.5 Medium.  
   - FLUX.2 Klein 4B.  
3. **Run prompts**:  
   - Example: `"A cat holding a sign that says hello world"`.  
4. **Display or save images**: `display(image)` or `image.save("example.png")`.  

---

## 🚀 How to Run
Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 📚 Course Context
Completed as part of COM6104 – Topics in Data Science and Artificial Intelligence at The Hang Seng University of Hong Kong.

---

## 💡 Reflection
This lab helped me compare Qwen Image, Stable Diffusion, and FLUX pipelines.
I learned how to handle GPU memory constraints, configure offloading, and generate images from text prompts.
Due to time limits, I only generated one test image (“cat holding hello world”), but I would like to explore more creative prompts such as:

- Victorian, Steampunk, Robotic Pet
- Underwater Tea Ceremony, Jellyfish, Noh theatre mask
- Crowd Fight, North Pole, Hello Kitty, Ironman

---

## 📚 Acknowledgements
Parts of this code were adapted from COM6104 lab materials and HuggingFace documentation.
This repository is licensed under the MIT License, which permits reuse and modification with proper attribution.



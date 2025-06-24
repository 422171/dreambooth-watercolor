# 🎨 DreamBooth + LoRA Watercolor Generation

> *"I am Loki of Asgard, and I am burdened with glorious purpose."*  
> This project is a creative tribute to **Tom Hiddleston** — the charismatic actor best known for his iconic role as **Loki** in the Marvel Cinematic Universe. Known for his charm, wit, and elegance, Hiddleston's distinct features were the perfect candidate for a small-scale DreamBooth + LoRA fine-tuning experiment.

This project showcases how to personalize image generation using **Stable Diffusion v1.5**, fine-tuned with **LoRA** and **DreamBooth** on a small dataset of Tom Hiddleston. The result: artistic watercolor-style images of the actor imagined in different creative scenes.

## 🧠 Project Overview

- Used 4 facial images of Tom Hiddleston from the [sandeshrajx/tom-hiddleston](https://huggingface.co/datasets/sandeshrajx/tom-hiddleston) dataset.
- Fine-tuned using LoRA and Hugging Face's DreamBooth training script.
- Generated watercolor-styled portraits using prompt engineering.
- Imagined scenes:
  - 🚀 In a spacesuit  
  - 🐎 Riding a horse  
  - 🏏 Playing cricket  

## 📁 What’s Included

- **Notebook**: Complete Colab notebook for training and generating images  
- **Training Data**: Four images used to fine-tune the model  
- **Outputs**: Sample results from inference  
- **Video**: Explanation of the project, code, and results

## ▶️ Quick Access

- **📓 Colab Notebook**: [Open in Colab](https://colab.research.google.com/drive/1jEG-NApvfJs-kPlZYGOlTwUq4lToLDBr?usp=sharing)  
- **📹 Video Walkthrough**: [Watch here](https://drive.google.com/file/d/1DoKBVMo2pKOz7HSoaBjz-iyAnitqXNyZ/view?usp=sharing)

You can copy the notebook and run each cell to train your own version or generate customized outputs.

## 📌 Notes

- The model was trained for **500 steps** with basic hyperparameters.
- Prompt used for personalization: *"a photo of sks person"*.
- Style and scenario were controlled via inference prompts.
- Based on Hugging Face’s official `diffusers` DreamBooth + LoRA script.

## 🧭 Try It Yourself

You can:
- Clone or fork this repository
- Use the included Colab notebook to retrain or generate your own images
- Replace training images with any subject of your choice

## 📝 Future Ideas

- Expand training data for improved generalization
- Experiment with other art styles (oil, pencil sketch, pixel art)
- Deploy as a lightweight web app using Gradio or Streamlit

## 📄 License & Credits

- This project is for **educational/demo purposes only**.
- Based on [diffusers](https://github.com/huggingface/diffusers) from Hugging Face.
- Training data: [sandeshrajx/tom-hiddleston](https://huggingface.co/datasets/sandeshrajx/tom-hiddleston)

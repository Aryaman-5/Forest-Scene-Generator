# 🌲 AI Forest Scene Generator

Generate detailed, photorealistic forest images from text prompts using Stable Diffusion XL and a specialized Forest LoRA!  
Perfect for creative projects, education, and as cover images for steganography.

---

## 🚀 Features

- **Text-to-Image Generation:** Create unique forest scenes from your own prompts or random generation.
- **Prompt Engineering:** Enhances prompts with curated forest textures, details, and styles.
- **Negative Prompting:** Exclude unwanted elements from generated images.
- **Customizable Parameters:** Control diffusion steps, guidance scale, and random seed.
- **Real-Time Progress:** See generation status and detailed metrics.
- **Gradio Web Interface:** Easy-to-use, interactive UI.
- **Steganography Ready:** Use generated images as covers for data hiding.


---

## 🛠️ Tech Stack

- **Stable Diffusion XL** (via Hugging Face Diffusers)
- **Forest LoRA** for realistic forest imagery
- **Gradio** for the web interface
- **PyTorch**, **NumPy**, **Pillow**, **OpenCV**, **pyzbar**

---

## 💡 Use Cases

- **Creative Content:** Art, backgrounds, concept design
- **Education & Research:** Nature visualization, ecological studies
- **Steganography:** Cover images for secure data hiding

---

## 🔧 Getting Started

### 1. Clone the repository

### 2. Install dependencies

pip install -r requirements.txt

### 3. Set your Hugging Face token

- Edit the script and replace `HF_TOKEN = "..."` with your [Hugging Face access token](https://huggingface.co/settings/tokens).

### 4. Run the app
python your_script.py
- The Gradio interface will open in your browser.

---

## 📷 Example

| Prompt | Output |
|--------|--------|
| `Enchanted forest with a small creek` | ![image](https://github.com/user-attachments/assets/9e6451ff-ac7a-4676-a8f2-3a3ae349e5c1)

---

## 🤝 Credits

- [Stable Diffusion XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
- [Forest LoRA by phoenix007654](https://huggingface.co/phoenix007654/forest_updated_LoRA)
- [Gradio](https://gradio.app/)
- [Hugging Face Diffusers](https://huggingface.co/docs/diffusers/index)

---

## 📜 License

This project is for educational and research purposes. See [LICENSE](LICENSE) for details.

---

*Created by [Aryan Mollick], 2025*

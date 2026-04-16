# 👗 Zyra - AI Smart Mirror for Personalized Outfit Styling

An AI-powered fashion assistant that analyzes your outfit using computer vision and recommends better styles based on occasion, skin tone, and cultural context (Indian + Western). It can even generate realistic outfit visualizations.
> 🎙️ Voice-enabled smart assistant with wake word “Zyra” and sleep command “Goodbye”

---

## ✨ Features

* 🧍‍♂️ **Pose Detection (YOLOv8)**
  Detects body keypoints to understand visible regions (face, upper, lower, full body)

* 🎨 **Outfit Analysis (Multimodal AI)**
  Extracts:

  * Skin tone
  * Gender
  * Clothing type (Indian + Western)
  * Fabric, pattern, accessories

* 👕 **Smart Outfit Recommendations**
  Suggests outfits based on:

  * Occasion (weddings, festivals, casual, etc.)
  * Skin tone compatibility
  * Cultural styling rules

* 🔍 **Outfit Rating System**
  Rates your current outfit (0–10) with actionable feedback

* 🖼️ **AI Outfit Visualization**
  Generates photorealistic outfit images using generative AI

* 🌐 **Web App Support**
  Flask backend with live camera + ngrok deployment

---

## 🎙️ Voice-Controlled Smart Interface

Zyra supports a fully voice-driven experience for seamless interaction.

- 🗣️ **Wake Word Activation:** Say **“Zyra”** to activate the assistant  
- 🎧 **Hands-Free Control:** Navigate and interact without using keyboard or mouse  
- ⚡ **Real-Time Responses:** Get instant styling feedback through voice commands  
- 🌙 **Sleep Command:** Say **“Goodbye”** to put the assistant back to sleep  
> Designed to simulate a real smart mirror — just say “Zyra” and start interacting.

## 🧠 Tech Stack

* **Computer Vision:** YOLOv8 (Ultralytics)
* **Backend:** Flask
* **LLMs:** OpenRouter, Gemini
* **Image Generation:** fal.ai
* **Other:** OpenCV, PIL, NumPy

---

## 📂 Project Structure

> The entire pipeline (detection, analysis, recommendation, and UI) is implemented within a single interactive notebook for easy experimentation and demo.
---


## 🚀 Run the Project

This project is designed to run directly in Google Colab — no local setup required.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-tOgPkUKPL2_Hu1P9Gv_Qadf8jyOD6gH?usp=sharing)

> The Flask app is automatically launched within the notebook using ngrok for public access.

---

### ⚙️ Steps

1. Open the notebook in Colab  
2. Paste your API keys in the provided cell  
3. Run all cells in order  
4. Start interacting with Zyra 🎙️  

---

### 🔗 Ngrok Setup (for Web Interface)

If you want to use the live camera web interface, set your ngrok auth token:
Create an ngrok account and paste your token when prompted.

from pyngrok import ngrok
ngrok.set_auth_token("your_ngrok_token_here")

## 🧪 Usage Modes

* **Basic Mode:** Get a full outfit recommendation
* **Matching Mode:** Rate your current outfit
* **Suggestion Mode:** Complete missing outfit parts

---

## 📸 Example Use Cases

* “What should I wear for a wedding?”
* “Does this outfit match?”
* “Suggest pants for this shirt”
* “What suits my skin tone?”

---

## ⚠️ Notes

* API keys are required for full functionality
* Works best with clear images
* Designed for experimentation and research purposes

---

## 📌 Future Improvements

* Mobile app version
* Real-time outfit tracking
* Personalized wardrobe memory
* E-commerce integration

---


## 👤 Author

**Bharath**
Engineering Student | AI + Computer Vision Enthusiast

---

## 📄 License

This project is open-source and available under the MIT License.

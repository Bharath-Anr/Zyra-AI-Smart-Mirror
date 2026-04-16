# 👗 Zyra - AI Smart Mirror for Personalized Outfit Styling — Indian & Western Outfit Intelligence

An AI-powered fashion assistant that analyzes your outfit using computer vision and recommends better styles based on occasion, skin tone, and cultural context (Indian + Western). It can even generate realistic outfit visualizations.
> 🎙️ Voice-enabled smart assistant with wake word “Zyra” and sleep command “Goodbye”
---

## 🚀 Demo

👉 Open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-tOgPkUKPL2_Hu1P9Gv_Qadf8jyOD6gH?usp=sharing)

---

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
> Designed to simulate a real smart mirror experience — just walk up and speak.

## 🧠 Tech Stack

* **Computer Vision:** YOLOv8 (Ultralytics)
* **Backend:** Flask
* **LLMs:** OpenRouter, Gemini
* **Image Generation:** fal.ai
* **Other:** OpenCV, PIL, NumPy

---

## 📂 Project Structure

```
ai-fashion-stylist/
│── app.py
│── requirements.txt
│── README.md
│── utils/
│   ├── detection.py
│   ├── analysis.py
│   ├── recommendation.py
│   ├── image_generation.py
```

---

## ⚙️ Setup & Run

### 1. Clone the repo

```
git clone https://github.com/YOUR_USERNAME/ai-fashion-stylist.git
cd ai-fashion-stylist
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Set API keys

Create a `.env` file:

```
OPENROUTER_API_KEY=your_key_here
GEMINI_API_KEY=your_key_here
FAL_API_KEY=your_key_here
```




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
* Works best with clear full-body or upper-body images
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

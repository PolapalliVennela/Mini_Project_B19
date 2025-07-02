# 🧏‍♀️ Telugu/English Speech to Indian Sign Language (ISL) Converter

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Open Source](https://img.shields.io/badge/Open--Source-Yes-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-informational)
![License](https://img.shields.io/badge/License-MIT-yellow)

This project is a Python-based system that converts spoken **Telugu** or **English** audio input into **Indian Sign Language (ISL)** using a GUI. It aims to assist hearing-impaired individuals by translating spoken language into visual ISL representations (images or videos).

---

## 📽️ Demo Video

🎬 **[Click here to watch the demo](https://drive.google.com/file/d/18dZlZ3wVCFXtQ3FmpiGTppyU1ZKdfgl5/view?usp=drive_link)** 

---

## 🌟 Features

- 🎙️ Accepts Telugu or English **audio/speech input**
- 🌐 Converts recognized text to **Indian Sign Language**
- 🧠 Uses **Google Speech Recognition** and **Translation APIs**
- 🖼️ Displays ISL as **images or gesture videos**
- 🖥️ Easy-to-use **Graphical User Interface** (Tkinter or Flask)

---

## 🛠️ Tech Stack

| Component        | Technology Used                          |
|------------------|-------------------------------------------|
| GUI              | Python (Tkinter / Flask)                 |
| Speech Recognition | Google Speech Recognition API           |
| Translation      | `googletrans` or HuggingFace Transformers |
| ISL Mapping      | Custom image/video dataset of ISL signs  |
| Media Display    | OpenCV / Pygame / PIL                    |

---

## 📁 Folder Structure

```
audio-to-ISL-converter/
├── app.py
├── gui/
│   └── interface.py
├── assets/
│   ├── isl_images/
│   └── isl_videos/
├── audio/
├── translations/
├── video_demo.mp4
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/audio-to-ISL-converter.git
cd audio-to-ISL-converter
```

### Step 2: Install required packages

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not available, install manually:
```bash
pip install googletrans==4.0.0-rc1 SpeechRecognition pygame opencv-python pillow nltk
```

### Step 3: Run the application

```bash
python app.py
```

---

## ✅ Example Use Case

1. Speak a sentence in **Telugu** or **English**.
2. The application captures the speech and converts it to text.
3. The translated text is mapped to **ISL signs**.
4. Corresponding sign language gestures (images/videos) are displayed in the GUI.

---

## 🚧 Future Improvements

- Real-time ISL avatar instead of static images/videos
- Add Hindi and other Indian language support
- Integration with webcam for real-time interaction
- Mobile version (Android/iOS) using Kivy or React Native

---

## 🤝 Contributing

Contributions are welcome! Feel free to raise issues or submit pull requests.

```bash
# Fork this repo
# Make changes
# Push and open a Pull Request!
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Varsha Sri Palakurthi**  
📫 [GitHub](https://github.com/varshasric4) | [LinkedIn](https://linkedin.com/in/varshasrip)

---

⭐ If you find this project useful, don’t forget to give it a **star**!

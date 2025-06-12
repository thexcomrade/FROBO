[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=FROBO,+The+Friendly+Robot;Emotionally+Responsive+%7C+Budget+Smart;Frog-Inspired+Design&font=Fira+Code&width=1000)](https://git.io/typing-svg)

# 🤖 Frobo: The Affordable Emotional Desktop Companion

🚀 Just built a $90 emotional robot that reacts to pets & shakes!

**Frobo** is a budget-friendly emotional AI companion robot built from scratch, inspired by expensive alternatives like Eilik. Frobo is designed to express human-like emotions, respond to tactile interaction, detect table vibrations, and build personality over time — all while being accessible and open-source.

---

## 💡 Origin of the Idea

The idea for Frobo was sparked by the high market price (~₹20,000 INR) of emotional robots like FASTRON Eilik. I asked myself — *why can't I create a smarter and more affordable version on my own?*  
That challenge turned into **Frobo**, a lovable and customizable robot created for under **₹8,000 INR (~$90)**!

---

## 🔧 Features

- Expressive OLED-based face with multiple moods
- Touch & tap interaction (head, body, table shake)
- Personality that evolves over time
- Vibration sensor & fear of heights detection
- Sound & movement interaction (via microphone + servo)
- Custom-built 3D-printed frog-inspired design 🐸
- Rechargeable Li-ion battery with USB-C charging
- Modular and upgradable design (open-source hardware/software)

---

## 📦 What's Inside?

- Microcontroller (Arduino Nano / ESP32)
- OLED display
- Servo motors (arms/head movement)
- Vibration sensor (shock detection)
- Touch sensors
- Rechargeable 3.7V 1000mAh Li-ion battery
- Custom 3D-printed shell (PLA)
- Handcrafted emotion animations & logic

---

## 📁 Project Folder Structure

1. Frobo Robot (Hardware + Firmware)
```plaintext
frobo-robot/
│
├── firmware/                  # Arduino or ESP32 code
│   ├── frobo_main.ino
│   ├── emotions.h             # OLED facial expressions
│   └── sensors.ino            # Touch, sound, vibration response
│
├── hardware/
│   ├── circuit-diagram.png
│   ├── 3D_model_frobo.stl
│   └── pcb_layout.fzz         # Optional: Fritzing PCB design
│
├── assets/
│   ├── frobo_logo.png
│   └── frobo_photos/
│
├── docs/
│   └── Frobo_Technical_Doc.pdf
│
├── LICENSE
└── README.md
```

2. Frobo App (Mobile or Desktop Companion)
```plaintext
frobo-app/
│
├── android-app/               # If Android app (Kotlin/Flutter)
│   ├── lib/
│   ├── assets/
│   └── main.dart / MainActivity.kt
│
├── desktop-app/               # If Python/React Electron App
│   ├── ui/
│   ├── frobo_control.py       # PySerial / Bluetooth controller
│   └── config.json            # Emotion profiles or settings
│
├── assets/
│   ├── app_icons/
│   └── qr_links/
│
├── docs/
│   └── App_User_Guide.pdf
│
└── README.md
```
---

## 📢 License & Copyright

**@thexcomrade**] (https://github.com/thexcomrade)
> 📁 All designs, source code, and media are original works.  
> ❗ **No reproduction, reselling, or commercial use allowed without explicit permission.**

---

## 🙌 Support Frobo

If you love Frobo and want to support its development, consider donating to help make affordable robotics accessible to everyone.

<img src="assets/gpay_qr.png" alt="Donate via GPay" width="300" />

📲 Scan this QR using any UPI-enabled app (Google Pay, PhonePe, Paytm, etc.)

[![Download QR](https://img.shields.io/badge/Download-QR_Code-green?style=for-the-badge&logo=googlepay)](assets/gpay_qr.png)





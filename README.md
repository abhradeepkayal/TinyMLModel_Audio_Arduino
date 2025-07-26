# 🆘 TinyML Keyword Spotting Model – "HELP" Detection  

This repository contains a **TinyML audio classification model** trained on the keyword **"HELP"** using [Edge Impulse](https://edgeimpulse.com/).  
The model is designed to run on microcontrollers (Arduino, ESP32, etc.) for **real-time voice-triggered emergency detection**.  

---

## 📂 Folder Structure  
``` audio_inferencing/
 ├─ examples/         # Example Arduino sketches
 ├─ src/              # Model source files
 └─ library.properties
```

---

## 🚀 How to Use  

### 1️⃣ Add the Library to Arduino IDE  
- Download this repository as a `.zip`.  
- Open **Arduino IDE** → `Sketch → Include Library → Add .ZIP Library`.  
- Select the downloaded `.zip` file.  

### 2️⃣ Run the Example  
- Go to `File → Examples → audio_inferencing`.  
- Open `audio_inferencing.ino`.  

### 3️⃣ Select Your Board  
- Go to `Tools → Board` → Choose your MCU (Arduino Nano 33 BLE Sense, ESP32, etc.).  
- Go to `Tools → Port` → Select the correct COM port.  

### 4️⃣ Upload the Code  
- Click **Upload**.  
- The board will continuously listen for the keyword **"HELP"**.  
- On detection, you can trigger alerts (buzzer, LED, SOS signal, etc.).  

---

## 🛠 Requirements  
✅ Arduino IDE  
✅ A supported MCU (Arduino Nano 33 BLE Sense, ESP32, etc.)  
✅ Microphone-enabled board  

---

## 🔗 Edge Impulse Project  
This model was trained on the keyword **"HELP"** using [Edge Impulse](https://edgeimpulse.com/).  

---

## ✨ Features  
✅ Real-time keyword spotting (**"HELP"**)  
✅ Lightweight & optimized for MCUs  
✅ Can be integrated with SOS systems  


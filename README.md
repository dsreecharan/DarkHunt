# 🕵️ DarkHunt – AR QR Poster

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Tech](https://img.shields.io/badge/AR.js-AFrame-orange.svg)  
![Platform](https://img.shields.io/badge/Platform-WebAR-green.svg)

**DarkHunt** is an **AR-powered QR code project** that brings posters to life.  
Scanning the QR opens the phone’s camera in the browser, detects a marker, and displays a **3D poster in augmented reality**.  
Tapping the poster redirects users to a **Google Form** (ideal for surveys, event registrations, or campaigns).

---

## ✨ Features
- 📱 **No App Required** → Works directly in the browser
- 🖼️ **3D Poster Rendering** → Loads `.glb` model in AR  
- 🔗 **Clickable Poster** → Redirects to a Google Form  
- 🌐 **Cross-Platform** → Works on Android Chrome & iOS Safari  

---

## 🛠️ Tech Stack
- [A-Frame](https://aframe.io/) → 3D/VR rendering  
- [AR.js](https://github.com/AR-js-org/AR.js/) → WebAR support  
- HTML + JavaScript → Core setup  
- [Netlify](https://www.netlify.com/) / GitHub Pages → Free hosting  
- QR Code Generator → User entry point  

---

## 📂 Project Structure
```
DarkHunt/
├── index.html     # Main AR page
├── poster.glb     # 3D poster model (to be added by user)
└── README.md      # Project documentation
```

---

## ⚙️ Setup & Deployment
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/DarkHunt.git
   cd DarkHunt
   ```

2. **Add your 3D poster model**
   - Place `poster.glb` inside the project folder.  

3. **Update Google Form link**
   - Open `index.html`  
   - Replace the placeholder form URL with your own.  

4. **Deploy the project**
   - Recommended: [Netlify](https://www.netlify.com/) (drag & drop)  
   - Alternative: GitHub Pages  

5. **Generate a QR code**
   - Point it to your hosted URL.  

6. **Share the QR code**
   - Print or distribute it → users scan and launch DarkHunt instantly!  

---

## 🎯 Usage
1. Scan the QR code → Browser requests camera permission.
2. A **3D poster** appears anchored on the marker.  
3. Tap the poster → Opens your **Google Form** in a new tab.  

---

## 🔮 Future Improvements 
- ✅ Animated & interactive posters  
- ✅ Multiple posters → different form links  
- ✅ Analytics for scans & submissions  

---

## 📸 Demo Flow
```
QR → Camera → AR Poster → Google Form
```

DarkHunt makes **event promotion, campaigns, and surveys** more **interactive, fun, and engaging 🎯**

---

## 📄 License
This project is licensed under the **MIT License** – feel free to use and adapt.

---

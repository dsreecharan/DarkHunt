# 🕵️ DarkHunt – AR QR Poster

**DarkHunt** is an AR-powered QR project that brings posters to life. Scanning the QR opens the phone camera in the browser, shows a 3D poster in AR, and redirects users to a Google Form when tapped. Perfect for events, surveys, and interactive campaigns.

---

## 🚀 Features
- Scan QR → launch AR in the browser (no app required)  
- Detects a **marker** (Hiro marker)  
- Displays a **3D poster/model** in AR  
- Tap the poster → redirects to a **Google Form**  
- Works on most modern smartphones (Chrome on Android & Safari on iOS)  

---

## 🛠️ Tech Stack
- [A-Frame](https://aframe.io/) – 3D/VR rendering framework  
- [AR.js](https://github.com/AR-js-org/AR.js/) – Lightweight WebAR library  
- **HTML + JavaScript** – Project setup  
- [Netlify](https://app.netlify.com/drop) – Free hosting & deployment  
- QR Code Generator – Shareable entry point  

---

## 📂 Project Structure
DarkHunt/
├── index.html # Main AR page
├── poster.glb # 3D poster model (to be added by user)
└── README.md # Project documentation

---

## ⚙️ Setup & Deployment
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/DarkHunt.git
   cd DarkHunt
Add your 3D poster model (poster.glb) into the project folder

Edit index.html → replace the sample model path and update the Google Form link

Deploy on Netlify Drop (drag & drop the project folder)

Generate a QR code pointing to your hosted URL

Share or print the QR → users can scan and launch DarkHunt instantly

🎯 Usage
Scan the QR code → browser opens with camera

Point camera at the Hiro marker (download marker)

A 3D poster appears anchored on the marker

Tap the poster → opens your Google Form in a new tab

💻 Sample Code (index.html)
html
Copy code
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.rawgit.com/jeromeetienne/AR.js/2.0.8/aframe/build/aframe-ar.js"></script>
  </head>
  <body style="margin:0; overflow:hidden;">
    <a-scene embedded arjs>
      
      <!-- Replace with your poster.glb file -->
      <a-entity gltf-model="url(poster.glb)" 
                position="0 0 -3" 
                scale="0.5 0.5 0.5"
                onclick="window.open('https://forms.gle/yourGoogleFormLink','_blank');">
      </a-entity>

      <a-marker-camera preset="hiro"></a-marker-camera>
    </a-scene>
  </body>
</html>
🔮 Future Improvements
Markerless AR (no Hiro marker needed)

Animated / interactive posters

Multiple posters linked to different Google Forms

Analytics dashboard for scan + form tracking

📸 Demo Flow
QR → Camera → AR Poster → Google Form

DarkHunt makes campaigns, events, and promotions interactive, engaging, and immersive 🎯

pgsql
Copy code

---

✅ You can literally copy-paste this into a file named `README.md` in your DarkHunt repo.  

Do you also want me to give you a **ready-to-copy `index.html` + folder structure** so you can make the

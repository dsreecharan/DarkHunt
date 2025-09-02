🕵️ DarkHunt – AR QR Poster

DarkHunt is an AR-powered QR code project. When a user scans a QR code, their phone’s camera opens in the browser, detects a marker, and displays a 3D poster in augmented reality. Tapping the poster redirects them to a Google Form (useful for surveys, event registrations, or campaigns).

🚀 Features

Scan QR → launch AR in the browser (no app required).

Detects a marker (Hiro marker).

Displays a 3D poster/model in AR.

Tap the 3D poster → redirects to a Google Form.

Works on most modern smartphones (Android Chrome & iOS Safari).

🛠️ Tech Stack

A-Frame
→ 3D/VR rendering framework.

AR.js
→ Lightweight WebAR library.

HTML + JavaScript → Base project setup.

Netlify → Free & easy hosting.

QR Code Generator → Shareable entry point.

📂 Project Structure
DarkHunt/
├── index.html # Main AR page
├── poster.glb # 3D poster model (to be added by user)
└── README.md # Project documentation

⚙️ Setup & Deployment

Clone the repository:

git clone https://github.com/yourusername/DarkHunt.git
cd DarkHunt

Add your 3D model (poster.glb) into the project folder.

Update the Google Form link inside index.html.

Deploy on Netlify
or GitHub Pages.

Generate a QR code pointing to your hosted URL.

Share or print the QR code → users can scan and launch DarkHunt.

🎯 Usage

Scan the QR code → browser opens with camera.

Point camera at the Hiro marker (download marker
).

A 3D poster appears anchored on the marker.

Tap the poster → opens Google Form in new tab.

🔮 Future Improvements

Markerless AR support.

Interactive posters (animations, hover effects).

Multiple posters linked to different forms.

Analytics for QR scans and form submissions.

📸 Demo Flow

QR → Camera → AR Poster → Google Form.

DarkHunt makes event promotion and campaigns interactive, fun, and engaging 🎯.

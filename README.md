# 🚗 PORSCHE-XR

PORSCHE-XR is a web-based Extended Reality (XR) project built using React that allows users to explore Porsche car models in an interactive 3D and AR-ready environment directly from the browser. The application supports GLB and USDZ models, making it compatible with mobile AR viewers such as iOS Quick Look and Android Scene Viewer. The project is optimized for performance, mobile responsiveness, and modern browsers, and is deployed as a static site on Vercel.

The application is built with React using Create React App and uses JavaScript, HTML5, and CSS3 for the frontend. AR and 3D assets are handled using GLB and USDZ formats, which are hosted in the public directory to ensure direct access by AR viewers. The project follows a clean and modular structure to make development, maintenance, and deployment simple.

### ✨ Features
- Interactive 3D Porsche car visualization
- AR-ready models with GLB and USDZ support
- Web-based XR experience without app installation
- Mobile-friendly and optimized for AR devices
- Fast and optimized production build
- Static deployment on Vercel

### 🛠 Tech Stack
React (Create React App), JavaScript, HTML5, CSS3, GLB/USDZ 3D models, npm, and Vercel for deployment.

### 📂 Project Structure
```bash
PORSCHE-XR/
├── public/
│   ├── models/        # AR 3D models (.glb, .usdz)
│   └── index.html
├── src/
│   ├── components/
│   ├── App.js
│   └── index.js
├── vercel.json        # MIME headers for AR models
├── package.json
├── README.md
└── .gitignore


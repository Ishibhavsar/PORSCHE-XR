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

🚀 Getting Started
Clone the repository, install dependencies, and run the project locally using the following commands:
git clone https://github.com/Ishibhavsar/PORSCHE-XR.git
cd PORSCHE-XR
npm install
npm start
The application will be available at http://localhost:3000

📦 Production Build
To create an optimized production build, run:
npm run build
The build output will be generated in the build/ directory and is ready for deployment.

🌐 Deployment
This project is deployed as a static site on Vercel. You can deploy it using Git integration by importing the repository into Vercel, or deploy manually using the Vercel CLI after creating a production build.
npm run build
npx vercel --prod

⚙️ AR Hosting Notes
All AR assets are stored in the /public/models directory. Proper MIME types are required for AR compatibility, with .glb served as model/gltf-binary and .usdz served as model/vnd.usdz+zip. These headers are configured using vercel.json to ensure compatibility with mobile AR viewers.

📱 Usage Notes
For best results, access the application over HTTPS, ensure QR codes point to the deployed site instead of localhost, and use a mobile device to experience AR features.

📚 Learn More
React: https://react.dev
Create React App: https://create-react-app.dev
Vercel: https://vercel.com/docs

👤 Author
Ishi Bhavsar
GitHub: https://github.com/Ishibhavsar

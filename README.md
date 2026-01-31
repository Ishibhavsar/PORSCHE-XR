# 🚗 PORSCHE-XR

PORSCHE-XR is a web-based **Extended Reality (XR)** application built with **React (Create React App)** that enables users to explore **Porsche car models** in an interactive **3D and AR-ready environment** directly from the browser. The project supports **GLB and USDZ** formats, making it compatible with mobile AR viewers such as **iOS Quick Look** and **Android Scene Viewer**. It is optimized for performance, mobile responsiveness, and modern browsers, and is deployed as a static site on **Vercel**.

---

## ✨ Features

- Interactive 3D Porsche car visualization  
- AR-ready models (GLB & USDZ support)  
- Web-based XR experience (no app installation required)  
- Mobile-friendly and optimized for AR devices  
- Fast and optimized production build  
- Static deployment on Vercel  

---

## 🛠 Tech Stack

React (Create React App), JavaScript, HTML5, CSS3, GLB/USDZ 3D models, npm, and Vercel for deployment.

---

## 📁 Project Structure

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
````

---

## 🚀 Getting Started

Clone the repository, install dependencies, and run the project locally using the following commands:

```bash
git clone https://github.com/Ishibhavsar/PORSCHE-XR.git
cd PORSCHE-XR
npm install
npm start
```

The application will be available at:
**[http://localhost:3000](http://localhost:3000)**

---

## 📦 Production Build

To create an optimized production build, run:

```bash
npm run build
```

The build output will be generated in the `build/` directory and is ready for deployment.

---

## 🌐 Deployment

This project is deployed as a static site on **Vercel**. You can deploy it using Git integration by importing the repository into Vercel, or deploy manually using the Vercel CLI after creating a production build.

```bash
npm run build
npx vercel --prod
```

---

## ⚙️ AR Hosting Notes

All AR assets are stored in the `/public/models` directory. Proper MIME types are required for AR compatibility:

* `.glb` → `model/gltf-binary`
* `.usdz` → `model/vnd.usdz+zip`

These headers are configured using `vercel.json` to ensure compatibility with mobile AR viewers.

---

## 📱 Usage Notes

* Always access the application over **HTTPS** for AR functionality
* Ensure QR codes point to the deployed site (not `localhost`)
* For the best experience, use a mobile device

---

## 📚 Learn More

* React: [https://react.dev](https://react.dev)
* Create React App: [https://create-react-app.dev](https://create-react-app.dev)
* Vercel: [https://vercel.com/docs](https://vercel.com/docs)

---

## 👤 Author

**Ishi Bhavsar**
GitHub: [https://github.com/Ishibhavsar](https://github.com/Ishibhavsar)

```
- **No broken formatting**
- **GitHub-safe**
- **Portfolio-ready**

If you want badges, screenshots, or a live demo link added next, I’ve got you 👌
```

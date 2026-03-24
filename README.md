# Realtime Whiteboard

A collaborative **Realtime Whiteboard** built using **HTML, CSS, JavaScript, Node.js, and Socket.io**.  
Multiple users can draw, erase, add sticky notes, upload images, and collaborate in real time with undo/redo functionality.  

---

##  Features

- 🎨 **Pen Tool**
  - Choose from multiple **colors**  
  - Adjustable **stroke sizes**  

- 🧽 **Eraser Tool**
  - Erase drawings with different eraser sizes  

- 🖼️ **Image Upload**
  - Upload and place images onto the canvas  

- 📝 **Sticky Notes**
  - Add draggable sticky notes on the board  
  - Edit and move them around for brainstorming  

- 🔄 **Undo & Redo**
  - Step backward or forward through drawing history  

- 🧹 **Clear Canvas**
  - Wipe the entire canvas for everyone  

- ⬇️ **Download Canvas**
  - Save your whiteboard as an image file  

- 👥 **Realtime Collaboration**
  - Every action (drawing, notes, images) is synced across all connected users instantly  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (Vanilla)  
- **Backend**: Node.js with Express  
- **Realtime Communication**: Socket.io  

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Vasisth05/realtime-whiteboard.git
cd realtime-whiteboard
npm install
node express.js
```
Open browser and visit
http://localhost:3000

## 🚀 Deployment

This project is configured for deployment on **Render.com**.

**To Deploy:**
1. Visit [Render.com](https://render.com)
2. Sign in with GitHub
3. Create a new **Web Service**
4. Select this repository (`realtime-whiteboard`)
5. Render will automatically use the `render.yaml` configuration
6. Click **Create Web Service** and wait for deployment

The app can now be deployed on Railway, which is working for this project. Use the instructions below and set the service start command to `node express.js`.

---

## 🚆 Railway Deployment (Recommended)

1. Go to https://railway.app and log in with GitHub.
2. Click **New Project**.
3. Select **Deploy from GitHub repo**.
4. Choose `Vasisth05/realtime-whiteboard`.
5. In service settings, set:
   - Build command: `npm install`
   - Start command: `node express.js`
6. Add environment variable if needed: `PORT` is set automatically by Railway.
7. Deploy and wait.
8. The live URL should be shown on your Railway project page (e.g. `https://your-app.up.railway.app`).

## 🔗 Links

- **GitHub Repo:** https://github.com/Vasisth05/realtime-whiteboard
- **Developer:** https://github.com/Vasisth05

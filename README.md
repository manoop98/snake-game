# 🐍 Nokia Snake Game (Nginx Deployment)

A **classic Nokia-style Snake game** built using **HTML5, CSS, and JavaScript**, designed with a retro interface and optimized for deployment as a **lightweight static web application using Nginx**.

---

## 🚀 Overview

This project demonstrates how a simple frontend application can be efficiently served using **Nginx**, making it ideal for:

* Static website hosting
* DevOps practice projects
* Lightweight deployments
* Container-based environments

---

## 🎮 Features

* 🟢 Classic Snake gameplay
* 🎯 Real-time score tracking
* 🏆 Leaderboard system
* ⚡ Dynamic speed increase
* 🎨 Retro Nokia-style UI
* 🎮 Keyboard + D-pad controls
* 📱 Mobile swipe support
* 💡 Zero backend dependency

---

## 🛠 Tech Stack

* **Frontend:** HTML5 (Canvas), CSS3, JavaScript
* **Web Server:** Nginx
* **Deployment Type:** Static Web Hosting

---

## 📁 Project Structure

```bash
.
├── index.html
└── README.md
```

---

## ⚙️ Local Setup

### Option 1: Run directly

```bash
open index.html
```

### Option 2: Run using Python server

```bash
python3 -m http.server 8000
```

Access:

```bash
http://localhost:8000
```

---

## 🌐 Deployment using Nginx

### Step 1: Install Nginx

```bash
sudo apt update
sudo apt install nginx -y
```

### Step 2: Copy application file

```bash
sudo cp index.html /var/www/html/index.html
```

### Step 3: Restart Nginx

```bash
sudo systemctl restart nginx
```

### Step 4: Access application

```bash
http://<server-ip>
```

---

## 🐳 Docker Deployment (Optional)

### Dockerfile

```dockerfile
FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
```

### Build and Run

```bash
docker build -t snake-game .
docker run -d -p 80:80 snake-game
```

Access:

```bash
http://localhost
```

---

## 🕹 Controls

* ⬆ Arrow Up → Move Up
* ⬇ Arrow Down → Move Down
* ⬅ Arrow Left → Move Left
* ➡ Arrow Right → Move Right
* ⏎ Enter / Space → Start / Restart

---

## 📸 Preview

> Add a screenshot here after deployment

---

## 📈 Use Cases

* DevOps learning project
* Static site deployment demo
* Nginx configuration practice
* Docker + Nginx integration
* GitHub Pages hosting

---

## 🔒 Performance & Benefits

* ⚡ Fast load time (static content)
* 🧩 No server-side processing required
* 📦 Easily containerizable
* 🌍 Can be deployed on any cloud (AWS, Azure, GCP)

---

## 🚀 Future Enhancements

* 🔊 Sound effects
* 🌐 Online leaderboard (backend integration)
* 🎮 Multiplayer support
* ☁️ CI/CD pipeline integration
* 📊 Monitoring with Prometheus/Grafana

---

## 👨‍💻 Author

**Manoop M**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---


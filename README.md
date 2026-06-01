
# 🛕 Pilgrim Path — Temple Finder

### 🌐 Live Demo: [Click Here to Visit](https://ad-gitspace.github.io/upstart/Project/Finding%20Place%20lite)

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

---

## 📌 Problem Statement

Travelers and devotees across India often struggle to find accurate, centralized
information about temples and sacred sites in unfamiliar areas. Existing solutions
are either too heavy, require account creation, or lack proximity-based search.

## 💡 Solution

Pilgrim Path is a lightweight, fully client-side web application that uses the
Browser Geolocation API to instantly detect the user's location and display
nearby temples with accurate distances, rich details, and direct navigation support
— all without any login or app installation.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 📍 Auto-Location | Detects user location via Browser Geolocation API |
| 🔍 Smart Search | Search by temple name, deity, city, or state |
| 📊 Dynamic Sorting | Sort by Distance or Name |
| 🖼️ Image Gallery | Multi-image gallery with keyboard navigation |
| 🗺️ Google Maps | One-click directions to any temple |
| 🤝 Contributions | Community form to submit new temples |
| 📱 Responsive | Fully optimized for mobile devices |

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **APIs:** Browser Geolocation API, Google Maps Directions
- **Backend:** Node.js (for local contribution handling)
- **Hosting:** GitHub Pages (zero-cost, always available)

---

## 📁 Project Structure

pilgrim_path/
├── index.html          → Main search & listing page
├── temple.html         → Individual temple detail page
├── contribute.html     → Community contribution form
├── app.js              → Core search, filter & sort logic
├── detail.js           → Temple detail & image gallery logic
├── contribute.js       → Form validation & submission
├── server.js           → Node.js local server
├── styles.css          → Complete styling
└── data_source/
├── myList.json     → Temple database
├── image_index.json → Image mapping
└── indian_temples_img/ → Temple images


---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/nikhildev113/pilgrim_path.git

# Navigate to project
cd pilgrim_path

# Install dependencies
npm install

# Start the server
node server.js

# Open in browser
http://localhost:3000
```

---

## 📸 Screenshots

> Home Page with Auto-Location | Smart Search | Temple Detail with Gallery

---

## 🙏 Contributors

| Name | Role |
|------|------|
| Nikhil | Min-Max using Heaps |
| Adesh | Core Development |
| Amar | UI & Design |
| Shubhashish | Data & Search Logic |
| Tejas | Testing & Deployment |

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

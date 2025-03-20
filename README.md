# 🌐 EduWeb Offline Education Web — by Manya Valecha

> ✨ Empowering Education Anywhere. Anytime. Even Without Internet.

EduWeb Offline Education Web is a cutting-edge **Progressive Web App (PWA)** designed to bridge the education gap in areas with **low or no internet connectivity**. Built with modern offline-first technologies and powered by AI, EduWeb ensures uninterrupted learning for underserved communities.

This project is a proud submission for **Local Dawn Hackathon 2025**, crafted with passion and purpose to drive real-world impact.

---

## 📌 Project Overview

### 🎯 Goal:
To **enable access to educational content without internet**, empowering schools and learners in remote areas with tools that work **fully offline**, sync when online, and provide **AI-powered support**.

### 💡 Core Features:
- 📥 **Offline-First PWA** using Service Workers & IndexedDB
- 🧠 **AI Chatbot (TensorFlow.js)** powered by MobileBERT QnA model
- 🗃️ **PouchDB for local storage & sync**
- ⚡ **Service Workers for caching educational assets**
- 🔄 Seamless **online-offline sync mechanism**
- 🛠️ **Interactive UI tour** using Driver.js for accessibility
- 📱 Fully **mobile responsive** and device agnostic
- 🔔 **Offline/Online status indicators**
- 📂 **Modular & lightweight frontend design**
- 🧠 **Subject-based QnA switching with smooth context transitions**
- 🖼️ Optimized homepage background only visible on landing
- 🔗 Integrated real-world **Help support link** to [education.gov.in](https://dsel.education.gov.in/contact_us)

---

## 🏆 Why EduWeb Stands Out

| Feature                             | Impact                                                |
|------------------------------------|--------------------------------------------------------|
| Offline Content Access             | Learning never stops, even in internet dead zones     |
| AI Chatbot with Local Context      | Students can ask questions without needing Google      |
| Lightweight Design for Low-end Devices | Designed for rural & low-resource environments    |
| Smart Sync with PouchDB            | Local data preserved, synced when back online          |
| Help Link & UI Tour                | Makes learning and navigation intuitive for all users  |
| Hackathon Ready Polish             | Clean UI, structured code, engaging user experience    |

---

## 💻 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript, Vite
- **AI Integration:** TensorFlow.js (MobileBERT QnA)
- **Offline Storage:** IndexedDB + PouchDB
- **Progressive Web App:** Service Workers + Web Manifest
- **UI Enhancements:** Driver.js, FontAwesome, Google Fonts
- **Responsive Design:** Media queries + mobile-first layout

---

## ⚙️ Architecture Diagram

User Device │ ├──> EduWeb PWA (HTML/CSS/JS) │ ├─ Service Worker → Caching │ ├─ IndexedDB → Content Storage │ ├─ PouchDB → Sync Engine │ └─ TensorFlow.js → AI QnA │ └──> [Online Sync ↔ Server (when available)]


---

## ✨ Key Enhancements Added

- 🎨 **Brighter, clearer Contact Us page text**
- 🌇 **Homepage background image only on main page**
- 🤝 **Help button now redirects to official [education.gov.in help page](https://dsel.education.gov.in/contact_us)**
- 🚥 **Offline/Online detection for users**
- 🎈 **Interactive guided UI tour using Driver.js**
- ✅ **Polished accessibility and mobile responsiveness**
- 📜 **MIT License, changelog and contribution ready**

---

## 📷 Screenshots

| Homepage with Background | AI QnA Interface | Offline Status Alert | UI Tour Step |
|--------------------------|------------------|-----------------------|--------------|
| ![Home](./screenshots/homepage.png) | ![QnA](./screenshots/qna.png) | ![Offline](./screenshots/offline.png) | ![Tour](./screenshots/tour.png) |

> *(Add screenshots in `screenshots/` folder before submission for best presentation.)*

---

## 🚀 Getting Started Locally

```bash
# 1. Clone the repo
git clone https://github.com/your-username/eduweb-offline-pwa.git
cd eduweb-offline-pwa

# 2. Install dependencies
npm install

# 3. Run the app locally
npm run dev

# 4. Build for production
npm run build

# 5. Preview production build
npm run preview
📂 Directory Structure

/
├── public/
│   ├── img/               → Assets & logos
│   ├── manifest.webmanifest
│   └── index.html         → Main HTML structure
├── src/
│   ├── components/        → UI Components
│   ├── ai/                → QnA model integration
│   ├── serviceWorker.js   → PWA Service Worker
│   ├── db/                → IndexedDB/PouchDB utils
│   └── main.jsx           → App entry
└── README.md
📡 Real-world Use Cases

Rural schools with limited connectivity
Educational NGOs & community centers
Emergency learning solutions post-disasters
Mobile classrooms and remote tutoring
🤝 Contribution Guidelines

Fork the repo
Create a new branch (git checkout -b feature-name)
Make changes
Commit (git commit -m "Add feature")
Push (git push origin feature-name)
Create a Pull Request
📄 License

This project is licensed under the MIT License. Feel free to reuse and build upon it!

🧠 Acknowledgements

Community Health Toolkit (CHT) — inspiration for offline-first design
TensorFlow.js for enabling in-browser AI
PouchDB for seamless offline syncing
Driver.js for guiding the user journey
🥇 Final Words

“EduWeb Offline Education Web is more than code — it’s a vision for equal access to knowledge. It brings the power of AI and offline-first technology to the hands of every learner, no matter where they are.”
Crafted by Manya Valecha — with purpose, precision, and people in mind. ❤️

📬 Contact

For collaboration, feedback, or outreach: 📧 manyavalechaofficial@gmail.com 

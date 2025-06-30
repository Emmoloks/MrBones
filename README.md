# 🦴 MrBones

**MrBones** is an AI-powered, interactive skeletal system learning platform designed to make anatomy education engaging and accessible. Built for students, educators, and medical enthusiasts, it combines intelligent Q&A, 3D visualization, and clinical simulations to deliver a rich learning experience.

---

## 🌟 Key Features

- 🎯 **Full Skeletal System Mapping** – Visualize and explore all 206 bones with interactive 3D models
- 💬 **Natural Language Q&A** – Ask questions like *“What are bones made of?”* and receive smart, AI-generated responses
- 🦿 **Fracture & Healing Simulations** – Understand how bones break, and how healing works at different stages
- 🧠 **Adaptive Quizzing** – Personalized quizzes that grow with your knowledge level
- 📖 **Context-Aware Learning** – Every bone comes with rich metadata: structure, function, common injuries, and healing processes

---

## 🧱 Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| **Frontend** | React, TailwindCSS, Three.js        |
| **Backend**  | Node.js, Express, REST API          |
| **AI**       | Azure OpenAI, LangChain             |
| **Database** | MongoDB (Mongoose ODM)              |
| **DevOps**   | GitHub Actions, Docker, Vercel/Azure |
| **Auth**     | JWT / OAuth2.0                      |

---

## 🖼️ UI Preview

> ✨ Coming soon: Live demo link + walkthrough video

| Bone Explorer | Quiz Module | Healing Visualizer |
|---------------|-------------|--------------------|
| ![](./assets/explorer.png) | ![](./assets/quiz.png) | ![](./assets/heal.png) |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/Emmoloks/MrBones.git
cd MrBones

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and config

# Start development server
npm run dev

# Legally AI

An AI-powered legal assistant web application that helps users submit legal questions and receive guided responses using a language model.  
This project is a customized fork of the original *LegallyFit* repository with improvements for usability, configuration, and deployment.

---

## 🚀 Live Demo (Optional)

If deployed, add your live URL here:  
🔗 https://legally-ai.vercel.app

---

## 🧠 About The Project

**Legally AI** is a full-stack web application built with:

- **Next.js (React)** on the frontend  
- **Node.js + Express** on the backend  
- **MongoDB Atlas** as the database  
- Any AI provider for answering legal queries (configurable via environment variables)

Users can enter legal questions in natural language and get an AI-generated response. Past questions and answers are stored so users can view their question history.

---

## 📦 Features

- Clean and responsive UI built with Next.js
- REST API backend using Express
- Persistent interaction history stored in MongoDB
- Easy configuration with environment variables
- Ready for deployment via Vercel (frontend) and other hosts (backend)

---

## 🛠 Built With

| Layer        | Technology |
|--------------|------------|
| Frontend     | Next.js / React |
| Backend      | Node.js + Express |
| Database     | MongoDB Atlas |
| AI Provider  | Configurable (OpenRouter / Hugging Face / others) |
| Deployment   | Vercel (frontend), Render or Railway (backend) |
| Containerization | Docker |

---

## 📋 Getting Started

These instructions will get the project running on your local machine.

---

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/your-username/legally-ai.git
cd legally-ai
# Safe Space
**An anonymous posting platform with AI-powered moderation**  

---

## Overview
Safe Space is a platform where people can share their thoughts **freely and anonymously**, without the fear of being judged.  
To keep the space healthy and respectful, we use an **AI moderation system** that detects and filters harmful content in real-time.  

This project is structured into three repositories:  

- **Frontend** → [https://github.com/lakshay-jainn/SafeSpace](https://github.com/lakshay-jainn/SafeSpace)
  
  A minimal, distraction-free interface where users can post, read, and engage anonymously.  

- **Backend** → [https://github.com/lakshay-jainn/safe-space-be](https://github.com/lakshay-jainn/safe-space-be)
  
  Manages anonymous identities, stores posts securely, and connects the frontend with the AI moderation engine.  

- **AI Model** → [https://github.com/lakshay-jainn/space-space-ai](https://github.com/lakshay-jainn/space-space-ai)
  
  A custom-made moderation model that detects toxicity, hate speech, spam, and other harmful content.  

---

## Features
- **Anonymous Posting** — Share without attaching personal identity.  
- **AI Moderation** — Filters out toxic, hateful, or harmful posts automatically.  
- **Privacy First** — No login, no tracking, just pure expression.  
- **Minimal UI** — Clean, distraction-free design focused on content.  
- **Scalable Backend** — Secure APIs, database handling, and modular architecture.  

---

## 🛠️ Tech Stack
- **Frontend:** React + Tailwind (modern, responsive UI)  
- **Backend:** Node.js + Express + MongoDB (or PostgreSQL)  
- **AI Model:** Python + Transformers / PyTorch (toxic content detection, sentiment analysis)  

---

## 🔗 How It Works
1. User writes a post anonymously on the **frontend**.  
2. Post request goes to the **backend API**.  
3. Backend sends content to the **AI moderation model**.  
4. AI decides if the post is **Safe** or **Flagged**.  
5. Backend stores and returns safe posts to the feed.  

---

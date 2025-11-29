# 📸 Pexels Hunter Bot

<!-- BADGES -->
![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Aiogram](https://img.shields.io/badge/Aiogram-Async-blue?style=for-the-badge&logo=telegram&logoColor=white)
![Pexels API](https://img.shields.io/badge/API-Pexels-05A081?style=for-the-badge&logo=pexels&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Current Status:** ⚪ Archived (Source Code Only)


## ⚡ The Mission
Searching for stock footage manually is inefficient. **Pexels Hunter** is an asynchronous Telegram bot that acts as a bridge to the Pexels API, delivering high-resolution creative assets directly to the user's chat interface in milliseconds.

It includes a **Admin Broadcast Module** for mass-communication with the userbase.

---

## ⚙️ Core Capabilities

### 1. 🔍 High-Velocity Search Engine
- **Instant Retrieval:** Users send a keyword (e.g., "Cyberpunk City"), and the bot fetches top-rated results instantly.
- **Smart Filtering:** Selects the highest resolution available while optimizing for Telegram's upload limits.

### 2. ⚖️ Attribution & Metadata
- **Auto-Credit:** Every image comes with the Photographer's Name and a Direct Link to the source.
- **Compliance:** Fully adheres to Pexels API usage guidelines regarding attribution.

### 3. 📢 Admin Broadcast Protocol (Ad System)
- **Global Reach:** Administrators can trigger a "Broadcast Mode" to send announcements, updates, or promotional content to **all active users** simultaneously.
- **Async Delivery:** Uses non-blocking queues to send thousands of messages without freezing the bot.

---

## 🛠️ Technical Architecture

The system is built on **Aiogram (Python)** to ensure non-blocking performance.


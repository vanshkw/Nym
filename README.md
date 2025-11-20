# Nym

**Nym** is a 5-page anonymous social media platform built for the Rishihood University student community. It allows users to create a permanent anonymous "Handle" to post public discussion prompts, while engaging in 1-on-1 chats using temporary, random "Aliases" for complete privacy.

This project is built using only **HTML, CSS, and Vanilla JavaScript**, with all data persisted in the browser's **`localStorage`**.

---

## 🚀 About This Project

This is the **Semester 1 Capstone Project** for the SNW subject at Newton School of Technology (Batch 2025). The goal is to build a unique and dynamic social media website, applying knowledge of web fundamentals.

The core challenge is to create a persistent, interactive social experience using only client-side technologies, with no backend server or database.


## ✨ Core Features

* **Anonymous "Handle" System:** A "Welcome" page for new users to create a unique, persistent anonymous handle (saved in `localStorage`).
* **Dynamic Prompt Feed:** A home page that dynamically loads all public prompts from `localStorage`.
* **Prompt Filtering by Tag:** Users can filter the feed by categories like "Advice," "Study," or "Campus Life."
* **Anonymous Prompt Posting:** Users can post new discussion topics under their public handle.
* **Personal Chat Inbox:** A private "Inbox" page that lists all of a user's active chats.
* **Private 1-on-1 Chat Rooms:** Users can initiate a private chat from any prompt.
* **Dual-Alias System:** The core privacy feature. Users have a *public handle* for posts but are assigned *temporary, random aliases* (e.g., "Aqua 💧", "Terra 🌳") in each private chat to ensure total anonymity.
* **Simulated Real-Time Chat:** The chat room includes timestamps and uses `setInterval` to check `localStorage` for new messages, adding them to the UI instantly to feel like a live chat.
* **`localStorage` Data Persistence:** All user data (handles, prompts, chats) is stored in the browser, making the app persistent between sessions.
* **Responsive Design:** All 5 pages are fully responsive for mobile, tablet, and desktop.

## 🛠️ Tech Stack

* **HTML5:** For the semantic structure of the 5 pages.
* **CSS3:** For all styling, layout (Flexbox/Grid), and responsiveness.
* **JavaScript (ES6+):** For all client-side logic, DOM manipulation, and interactivity.
* **`localStorage`:** For the client-side "database" to store all user and app data.

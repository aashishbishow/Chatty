# Chatty 🗨️

**Chatty** is a lightweight real-time chat application built using **React**, **Express**, and **Socket.IO**. It features a minimal UI, fast messaging, and uses `nanoid` for generating unique IDs.

---

## ⚙️ Tech Stack

- **Frontend**: React (with CRA)
- **Backend**: Express.js
- **Realtime**: Socket.IO
- **ID Generation**: nanoid

---

## 🚀 Features

- 🔌 Real-time chat via WebSocket (Socket.IO)
- 🧾 Minimal UI with clean UX
- 🆔 Unique room and user ID generation using nanoid
- 🧠 In-memory user and message state (no database yet)

---

## 📦 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/aashishbishow/Chatty.git
cd Chatty
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the App

```bash
# Start the backend (Express + Socket.IO)
node server.js

# In another terminal, start the React frontend (adjust if using Vite or CRA)
npm start
```

> By default:
>
> * Frontend: [http://localhost:3000](http://localhost:3000)
> * Backend: [http://localhost:5000](http://localhost:5000)

---

## 💡 How It Works

1. Open **two or more browser tabs or windows** pointing to [http://localhost:3000](http://localhost:3000).
2. Each client connects automatically to the same default room.
3. Start typing and sending messages — they will appear in real-time across all connected clients.
4. No additional setup or room joining required.
5. All data lives in memory during runtime (no database).

---

## 📁 Project Structure

```
/client        → React frontend
/server.js     → Express backend with Socket.IO
/package.json  → Shared dependencies
```

---

## 🔧 Configuration

You can edit the port or default settings inside `server.js` and React client config.

---

## 📌 Limitations

* ❌ No persistent storage (in-memory only)
* ❌ No user authentication
* ❌ No message history after reload

---

## 🧪 Future Ideas

* Add MongoDB or Redis for persistence
* Add typing indicators, private messages
* Add room listing, user count, emojis

---

## 📝 License

MIT License

---

## 👤 Author

Made by [@aashishbishow](https://github.com/aashishbishow)

```


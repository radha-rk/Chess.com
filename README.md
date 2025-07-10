# ♟ Custom Chess Game

A real-time, multiplayer Chess game built using **Node.js**, **Socket.io**, and **Chess.js**. Play as White or Black with drag-and-drop controls, live updates, and spectator support.

&#x20;

---

## 🚀 Features

- ♟ Real-time multiplayer gameplay with Socket.io
- ♻️ Live board updates using FEN notation
- 🎮 Player roles: White, Black, or Spectator
- 👆 Intuitive drag-and-drop chess moves
- ✅ Valid move enforcement via chess.js
- 🔄 Automatic board flip for black player
- 📱 Responsive design using HTML/CSS

---

## 🧐 Tech Stack

- **Backend:** Node.js, Express.js, Socket.io, Chess.js
- **Frontend:** HTML, CSS, JavaScript
- **Templating:** EJS

---

## 📁 Project Structure

```
├── public/                 
│   └── client.js           
├── views/                 
│   └── index.ejs           
├── server.js               
├── package.json
└── README.md
```

---

## 🛠️ Installation & Running Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/custom-chess-game.git
   cd custom-chess-game
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   node server.js
   ```

4. **Open in browser**

   ```
   http://localhost:3000
   ```

---

## 🌐 How It Works

- When a client connects:
  - First two players are assigned `white` and `black`
  - Others become spectators
- Players take turns moving pieces by dragging and dropping
- Chess rules are enforced by `chess.js`
- Moves are validated and broadcast to all clients
- Disconnections free up the player slot

---

## 📸 Preview
<img width="889" height="503" alt="image" src="https://github.com/user-attachments/assets/f9aa8572-cd84-4938-8ad3-0d11db1da776" />


---


## 👩‍💻 Made by [Radha](https://github.com/radha-rk)

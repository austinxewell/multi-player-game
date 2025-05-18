# Attack Spheres

<!-- Status badges -->

![Node.js](https://img.shields.io/badge/Node.js-20.x-green?style=flat-square&logo=node.js&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-4.x-black?style=flat-square&logo=socket.io&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript&logoColor=black)
![Canvas API](https://img.shields.io/badge/Canvas%20API-HTML5-orange?style=flat-square&logo=html5&logoColor=white)
![Multiplayer](https://img.shields.io/badge/Real--Time-Multiplayer-blue?style=flat-square)

> A real-time multiplayer arena game where players eliminate each other with projectiles and climb the leaderboard.

![Game Preview](https://i.postimg.cc/y88tvRHj/attack-spheres-firing-projectiles.png)

---

## 🔗 Live Demo

**[Play Attack Spheres](https://attack-spheres.onrender.com)**

> ⚠️ Hosted on Render’s free tier — may require a cold start. Contact me if you want to coordinate a game session (info below).

---

## 📦 About the Project

Attack Spheres is a fast-paced multiplayer browser game. Players control “attack spheres” in a shared arena, firing projectiles to eliminate others and earn points.

Gameplay is powered by a real-time backend using **authoritative server movement**, **client-side prediction**, and **server reconciliation**. All player data is securely managed server-side to prevent cheating. The game dynamically handles joins, disconnections, and real-time leaderboard updates.

Visuals are rendered with the **Canvas API**, and the game accounts for device pixel ratio scaling for crisp visuals on all displays.

---

## ⚙️ Features

- 🎯 Real-time multiplayer gameplay
- 🕹️ Canvas-based visual rendering
- 📡 Socket.IO for instant server-client communication
- 🧠 Authoritative server movement logic
- ⚡ Client-side prediction + server reconciliation
- 🎮 Firing projectiles with server-side collision detection
- 🧼 Garbage collection of old projectiles
- 📊 Dynamic, real-time leaderboard (sorted by high score)
- 📵 Idle timeout/disconnection management
- 🖥️ Retina and hi-DPI display support

---

## 🛠 Tech Stack

| Technology     | Purpose                                            |
| -------------- | -------------------------------------------------- |
| **Node.js**    | Server runtime for real-time game logic            |
| **Socket.IO**  | Real-time WebSocket communication                  |
| **JavaScript** | Language used on both client and server            |
| **Canvas API** | Frontend rendering of players and projectiles      |
| **OOP**        | Game entities structured with object-oriented code |

---

## 📸 Screenshots

| Feature             | Preview                                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------- |
| Landing Screen      | ![](https://i.postimg.cc/SsMwcphp/attack-spheres-landing.png)                                  |
| Username Input      | ![](https://i.postimg.cc/XvhRZYt8/attack-sphere-username-input.png)                            |
| Random Spawn        | ![](https://i.postimg.cc/Z5ftSccX/attack-spheres-random-spawn-location-upon-user-creation.png) |
| Multiple Players    | ![](https://i.postimg.cc/9fr3F7g0/attack-spheres-adding-multiple-players.png)                  |
| Leaderboard View    | ![](https://i.postimg.cc/sgfdq8pp/attack-spheres-leaderboard.png)                              |
| Dynamic Leaderboard | ![](https://i.postimg.cc/L63FyRZ9/attack-spheres-dynamic-leaderboard.png)                      |
| Firing Projectiles  | ![](https://i.postimg.cc/y88tvRHj/attack-spheres-firing-projectiles.png)                       |

---

## 🚀 Getting Started

### Clone & Install

```bash
git clone https://github.com/austinxewell/multi-player-game.git
cd multi-player-game
npm install
```

### Run Server

```bash
node backend.js
```

Then open your browser and go to `http://localhost:3000`

---

## 🧠 Project Structure

```
attack-spheres/
├── backend.js
├── package.json
├── public/
│   ├── index.html
│   ├── js/
│   │   ├── classes/
│   │   │   ├── Enemy.js
│   │   │   ├── Particle.js
│   │   │   ├── Player.js
│   │   │   └── Projectile.js
│   │   ├── eventListeners.js
│   │   └── frontend.js
│   └── img/
```

---

## 👨‍💻 Author

**Austin Ewell**  
Front-End Developer — Focused on real-time systems, clean UI, and performance.

🔗 [GitHub](https://github.com/austinxewell)  
📧 [austin.ewell86@gmail.com](mailto:austin.ewell86@gmail.com)  
📱 [385-443-9375](tel:3854439375)

---

## 📄 License

Distributed under the Unlicense. See [The Unlicense](http://unlicense.org/) for more information.

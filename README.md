# ChatCord

ChatCord is a real-time chat application built using **Node.js**, **Express**, **Socket.io**, and **Redis**. It allows users to join chat rooms, exchange messages instantly, and see who else is online — with support for Redis-based scaling.

---

## Features

- Real-time messaging using Socket.io
- Multiple chat rooms support
- Redis adapter for horizontal scalability
- Bot welcome messages
- Display of current users in the room
- Clean and minimal UI

---

##  Tech Stack

- **Node.js** + **Express.js**
- **Socket.io**
- **Redis** (`@socket.io/redis-adapter`)
- **dotenv** for environment management
- **nodemon** for live server reload
- **HTML/CSS/JS** (client-side)

---

##  Installation

```bash
# Clone the repo
git clone https://github.com/ArghaAuddy/ChatCord-.git
cd ChatCord

# Install dependencies
npm install 
```

## Acknowledgements

Inspired by Brad Traversy’s ChatCord tutorial, with improvements for Redis scalability and custom features.

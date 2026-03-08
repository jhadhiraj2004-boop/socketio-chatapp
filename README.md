# Real-Time Chat Application

A real-time one-to-one chat platform built using **MERN stack and Socket.IO**.
The application enables instant messaging between users using **WebSockets**, while messages are handled by a **Node.js + Express backend**.

---

## Features

* Real-time messaging using **Socket.IO**
* WebSocket-based communication
* Node.js and Express backend
* React frontend interface
* Modular backend structure with routes and user management
* Scalable architecture for real-time applications

---

## Tech Stack

**Frontend**

* React.js
* HTML5
* CSS3
* JavaScript

**Backend**

* Node.js
* Express.js
* Socket.IO

**Other Tools**

* npm
* Git

---

## Project Structure

```
realtime-chat-app
│
├── client
│   ├── public
│   │   └── index.html
│   ├── src
│   └── package.json
│
├── server
│   ├── index.js
│   ├── router.js
│   ├── users.js
│   └── package.json
│
└── README.md
```

---

## Installation

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/realtime-chat-app.git
cd realtime-chat-app
```

---

### 2. Install backend dependencies

```
cd server
npm install
```

Start the backend server:

```
node index.js
```

Backend runs on:

```
http://localhost:5000
```

---

### 3. Install frontend dependencies

Open a new terminal:

```
cd client
npm install
```

Start the frontend:

```
npm start
```

or

```
npm run dev
```

Frontend runs on:

```
http://localhost:3000
```

or

```
http://localhost:5173
```

---

## Usage

1. Open the application in the browser.
2. Join the chat room.
3. Send and receive messages instantly in real time.

---

## Future Improvements

* User authentication (JWT)
* Private messaging
* Message persistence using MongoDB
* Online user indicator
* Typing indicators

---

## Author

**Dhiraj Kumar**

Electronics & Communication Engineering
Full Stack Developer (MERN)

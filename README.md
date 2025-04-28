# Real-Time Chat Application with WebSocket

A modern real-time chat application built with **Node.js** and **WebSocket**, supporting user identification and online user counting, designed with a clean and responsive UI.
## 👤 Profile

| Field  | Information         |
|--------|----------------------|
| Name   | Ridho Fauzi          |
| NIM    | 312310563            |
| Class  | TI.23.A.5            |

## 🚀 Features

- Unique user ID assigned automatically.
- Real-time chat without page reloads.
- Live online user counter.
- Notifications when users join or leave.
- Automatic reconnection when WebSocket disconnects.
- Modern, responsive chat UI (HTML + CSS).
- Basic XSS protection on messages.

## 🛠️ Tech Stack

- **Backend:** Node.js, [ws](https://www.npmjs.com/package/ws) WebSocket library
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Protocol:** WebSocket (Full-duplex communication)

## 📂 Project Structure

```
├── server.js         # WebSocket server
├── index.html        # Chat client UI
├── README.md         # Project documentation
```

## 🏃‍♂️ How to Run Locally

1. **Clone this repository:**

```bash
git clone https://github.com/your-username/realtime-websocket-chat.git
cd realtime-websocket-chat
```

2. **Install dependencies:**

```bash
npm install ws
```

3. **Start the WebSocket server:**

```bash
node server.js
```

4. **Open the chat client:**
   
Just open `index.html` directly in your browser (Chrome, Edge, etc.)

Make sure the server is running at `ws://localhost:8080`.

> **Tip:** You can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VSCode to serve `index.html` with auto-reload.

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/d6af073f-589e-4eb5-b471-5499e103e2c6)



*(optional, you can upload screenshots to the repo and update the paths above)*

## ✨ Future Improvements

- Add user authentication (login system).
- Save chat history using a database (e.g., MongoDB).
- Support private one-to-one messaging.
- Add file/image sharing feature.
- Dark mode toggle.
- Emoji support in messages.

## 📚 References

- [MDN WebSocket API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket)
- [RFC 6455 - The WebSocket Protocol](https://datatracker.ietf.org/doc/html/rfc6455)
- [ws npm package](https://www.npmjs.com/package/ws)


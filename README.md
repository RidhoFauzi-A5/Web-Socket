**Collaborative Drawing Board with WebSocket**
A real-time collaborative drawing application built with Node.js, Express, and Socket.IO, enabling multiple users to draw on the same canvas simultaneously in their browsers.

👤 Profile
Field	Information
Name	Ridho Fauzi
NIM	312310563
Class	TI.23.A.5

🚀 Features
Real-time collaborative drawing across multiple clients.

Full-duplex communication using WebSocket (Socket.IO).

Lightweight client-side drawing logic with canvas.

Automatic broadcasting of drawing events to all users.

Simple and responsive UI.

🛠️ Tech Stack
Backend: Node.js, Express, Socket.IO

Frontend: HTML, CSS, JavaScript (Vanilla), <canvas>

Protocol: WebSocket via Socket.IO (built on top of WebSocket)

📂 Project Structure
csharp
Salin
Edit
├── public/
│   └── index.html      # Frontend drawing UI
├── server.js           # WebSocket server
├── README.md           # Project documentation
🏃‍♂️ How to Run Locally
Clone the repository:

bash
Salin
Edit
git clone https://github.com/your-username/collaborative-drawing-board.git
cd collaborative-drawing-board
Install dependencies:

bash
Salin
Edit
npm install express socket.io
Start the server:

bash
Salin
Edit
node server.js
Open the app in your browser:

Navigate to http://localhost:3000

Make sure port 3000 is available and not blocked by another process.

🧪 How It Works
When a user draws on the canvas, their coordinates are sent to the server via WebSocket.

The server broadcasts this drawing event to all other connected users.

Other clients receive the event and replicate the drawing in real time.

📸 Screenshots
![image](https://github.com/user-attachments/assets/e4ad7ab5-7262-497f-abad-ab824cfa9b09)


✨ Future Improvements
Add color picker and brush size options.

Implement undo/redo functionality.

Save drawing history with a backend database.

Add user presence indicators (e.g., cursors).

Mobile/touch support.

📚 References
MDN WebSocket API

Socket.IO Documentation

Node.js Documentation

Express.js Guide


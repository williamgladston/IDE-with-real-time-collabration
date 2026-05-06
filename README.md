# 🚀 Full Stack Project with ReactJS, Node.js, and WebSocket 🌐

This is a full-stack application that uses **React.js** for the frontend, **Node.js** for the backend, and **WebSocket** for real-time communication between the client and server. This application provides a seamless experience for users who want to interact in real time! 🎮✨

## 💻 Technologies Used:

- **Frontend:** ![React](https://img.shields.io/badge/React.js-61DAFB?logo=react&logoColor=black) 
- **Backend:** ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
- **Real-Time Communication:** ![WebSocket](https://img.shields.io/badge/WebSocket-1e90ff?logo=websocket&logoColor=white)
- **Environment:** ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) & ![React](https://img.shields.io/badge/React.js-61DAFB?logo=react&logoColor=black)

---

## 📦 Project Setup & Installation 🛠️

Follow these steps to get the project up and running on your local machine.

### 1️⃣ Clone the Repository

Clone the repo to your local machine:

```bash
git clone https://github.com/SharmaSanchay/IDE-with-real-time-collabration.git
cd IDE-with-real-time-collabration

```
# 2️⃣ Frontend Setup (React.js) 🔧
# Step 1: Install Dependencies

Navigate to the frontend directory and install the required dependencies:
``` bash
cd frontend
npm install
```
# Step 2: Start the React Development Server 🚀

Once dependencies are installed, start the React development server:
``` bash
npm run dev
```
This should open up the application in your browser at http://localhost:5173.

# 3️⃣ Backend Setup (Node.js with WebSocket) 🌍
# Step 1: Install Dependencies

Navigate to the backend directory and install the required dependencies:
``` bash
cd backend
npm install
```
# Step 2: Start the Node.js Server 🚀

Once the dependencies are installed, start the backend server:
``` bash
npm run  start
```
This will start the backend server on http://localhost:3000. The WebSocket server will also be up and running, allowing real-time communication with the frontend.

## 🚀 Happy Coding! 💻🎉
## Explanation of Features:
- **WebSocket Connection**: This setup allows the frontend (React) and backend (Node.js) to communicate in real-time.
- **Frontend**: Simple WebSocket integration in React to display messages and send them to the server.
- **Backend**: WebSocket server built using the `ws` library in Node.js to broadcast messages to all connected clients.

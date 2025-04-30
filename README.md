## ⭐ Project Overview

This project replicates the functionality of **Google Docs**, offering a real-time collaborative document editing platform. It enables multiple users to simultaneously create, modify, and manage shared documents with live updates.

---

## 🟢 Key Features

- **Document Management:** Users can create, edit, and persist documents securely in the database.
- **Simultaneous Editing:** Multiple users can edit a single document at the same time, with updates propagated in real time.
- **Live Synchronization:** Edits from any user are instantly synchronized across all active clients to maintain consistency.
- **Advanced Text Formatting:** Integrated with the Quill rich text editor to support text styling, embedding images, and more.

---

## 🔧 Tech Stack

### 🚀 Frontend

| Technology | Description |
|------------|-------------|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | Component-based JavaScript library for building UI |
| ![Quill](https://img.shields.io/badge/Quill-1A202C?style=for-the-badge&logo=quill&logoColor=white) | Rich text editor for formatting content |
| ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-%231A202C.svg?style=for-the-badge) | Headless UI components built on top of Tailwind CSS |

### 🔙 Backend

| Technology | Description |
|------------|-------------|
| ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) | JavaScript runtime for building scalable backend services |
| ![Socket.IO](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white) | Enables real-time, bidirectional communication |

### 🗃️ Database

| Technology | Description |
|------------|-------------|
| ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) | NoSQL database for storing document data |

### 🛠️ Other Tools

| Technology | Description |
|------------|-------------|
| ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) | Strongly typed superset of JavaScript |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Containerization platform to ensure environment consistency |

---

## ✅ Summary

This clone serves as a collaborative text editor powered by real-time synchronization and modern web technologies. It delivers a seamless user experience through a responsive frontend and an efficient backend architecture.

---

## ▶️ Getting Started

To run this project locally, follow the setup steps below. This guide walks you through installing dependencies, configuring environment variables, and running the application.

---

### 🟡 Prerequisites

Ensure the following tools are installed on your system:

| Requirement | Version |
|-------------|---------|
| Node.js     | ≥ 18.x  |
| MongoDB     | Any (local or cloud) |
| npm or yarn | Latest  |

---

## 💻 Development Setup

### 🛠️ Manual Setup (without Docker)

#### 1️⃣ Clone the Repository

You can clone or fork the project using:

```bash
git clone https://github.com/catwine/miniProject.git
```

#### 2️⃣ Navigate to the Server Directory

```bash
cd miniProject/server
```

#### 3️⃣ Install Server Dependencies

Use your preferred package manager:

```bash
npm install
# or
yarn install
```

#### 4️⃣ Configure Environment Variables (Server)

Create a `.env` file inside the `server` directory:

```bash
touch .env
```

Add the following keys:

```
DATABASE_URL=<Your MongoDB connection URI>
CLIENT_ORIGIN=http://localhost:5173
```

> ⚠️ Replace `<Your MongoDB connection URI>` with your actual database connection string.

#### 5️⃣ Start the Backend Server

```bash
npm run dev
```

The server will be accessible at: [http://localhost:3000](http://localhost:3000)

---

#### 6️⃣ Open a New Terminal and Move to the Client Directory

```bash
cd ../client
```

#### 7️⃣ Install Client Dependencies

```bash
npm install
# or
yarn install
```

#### 8️⃣ Configure Environment Variables (Client)

Create a `.env` file inside the `client` directory:

```bash
touch .env
```

Add the following:

```
VITE_SERVER_URL=http://localhost:3000
```

#### 🔟 Start the React Application

```bash
npm run dev
```

Your frontend should now be running at: [http://localhost:5173](http://localhost:5173)

---

## ▶️ Live Preview

https://github.com/user-attachments/assets/b7990d6e-4e51-4c4f-9098-bab6629e53c8



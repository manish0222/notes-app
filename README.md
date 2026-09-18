# MERN Student Notes CRUD App

## Student Details

* **Name:** Manish Godbole
* **Student ID:** 2026201064
* **Course:** SSD
* **Lab Activity:** MERN CRUD App

## GitHub Repository

https://github.com/manish0222/notes-app

## Project Overview

A simple Student Notes CRUD application built using the MERN stack.

* **Frontend:** React + Vite
* **Backend:** Node.js + Express.js
* **Database:** MongoDB
* **ODM:** Mongoose
* **HTTP Client:** Axios

The application allows users to create, view, and delete notes.

---

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/manish0222/notes-app.git
cd notes-app
```

### 2. Start MongoDB

Make sure MongoDB is installed and running.

On Ubuntu:

```bash
sudo systemctl start mongod
```

Check the service:

```bash
sudo systemctl status mongod
```

The application uses:

```text
mongodb://localhost:27017/notes_db
```

---

## Backend Setup

Open a terminal and run:

```bash
cd server
npm install
npm start
```

The backend will run on:

```text
http://localhost:5000
```

Expected output:

```text
MongoDB connected
Server running on port 5000
```

### Backend API

| Method | Endpoint         | Description   |
| ------ | ---------------- | ------------- |
| POST   | `/api/notes`     | Create a note |
| GET    | `/api/notes`     | Get all notes |
| DELETE | `/api/notes/:id` | Delete a note |

---

## Frontend Setup

Open a **new terminal** and run:

```bash
cd notes-app/client
npm install
npm run dev
```

The frontend will run on:

```text
http://localhost:5173
```

Open the above URL in a browser.

---

## Running the Application

Make sure all three are running:

**Terminal 1 — MongoDB**

```bash
sudo systemctl start mongod
```

**Terminal 2 — Backend**

```bash
cd notes-app/server
npm start
```

**Terminal 3 — Frontend**

```bash
cd notes-app/client
npm run dev
```

Then open:

```text
http://localhost:5173
```

---

## Screenshots

* `screenshots/ui-preview.png` — Application UI with notes
* `screenshots/delete-action.png` — Successful DELETE request showing `200 OK`

---

## Submission

**Student ID:** 2026201064

Submission ZIP:

```text
2026201064_MERN_Lab.zip
```

Have not included `node_modules` or `dist` directories.

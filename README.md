Great 👍
Here’s a **clean, professional project title** and a **ready-to-use README.md** you can directly upload to GitHub.

---

## ✅ **Project Title (Choose One)**

**Recommended (Best):**

> **Visual Pipeline Builder with Dynamic Nodes**

Other good options:

* **Low-Code Pipeline Builder (React + FastAPI)**
* **Node-Based Workflow Builder**
* **Visual AI Pipeline Editor**
* **Drag-and-Drop Pipeline Editor**

👉 I recommend the **first one** — it sounds professional and neutral.

---

## 📄 **README.md (Full Content)**

You can copy-paste this directly into `README.md`.

---

# 🧩 Visual Pipeline Builder with Dynamic Nodes

A drag-and-drop, node-based pipeline builder built using **React**, **ReactFlow**, and **FastAPI**.
This project allows users to visually construct pipelines, connect nodes, define dynamic variables, and validate pipeline structure using a backend service.

---

## 🚀 Features

* 🔗 Drag-and-drop pipeline editor
* 🧱 Multiple node types (Input, Text, LLM, Output)
* ✍️ Dynamic Text Node with variable detection (`{{variable}}`)
* 🔄 Auto-resizing text area
* 🎯 Real-time creation of input handles
* 🌙 Clean, dark-themed UI
* 🔍 Backend validation for:

  * Number of nodes
  * Number of edges
  * DAG (Directed Acyclic Graph) check

---

## 🖥️ Tech Stack

### Frontend

* React
* ReactFlow
* Zustand (state management)
* JavaScript
* CSS (custom styling)

### Backend

* Python
* FastAPI

---

## 📂 Project Structure

```
.
├── frontend/
│   ├── src/
│   │   ├── nodes/
│   │   │   ├── base/
│   │   │   │   └── BaseNode.js
│   │   │   ├── inputNode.js
│   │   │   ├── textNode.js
│   │   │   ├── llmNode.js
│   │   │   └── outputNode.js
│   │   ├── ui.js
│   │   ├── store.js
│   │   ├── submit.js
│   │   └── App.js
│   └── package.json
│
├── backend/
│   └── main.py
│
└── README.md
```

---

## ⚙️ How to Run the Project

### 1️⃣ Backend (FastAPI)

```bash
cd backend
pip install fastapi uvicorn
uvicorn main:app --reload
```

Backend will run at:

```
http://localhost:8000
```

---

### 2️⃣ Frontend (React)

```bash
cd frontend
npm install
npm start
```

Frontend will run at:

```
http://localhost:3000
```

---

## 🧪 How to Use / Test the Application

1. Drag nodes from the toolbar onto the canvas.
2. Connect nodes using the handles.
3. In the **Text node**, type variables like:

   ```
   Hello {{username}}
   ```
4. New input handles appear automatically for each variable.
5. Connect Input → Text → Output.
6. Click **Submit Pipeline**.
7. View pipeline summary (nodes, edges, DAG status).

---

## 🧠 Key Design Decisions

* **BaseNode abstraction** reduces duplicated code and simplifies adding new node types.
* **Text node variable parsing** enables dynamic pipeline inputs.
* **Zustand** provides clean, centralized state management.
* **Backend validation** ensures pipeline correctness.

---

## 📌 Assignment Coverage

✅ Node abstraction
✅ Custom styling
✅ Dynamic Text node logic
✅ Backend integration & DAG validation

---

## 📽️ Demo

A screen recording walkthrough is included as part of the submission, showcasing:

* UI interaction
* Dynamic node behavior
* Backend validation
* Code overview

---

## 🙌 Author

**Abhishek Ambasta**
Frontend / Full Stack Developer

---

If you want, I can also:

* Shorten this README
* Make it more **startup-style**
* Add **badges** (React, FastAPI, etc.)
* Add **screenshots section**

Just tell me 👍

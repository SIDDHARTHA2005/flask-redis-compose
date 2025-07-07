# 🚀 Flask + Redis Docker Compose App

This mini project demonstrates a simple **Flask** web app that uses **Redis** as a backend database to count page visits. The entire application is containerized using **Docker Compose**.

> 🔥 Built by [@SIDDHARTHA2005](https://github.com/SIDDHARTHA2005)

---

## 📸 Screenshot
![Screenshot 2025-07-07 190419](https://github.com/user-attachments/assets/337bf117-f5b9-4517-b5fd-d6b822efc7b4)


---

## 🧰 Tech Stack

- 🐳 Docker & Docker Compose
- 🐍 Python 3.10 (Flask)
- 🧠 Redis (Hit Counter)
- 🧪 HTML (Flask Templates)

---

## 📁 Project Structure

flask-redis-compose/
├── app.py
├── requirements.txt
├── templates/
│ └── index.html
├── Dockerfile
└── docker-compose.yml


---

## 🚀 How to Run

Make sure Docker and Docker Compose are installed.

```bash
# Clone the project
git clone https://github.com/SIDDHARTHA2005/flask-redis-compose.git
cd flask-redis-compose

# Run with Docker Compose
docker-compose up --build

Open your browser: http://localhost:5000

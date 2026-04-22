# 🚀 Go Todo REST API

A simple and efficient RESTful API built with Go for managing Todos.  
Beginner-friendly and easy to extend.

---

## 📌 Features

- Create a Todo
- Get all Todos
- Get single Todo by ID
- Update a Todo
- Delete a Todo
- Fast and lightweight

---

## 🛠️ Tech Stack

- Go (Golang)
- Gorilla Mux
- net/http

---

## 📁 Project Structure

go-todo-api/
│── main.go
│── go.mod

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/your-username/go-todo-api.git  
cd go-todo-api

### 2. Install Dependencies

go mod tidy

### 3. Run the Server

go run main.go

---

## 🌐 Server

http://localhost:8000

---

## 📡 API Endpoints

### Get All Todos

GET /todos

---

### Get Single Todo

GET /todos/{id}

---

### Create Todo

POST /todos

Body:
{
  "task": "Learn Go",
  "done": false
}

---

### Update Todo

PUT /todos/{id}

Body:
{
  "task": "Master Go",
  "done": true
}

---

### Delete Todo

DELETE /todos/{id}

---

## 🧪 Testing

Use Postman, Thunder Client, or curl:

curl -X GET http://localhost:8000/todos

---

## 🚀 Future Improvements

- Add JWT Authentication
- Add Database (MongoDB / PostgreSQL)
- Docker Support
- Frontend Integration (React)

---

## 🤝 Contributing

1. Fork the repo  
2. Create a branch  
3. Make changes  
4. Submit PR  

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Rishi Soni  
Building impactful tech 🚀



## ✅ Description
A simple RESTful API built with Node.js and Express to manage a list of books (CRUD operations).  
Data is stored in memory (no database required).

---

## 🚀 Setup Instructions

### 🔧 Prerequisites
- Node.js installed

### 🛠 Installation & Run

```bash
npm install
npm start
````

Server runs at: [http://localhost:3000](http://localhost:3000)

---

## 🧪 API Endpoints

| Method | Endpoint     | Description       |
| ------ | ------------ | ----------------- |
| GET    | `/books`     | Get all books     |
| POST   | `/books`     | Add a new book    |
| PUT    | `/books/:id` | Update book by ID |
| DELETE | `/books/:id` | Delete book by ID |

---

## 📝 Sample Request for POST

```json
{
  "title": "Wings of Fire",
  "author": "A.P.J. Abdul Kalam"
}
```

## 📡 Sample cURL Request

```bash
curl -X POST http://localhost:3000/books \
-H "Content-Type: application/json" \
-d '{ "title": "1984", "author": "George Orwell" }'
```

---

## 📦 Technologies Used

* Node.js
* Express.js
* Postman (for testing)

---

## 📁 Folder Structure

```
book-api-rest-express/
├── index.js
├── package.json
└── README.md
```

---

## 👩‍💻 Author

Created for internship submission by **Chandrika Talluri**


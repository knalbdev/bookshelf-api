# 📚 Bookshelf API

A simple RESTful API built with **Hapi.js** and **Node.js**, designed as a submission project for the Dicoding course: _"Belajar Membuat Aplikasi Back-End untuk Pemula dengan JavaScript"_.

This API allows users to add, read, update, and delete books from a virtual bookshelf. It includes both required and optional features as per the course submission guidelines.

---

## 🚀 Features

- Add a new book (`POST /books`)
- Get all books (`GET /books`)
- Get book details by ID (`GET /books/{bookId}`)
- Update book data (`PUT /books/{bookId}`)
- Delete a book (`DELETE /books/{bookId}`)
- Query by book name (case-insensitive)
- Filter by reading status (`reading`)
- Filter by finished status (`finished`)
- ESLint support for consistent code style

---

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/)
- [Hapi.js](https://hapi.dev/)
- [nanoid](https://github.com/ai/nanoid) for generating unique IDs
- [ESLint](https://eslint.org/) for code linting

---

## ⚙️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/bookshelf-api.git
   cd bookshelf-api
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm run start
   ```
   > Server runs at `http://localhost:9000`

---

## 🧪 API Testing

You can test the API using [Postman](https://www.postman.com/).  
The Postman test collection and environment file are available here:

🔗 [Bookshelf API Test Collection](https://github.com/dicodingacademy/a261-backend-pemula-labs/raw/099-shared-files/BookshelfAPITestCollectionAndEnvironment.zip)

---

## 🔍 Example Query Parameters

You can use the following optional query parameters when fetching all books:

- `/books?name=dicoding`
- `/books?reading=1`
- `/books?finished=0`

---

## 🧹 Linting

To check for code style issues, run:
```bash
npm run lint
```

To automatically fix lint issues:
```bash
npx eslint . --fix
```

---

## 📜 License

This project is part of a submission for Dicoding Indonesia's course  
_"Belajar Membuat Aplikasi Back-End untuk Pemula dengan JavaScript"_  
© 2025 – Tia
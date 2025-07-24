# 📚 Book Tracker API – My First Spring Boot Project

This is my very first Spring Boot project — a simple **Book Tracker API** that allows users to manage books with full CRUD functionality. The app follows a clean layered architecture and connects to an in-memory H2 database.

---

## 🚀 Features

- ➕ Add a new book
- 📖 View all books
- 🔍 Get book by ID
- ✏️ Update book details
- ❌ Delete a book
- 🔄 RESTful API structure
- 💾 H2 Database for testing

---

## 🧰 Tech Stack

- Java 17+
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Postman

---

## 📁 Project Structure

```

src/
└── main/
├── java/
│   └── com.example.booktracker
│       ├── controller
│       ├── model
│       ├── repository
│       └── service
└── resources/
├── application.properties

````

---

## 🔗 API Endpoints

| Method | Endpoint        | Description         |
|--------|-----------------|---------------------|
| GET    | `/books`        | Get all books       |
| GET    | `/books/{id}`   | Get book by ID      |
| POST   | `/books`        | Create a new book   |
| PUT    | `/books/{id}`   | Update book by ID   |
| DELETE | `/books/{id}`   | Delete book by ID   |

---

## 🛠️ Run the App

1. **Clone the project:**
```bash
git clone https://github.com/your-username/book-tracker.git
cd book-tracker
````

2. **Open in IntelliJ / VS Code**

3. **Start the application:**

```bash
./mvnw spring-boot:run
```

4. **Access the API:**

```
http://localhost:8080/books
```

5. **Access H2 Console:**

```
http://localhost:8080/h2-console
```

* JDBC URL: `jdbc:h2:mem:testdb`
* Username: `sa`
* Password: *(leave blank)*

---

## 🧪 Sample Book JSON

```json
{
  "title": "Atomic Habits",
  "author": "James Clear",
  "genre": "Self-help"
}
```

---

## 📬 Postman Testing

Test all endpoints using [Postman](https://www.postman.com).
Make sure your request body is in raw JSON and headers include:

```
Content-Type: application/json
```

---

## 📝 License

This project is open-source and free to use for learning or educational purposes.

---

## 👩‍💻 Author

Built with ❤️ by **Nethmi Herath**
🔗 [Portfolio](https://nethmi-herath.netlify.app/)
📘 This is my **first Spring Boot project**!

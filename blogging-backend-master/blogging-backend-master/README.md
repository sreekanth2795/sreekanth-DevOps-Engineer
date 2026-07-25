# Blogging Backend Application 📝

This is a **backend REST API** for a blogging platform built with **Java Spring Boot**. It allows users to create, read, update, and delete blog posts, manage categories, and handle user authentication.

---

## 🚀 Features

- **User Authentication:** Register, login, and secure endpoints using JWT tokens.
- **Blog Management:** Create, update, delete, and fetch blog posts.
- **Category Management:** Organize posts into categories.
- **CRUD APIs:** Fully functional RESTful endpoints for blogs and users.
- **Pagination & Sorting:** Easily fetch posts with pagination and sort by date, title, or category.
- **Role-Based Access Control:** Admin and regular user roles for secured access.

---

## 💻 Tech Stack

| Layer            | Technology                       |
|-----------------|---------------------------------|
| Backend         | Java 17, Spring Boot             |
| Database        | PostgreSQL / MySQL               |
| Security        | Spring Security, JWT             |
| Persistence     | JPA / Hibernate                  |
| Build Tool      | Maven                            |
| API Testing     | Postman / Swagger                |

---

## 📁 Project Structure

```

blogging-backend/
├── src/main/java/
│   └── com.example.blog/
│       ├── controller/       # REST controllers
│       ├── model/            # Entities and models
│       ├── repository/       # JPA repositories
│       ├── service/          # Business logic
│       └── security/         # JWT and authentication
├── src/main/resources/
│   ├── application.properties
└── pom.xml

````

---

## ⚡ Getting Started

### Prerequisites

- Java 17+
- Maven
- PostgreSQL / MySQL
- Postman (optional, for testing APIs)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/blogging-backend.git
cd blogging-backend
````

2. **Configure Database**

* Update `src/main/resources/application.properties` with your database credentials:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/blogdb
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update
```

3. **Build and Run**

```bash
mvn clean install
mvn spring-boot:run
```

---

## 🛠 Usage

* Use Postman or any API client to test endpoints.
* **Endpoints Examples:**

  * `POST /api/auth/register` – Register a user
  * `POST /api/auth/login` – Login and get JWT
  * `GET /api/posts` – Fetch all posts
  * `POST /api/posts` – Create a new post (authenticated)
  * `PUT /api/posts/{id}` – Update post (authenticated)
  * `DELETE /api/posts/{id}` – Delete post (admin or owner)

---

## 📝 Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a feature branch:

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push to your branch:

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🌐 Contact

* GitHub: Sreekanth Penumala
* Email: sreekanth.p2793@gmail.com


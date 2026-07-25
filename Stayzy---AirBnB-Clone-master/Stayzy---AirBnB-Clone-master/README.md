# Stayzy - Airbnb Clone 🏡

Stayzy is a modern, full-stack web application inspired by Airbnb, allowing users to **discover, list, and book accommodations** seamlessly.

---

## 🚀 Features

- **User Authentication** – Sign up, log in, and secure access.
- **Property Listings** – Hosts can add, edit, or remove their listings.
- **Search & Filters** – Find stays by location, price, and amenities.
- **Booking System** – Book stays and manage reservations.
- **Responsive UI** – Works on desktop and mobile.
- **Stripe Integration** – Secure payment processing in test mode.

---

## 💻 Tech Stack

| Frontend       | Backend           | Database         | Other Tools           |
|----------------|-----------------|-----------------|----------------------|
| React / HTML / CSS | Spring Boot / Java | PostgreSQL / MySQL | Stripe API, REST API |
| Responsive Design | Spring Security | JPA / Hibernate | Git, GitHub |

---

## 📁 Project Structure

```

Stayzy/
├── backend/               # Spring Boot application
│   ├── src/main/java/
│   └── src/main/resources/
├── frontend/              # React / HTML / CSS
├── README.md
└── .gitignore

````

---

## ⚡ Getting Started

### Prerequisites

- Java 17+
- Maven
- Node.js & npm
- PostgreSQL / MySQL
- Stripe account (for testing payments)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/amansachann/Stayzy---AirBnB-Clone.git
cd Stayzy
````

2. **Backend Setup**

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

3. **Frontend Setup**

```bash
cd frontend
npm install
npm start
```

4. **Configure Environment Variables**

* Create a `.env` file for secrets like `STRIPE_API_KEY`:

```env
STRIPE_API_KEY=your_test_key_here
```

---

## 🛠 Usage

* Register as a user or host.
* Add or browse property listings.
* Search and filter by location, price, or amenities.
* Make bookings and process payments (Stripe test mode).

---

## 📝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```
3. Make your changes.
4. Commit your work:

   ```bash
   git commit -m "Add new feature"
   ```
5. Push to your branch:

   ```bash
   git push origin feature-name
   ```
6. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🌐 Contact

* GitHub: [amansachann](https://github.com/amansachann)
* Email: [codewithaman78@gmail.com](mailto:codewithaman78@gmail.com)


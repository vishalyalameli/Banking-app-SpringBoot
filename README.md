
# 🏦 Banking App - Spring Boot

A simple RESTful Banking Application backend built with **Spring Boot**, **Spring Data JPA (Hibernate)**, and **MySQL**.  
This project provides APIs for account creation, balance checking, deposit, withdrawal, and account deletion.

---

## 🚀 Features

- Create Bank Account
- View Account Details
- Deposit Amount
- Withdraw Amount
- Delete Account
- Validations and Error Handling

---

## 🛠 Tech Stack

- Java 17+
- Spring Boot
- Spring Data JPA (Hibernate)
- MySQL
- Maven
- Postman (for testing)

---

## 📦 API Endpoints

| Method | Endpoint              | Description              |
|--------|-----------------------|--------------------------|
| POST   | `/api/accounts`       | Create new account       |
| GET    | `/api/accounts/{id}`  | Get account details      |
| PUT    | `/api/accounts/{id}/deposit` | Deposit money         |
| PUT    | `/api/accounts/{id}/withdraw`| Withdraw money       |
| DELETE | `/api/accounts/{id}`  | Delete account           |

---

## 🧪 Sample JSON Payload

### Create Account:
```json
{
  "name": "Vishal Yalameli",
  "initialBalance": 5000
}

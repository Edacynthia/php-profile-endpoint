# Stage 0 Backend Task (Pure PHP)

## 📝 Description
A simple **RESTful API** built with **pure PHP** that returns my profile information along with a **dynamic cat fact** fetched from an external API ([Cat Facts API](https://catfact.ninja/fact)).

This project satisfies all requirements for the **Stage 0 Backend Task**, including proper JSON response structure, dynamic data fetching, and clean, production-ready code.

---

## ⚙️ Tech Stack
- **PHP 8+**
- **cURL** (for external API calls)
- **JSON** (for structured API response)

---

## ⚙️ Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/Usenmfon/dynamic-profile-endpoint.git
cd php-profile-endpoint
```


### 2. Run project
```bash
php -S localhost:8000
```

### 3. Access the API endpoint

Open your browser or use Postman/cURL:

GET request:

http://localhost:8000/me


## 🚀 Endpoint
| Method | Endpoint | Description |
|--------|-----------|-------------|
| **GET** | `/me` | Returns profile info and a random cat fact |

---

## 📦 Response Format
```json
{
  "status": "success",
  "user": {
    "email": "edacynthia3@gmail.com",
    "name": "Eda Cynthia Itsekirimi",
    "stack": "PHP, Laravel"
  },
  "timestamp": "2025-10-16T15:23:42.213Z",
  "fact": "Cats sleep 70% of their lives."
}

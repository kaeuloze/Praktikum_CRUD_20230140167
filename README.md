
# 📘 User API Documentation

## 🔗 Base URL

```
/api/users
```

---

# 📌 1. Get All Users

**Method:** `GET`
**Endpoint:** `/api/users`

### ✅ Response

```json
{
  "data": [
    {
      "id": "7d83d59d-4e07-4057-8aa2-8031a1619af2",
      "name": "Mariska",
      "age": 20
    },
    {
      "id": "d231e2aa-256f-4817-a7c0-21489c84ad0f",
      "name": "Dipo",
      "age": 16
    },
    {
      "id": "d75f820d-1d07-4733-af0d-8c097e433cfd",
      "name": "Dipo",
      "age": 16
    }
  ],
  "status": "success"
}
```

---

# 📌 2. Create User

**Method:** `POST`
**Endpoint:** `/api/users`

### 📥 Request Body

```json
{
  "name": "Dipo",
  "age": "16"
}
```

### ✅ Response

```json
{
  "status": "success",
  "message": "User berhasil ditambahkan",
  "data": {
    "id": "dec554a4-1005-41ae-995d-fe24196b2fd0",
    "name": "Dipo",
    "age": 16
  }
}
```

---

# 📌 3. Update User

**Method:** `PUT`
**Endpoint:** `/api/users/{id}`

### 📥 Request Body

```json
{
  "name": "Sifa",
  "age": "16"
}
```

### ✅ Response

```json
{
  "status": "success",
  "message": "User berhasil diperbarui",
  "data": {
    "id": "dec554a4-1005-41ae-995d-fe24196b2fd0",
    "name": "Sifa",
    "age": 16
  }
}
```

---

# 📌 4. Delete User

**Method:** `DELETE`
**Endpoint:** `/api/users/{id}`

### ✅ Response

```json
{
  "message": "User berhasil dihapus dengan id dec554a4-1005-41ae-995d-fe24196b2fd0",
  "status": "success"
}
```

---

TAMPILAN WEBSITE 
<img width="1914" height="962" alt="image" src="https://github.com/user-attachments/assets/b0b984dc-3214-4136-b09f-5c3084eed215" />

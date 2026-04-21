# ReqRes API Testing with Postman

This repo demonstrates API testing using Postman & Newman against the **ReqRes API**.

## 📌 Features Tested

✔ GET /users — list users  
✔ GET /users/{id} — fetch single user  
✔ POST /users — create user  
✔ PUT /users/{id} — update user  
✔ PATCH /users/{id} — partial update  
✔ DELETE /users/{id} — delete user
✔ Negative scenarios

## 📁 Structure

- **collections/** — Postman Collection JSON
- **environments/** — Environment JSON
- **newman_reports/** — Generated reports

## ▶ Run with Newman

```bash
newman run collections/collection.json \
  -e environments/environment.json \
  -r html
```

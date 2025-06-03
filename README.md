# Test-PetStore
Tests for PetStore 4 endpoits

time spent: 4h
used ChatGPT to make everything beautiful ✨

## 🗓 Task 1: Postman Collection (Swagger: https://petstore.swagger.io)

### ✅ Endpoints

1. **Create Pet** - `POST /pet`
2. **Get Pet** - `GET /pet/{petId}`
3. **Update Pet** - `PUT /pet`
4. **Get Pet After Update** - `GET /pet/{petId}` (to verify updates)

### 📃 Dynamic Data

Pre-request Script (**collection** level) ensures a **new random ID is generated once per run**, and remains constant during that run. `pm.variables` are **temporary** and cleared after the run automatically.


## 📊 Task 2: Test Cases for `POST /pet`

![image](https://github.com/user-attachments/assets/509eca9c-2a2f-4254-953b-ff2e5e215d68)

---

### ✅ Приклад тест-кейсу: Створення улюбленця
![image](https://github.com/user-attachments/assets/a8342793-18d8-48ec-b52f-e5d547605610)



## 🔄 How to Run

1. Import `Petstore_Collection.json` to Postman
2. Run the collection using Postman Runner (no manual edits required)
3. A new pet is generated per run automatically
4. Temporary variables (`pm.variables`) reset after each run automatically

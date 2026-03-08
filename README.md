# Teachers API Automation

## Project Overview

This project contains automated API tests for Authentication and Teachers CRUD APIs using Postman and Newman.

## Technologies

* Postman
* Newman
* Node.js
* HTML Extra Reporter

## Test Cases

1. Login Authentication
2. Create Teacher
3. Get All Teachers
4. Get Teacher by ID
5. Update Teacher
6. Delete Teacher
7. Negative Test Scenarios

## How to Run

### Install Newman

```
npm install -g newman
```

### Run Collection

```
newman run collection.json
```

### Generate HTML Report

```
newman run collection.json -r htmlextra
```
![HTML Extra Report](screenshots/image.png)

## Project Files

* collection.json (Postman Collection)
* environment.json (Environment File)
* HTML Report

## Drive Folder

## 1. Token Saved

![Token Saved](screenshots/a.png)

---
## 2. Environment variable Saved

![Token Saved](screenshots/b.png)

---

## 3. Create Teacher and Save teacherId

![Create Teacher](screenshots/d.png)

---
## 4. Get Teacher by id

![Get Teacher By Id](screenshots/e.png)

---

## 5. Update Teacher Verified

![Update Teacher](screenshots/f.png)

---

## 6. Delete Teacher + 404 Verification

![Delete Teacher](screenshots/g.png)

---

## 7. Negative Test Cases Passing

![Negative Test](screenshots/h.png)
![Negative Test](screenshots/i.png)
![Negative Test](screenshots/j.png)
![Negative Test](screenshots/k.png)

## Video Demonstration

(Add Video Link Here)





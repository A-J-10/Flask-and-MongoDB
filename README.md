# Flask & MongoDB Assignment

This repository contains two separate Flask-based projects.

---

# 1. Flask Project

A simple Flask API project that reads data from a JSON file and returns it through the `/api` route.

### Run Project

```bash
cd Flask
pip install -r requirements.txt
python app.py
```

### Open in Browser

http://127.0.0.1:5000/api

---

# 2. MongoDB Project

A Flask form application connected with MongoDB Atlas.  
Submitted form data is stored in the database and redirects to a success page.

### Create `.env` File

Inside the `MongoDB` folder create a file named:

```env
.env
```

Add:

```env
MONGO_URI=your_mongodb_connection_string
```

---

### Run Project

```bash
cd MongoDB
pip install -r requirements.txt
python app.py
```

### Open in Browser

http://127.0.0.1:5000

---

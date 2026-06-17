# 📅 Timestamp Microservice

This is a **backend-only API project** built as part of the **freeCodeCamp Backend Development and APIs Certification**.

It is the **first major project in the certification path** and focuses on building a simple but powerful REST API using Node.js and Express.

👉 This project has **no frontend (no client-side UI)** — it only serves JSON responses through API endpoints.

---

## 🎯 Project Purpose

The goal of this project is to build a microservice that converts date values into:

- Unix timestamp (milliseconds)
- UTC date string

It demonstrates how to handle:
- URL parameters
- Date parsing in JavaScript
- API development using Express.js
- Error handling for invalid inputs

---

## 🚀 Features

- Get current timestamp
- Convert valid date strings to Unix + UTC format
- Accept Unix timestamp input
- Handle invalid date errors
- Simple REST API structure

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- JavaScript
- CORS middleware

---

## 📁 Project Structure

👉 No frontend (client folder is NOT used in this project)

---
## 📡 API Endpoints

### 🔹 Get current timestamp

GET /api

👉 Returns current time in Unix and UTC format

---

### 🔹 Get timestamp from date (string or Unix)

GET /api/:date

👉 Accepts:
- Date string (e.g. 2015-12-25)
- Unix timestamp (e.g. 1451001600000)

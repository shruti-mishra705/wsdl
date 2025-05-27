# wsdl
# 🌐 SOAP Hello World Service

This is a simple **SOAP-based web service** built with **Node.js**, **Express**, and **Strong-soap**, which responds with a personalized greeting. It includes a minimal web-based UI for sending requests and displaying responses.

---

## 📁 Project Structure

├── server.js # Main server file
├── service.wsdl # WSDL file describing the SOAP service
├── index.html # Frontend UI to test the SOAP service
├── package.json # Node.js dependencies and scripts


---

## 🚀 Features

- SOAP Web Service using `strong-soap`
- UI to consume the SOAP service
- Deployed on [Render](https://render.com/)
- Accepts a name and returns: `Hello, <name>!`

---

## 📦 Dependencies

- `express`
- `strong-soap`
- `fs`
- `path`
- `http`

---

## 🔧 Setup Instructions

### 1. Clone the Repository
### 2. Install Dependencies
npm install
### 3. Start the Server
npm start
Server runs on: http://localhost:8000

### 🌐 Accessing the SOAP Service
📄 WSDL URL
http://localhost:8000/wsdl?wsdl

### 🔘 Test UI
Open in browser:
http://localhost:8000/ui

Enter your name and hit "Say Hello!"

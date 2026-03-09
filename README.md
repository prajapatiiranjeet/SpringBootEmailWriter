# Email Writer

Email Writer is a productivity tool that helps users generate well-structured emails quickly using AI. The project consists of a **browser extension, a React-based interface, and a Spring Boot backend service** that processes requests and generates email content.

The goal of this project is to simplify email writing by allowing users to provide a short prompt or context and automatically generate a professional email draft. It can be useful for composing replies, drafting professional messages, or improving email clarity and tone.

---

# Features

* Generate email drafts from a short prompt
* Clean and simple user interface
* Browser extension support for quick access
* Backend service for processing email generation requests
* Modular architecture with separate frontend and backend components
* Easy integration with other applications

---

# Project Structure

The repository contains multiple components that work together.

```
email-writer
│
├── email-writer-ext        # Browser extension
├── email-writer-react      # React frontend application
├── email-writer-sb         # Spring Boot backend service
├── hello-world-ext         # Sample extension project
└── README.md
```

### email-writer-react

Frontend application built using React.
Provides the user interface where users can enter prompts and receive generated email responses.

### email-writer-sb

Backend service built with Spring Boot.
Handles API requests from the frontend and processes email generation logic.

### email-writer-ext

Browser extension that allows users to quickly generate emails directly from the browser.

---

# Technologies Used

### Backend

* Java
* Spring Boot
* REST APIs

### Frontend

* React
* JavaScript
* HTML
* CSS

### Tools

* Maven
* Node.js
* Browser Extension APIs

---

# Installation and Setup

## 1. Clone the Repository

```bash
https://github.com/prajapatiiranjeet/SpringBootEmailWriter.git
cd email-writer
```

---

# Backend Setup (Spring Boot)

Navigate to the backend directory:

```bash
cd email-writer-sb
```

Run the Spring Boot application:

```bash
mvn spring-boot:run
```

The backend server will start and expose APIs for the frontend.

---

# Frontend Setup (React)

Navigate to the React application directory:

```bash
cd email-writer-react
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The frontend will run locally and communicate with the backend service.

---

# Browser Extension Setup

1. Open **Google Chrome**
2. Go to **chrome://extensions/**
3. Enable **Developer Mode**
4. Click **Load unpacked**
5. Select the folder:

```
email-writer-ext
```

The extension will now appear in your browser toolbar.

---

# How It Works

1. The user enters a prompt describing the email they want to write.
2. The frontend sends the request to the backend API.
3. The backend processes the request and generates an email response.
4. The generated email is returned to the frontend and displayed to the user.

---

# Future Improvements

* Integration with email platforms (Gmail, Outlook)
* More customization options for tone and style
* Improved UI for faster interaction
* Support for multiple languages
* Better AI prompt optimization

---

# License

This project is created for educational and learning purposes.


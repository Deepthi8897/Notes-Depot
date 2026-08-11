# Notes-Depot
-A Full stack web application that is used by B. Tech students which provide all academic notes of all semesters to view  and download. Gives you tube videos with most views and likes for the topic and a friendly chatbot named buddy to ask  any questions related to the subject and clarify the doubts.  
# 📚 Notes Depot – Simplified Learning Resource

Notes Depot is a web-based educational platform designed mainly for engineering students to access study materials, tutorial videos, and AI-powered academic assistance in one place.

The platform provides subject-specific notes that users can view and download, tutorial videos fetched using the YouTube Data API, and an interactive chatbot called **Buddy** powered by the OpenAI API.

---

## 🚀 Features

### 📖 Notes Repository
- Access subject-specific study notes.
- Filter notes based on:
  - Year
  - Semester
  - Subject
- View and download available notes.

### 🎥 Tutorial Videos
- Search for educational and tutorial videos.
- Videos are retrieved using the YouTube Data API.
- Provides supplementary learning resources for different topics.

### 🤖 Buddy – AI Chatbot
- Interactive chatbot for academic queries.
- Users can ask questions in natural language.
- Responses are generated using the OpenAI API.

### 🗄️ MySQL Database
- Stores educational notes and related information.
- Supports retrieving notes based on year, semester, and subject.
- Uses CRUD operations for database management.

### 🌐 Responsive Web Interface
- Simple and user-friendly interface.
- Built using HTML, CSS, and JavaScript.
- Separate sections for Notes, Tutorial Videos, and Buddy.

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL
- XAMPP

### APIs
- YouTube Data API
- OpenAI API

### Development Tools
- Visual Studio Code
- npm

---

## 🏗️ Project Architecture

```text
                    ┌───────────────────┐
                    │      User         │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │    Frontend       │
                    │ HTML/CSS/JS       │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │  Node.js +        │
                    │  Express Server   │
                    └──────┬─────┬──────┘
                           │     │
                ┌──────────┘     └───────────┐
                ▼                            ▼
       ┌─────────────────┐          ┌─────────────────┐
       │  MySQL Database │          │ External APIs   │
       │     Notes       │          │ YouTube/OpenAI  │
       └─────────────────┘          └─────────────────┘




notes-depot/
│
├── frontend/
│   ├── index.html
│   ├── notes.html
│   ├── videos.html
│   ├── about.html
│   ├── styles.css
│   ├── script.js
│   └── script1.js
│
├── server.mjs
├── database.js
├── package.json
└── README.md


User
  │
  ▼
Home Page
  │
  ├──────────────► Notes
  │                  │
  │                  ├── Select Year
  │                  ├── Select Semester
  │                  ├── Select Subject
  │                  └── View / Download Notes
  │
  ├──────────────► Tutorial Videos
  │                  │
  │                  └── Search YouTube Videos
  │
  └──────────────► Buddy
                     │
                     └── Ask Academic Questions
                              │
                              ▼
                         OpenAI API

🎯 Project Objectives

The main objectives of Notes Depot are:

Provide a centralized repository for educational notes.
Make study materials easier to find and access.
Provide tutorial videos for additional learning.
Provide AI-based assistance through the Buddy chatbot.
Create a simple and user-friendly learning platform for engineering students.
🔮 Future Enhancements

Planned improvements include:

👨‍💼 Admin content management system
📱 Progressive Web App (PWA)
🤖 Advanced NLP-powered chatbot
📝 Interactive note-taking
👥 Discussion forums and community features
📚 Expansion of educational content
⚡ Performance and scalability improvements

👨‍💻 Contributors
KOTHUR DEEPTHI

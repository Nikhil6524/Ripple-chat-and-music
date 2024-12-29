# Chat and Music Web Application

This repository contains a full-stack web application that combines real-time chat functionality with an integrated music playback feature. The application leverages modern web technologies to deliver a seamless user experience.

---

## 🚀 Features

### Chat Module:
- **Real-Time Messaging**: Instant chat functionality for one-to-one or group conversations.
- **User Authentication**: Secure login and registration system.
- **Typing Indicators**: Notifies when a user is typing.
- **Message History**: Stores and retrieves chat history.

### Music Module:
- **Music Playback**: Stream or play local music files directly within the application.
- **Playlists**: Create and manage custom playlists.
- **Search**: Find songs by title, artist, or album.
- **Now Playing**: Display the current track with playback controls.

---

## 🗂️ Project Structure

```plaintext
├── frontend/                     # Frontend application (TypeScript)
│   ├── src/
│   │   ├── components/           # React components
│   │   ├── pages/                # Application pages
│   │   ├── styles/               # CSS and styling
│   │   ├── services/             # API service integrations
│   │   ├── App.tsx               # Root application component
│   │   └── index.tsx             # Application entry point
├── backend/                      # Backend application (JavaScript)
│   ├── controllers/              # API controllers
│   ├── models/                   # MongoDB models
│   ├── routes/                   # Express.js routes
│   ├── utils/                    # Utility functions
│   ├── server.js                 # Application entry point
│   └── config/                   # Database and environment configurations
├── database/                     # MongoDB database configurations
├── README.md                     # Project documentation
├── package.json                  # Dependency manager file
└── tsconfig.json                 # TypeScript configuration file
```

---

## 🛠️ Technologies Used

### Frontend:
- **TypeScript**
- **React.js**
- **CSS Modules**

### Backend:
- **Node.js**
- **Express.js**
- **JavaScript**

### Database:
- **MongoDB**

---

## 🛠️ Setup and Installation

### Prerequisites
Ensure the following are installed on your system:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/chat-music-app.git
   cd chat-music-app
   ```

2. **Install dependencies**:
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```
   - For the backend:
     ```bash
     cd backend
     npm install
     ```

3. **Set up environment variables**:
   - Create a `.env` file in the `backend/` directory and include:
     ```env
     MONGO_URI=your-mongodb-uri
     PORT=5000
     JWT_SECRET=your-jwt-secret
     ```

4. **Start the development servers**:
   - Backend:
     ```bash
     cd backend
     npm start
     ```
   - Frontend:
     ```bash
     cd frontend
     npm start
     ```

5. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## 📈 Features in Progress

- **Video Chat Integration**
- **Advanced Music Recommendations**
- **PWA (Progressive Web Application)** Support
- **Dark Mode Toggle**

---

## 🤝 Contributions

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

---

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙌 Acknowledgments

Special thanks to the open-source community for providing tools and libraries that made this project possible.

---

## 📞 Contact

For any inquiries, feel free to contact:
- **Author**: [V R N S NIKHIL](https://github.com/Nikhil6524)
- **Email**: bl.en.u4aie22062@bl.students.amrita.edu

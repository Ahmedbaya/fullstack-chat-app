# Fullstack Chat App

A real-time chat application built with modern web technologies, featuring authentication, user-friendly UI, and seamless communication. This project is designed to demonstrate a full-stack implementation of a chat app.

## Features

- **Real-Time Communication**: Instant messaging powered by WebSocket.
- **Authentication**: Secure user registration and login functionality.
- **Responsive Design**: Mobile-friendly and optimized for various screen sizes.
- **User Profiles**: Each user has a customizable profile.
- **Group Chats**: Create and participate in group conversations.

## Tech Stack

### Frontend:
- **React**: For building the user interface.
- **Tailwind CSS**: For styling and responsive design.
- **DaisyUI**: For pre-styled UI components.
- **Axios**: For handling HTTP requests.

### Backend:
- **Node.js**: For server-side development.
- **Express**: For building RESTful APIs.
- **Socket.IO**: For real-time communication.
- **MongoDB**: For storing user and chat data.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- Node.js (v14 or higher)
- MongoDB (local or cloud-based)
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ahmedbaya/fullstack-chat-app.git
   cd fullstack-chat-app
   ```

2. Install dependencies:
   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add the following keys:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     SOCKET_PORT=port_number
     ```

4. Run the application:
   ```bash
   # Start backend server
   cd backend
   npm start

   # Start frontend development server
   cd ../frontend
   npm start
   ```

5. Open the application in your browser at `http://localhost:3000`.

## Deployment

The production version of this app is hosted at:
[Production Link] https://chatty-7p4a.onrender.com/login

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, feel free to reach out:
- **GitHub**: [Ahmedbaya](https://github.com/Ahmedbaya)

---

Happy coding! 🎉


# Simple Chatroom Website

A real-time chatroom application where users can join chatrooms, interact with others, and exchange messages seamlessly.

---

## Features

### 1. User Authentication
- Users can log into the chatroom by providing a name.
- No need for complex signup; instant access with a unique name.

### 2. Room Selection
- Users can choose a room to join from a list of available rooms.
- A user can switch between rooms.

### 3. Room Details
- Users can see:
  - The total number of participants in the room.
  - A list of all users currently in the room.

### 4. Messaging Features
- **Old Messages**: Users can view message history for the room when they join.
- **Real-Time Messaging**: Users can send new messages, which are instantly visible to all participants in the room.
- Messages show:
  - Sender's name.
  - Timestamp of the message.

### 5. Responsive Design
- Accessible and easy to use on both desktop and mobile devices.

---
![chatroom] 

## Technology Stack

### **Frontend**
- **React.js**: For building the user interface.
- **CSS (TailwindCSS/Plain CSS)**: For styling the application.

### **Backend**
- **Express.js**: A lightweight web framework for building APIs.

### **Real-Time Communication**
- **Socket.IO**: For handling real-time communication between clients and the server.

### **Database**
- **MongoDB** (or other DB): To store old messages persistently.

---


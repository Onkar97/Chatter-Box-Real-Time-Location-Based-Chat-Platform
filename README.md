# Chatter Box – Real-Time Location-Based Chat Platform

Chatter Box is a real-time chat application built with **Node.js** and **Socket.io**. It supports chat rooms, user presence, message timestamps, and location sharing via the browser's geolocation API.

## Features
- **Live Messaging** with Socket.io (rooms, join/leave notifications, timestamps)
- **Location Sharing** to broadcast a user's coordinates into the room
- **User Management** (join/leave, active user list) via utility helpers
- **Static Front-End** served from `/public` with chat UI and room join page

## Tech Stack
- **Backend:** Node.js, Express, Socket.io
- **Frontend:** HTML, CSS, Vanilla JS
- **Package Dependencies:** bad-words, express, socket.io

## Getting Started
```bash
# Install dependencies
npm install

# Start the server (default port 3000)
npm start
# or
node src/index.js
```

Then open: `http://localhost:3000`

## Project Structure
```
public/
  index.html
  chat.html
  css/
  js/chat.js
src/
  index.js            # Express + Socket.io server
  utils/messages.js   # message formatting (timestamps, text/location)
  utils/users.js      # user join/leave, getUser(s)
```

## Environment
- Node.js 16+ recommended


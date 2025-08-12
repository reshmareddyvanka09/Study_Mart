ad# StudyMart – Academic Exchange Platform

**StudyMart** addresses the lack of a reliable, structured way for students to exchange academic resources. It enables peer-to-peer sharing, real-time communication, and trusted interactions within a secure academic network.

## Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Installation](#installation)  
4. [Usage Workflow](#usage-workflow)  
5. [Future Improvements](#future-improvements)  

## Features

- Domain-based sign up/login  
- Profile personalization with avatar and bio  
- Upload and share academic materials  
- Request and approve materials from peers  
- Rate received content and users  
- Real-time one-on-one chat using Socket.IO  
- Animated and responsive UI using TailwindCSS and Lottie  
- Role-based content visibility (e.g. course, year, branch)



## Tech Stack

**Client:** React, TailwindCSS, Lottie Animations

**Server:** Node.js, Express.js  

**Real-time Messaging:** Socket.IO  

**Database:** MongoDB  

**Authentication:** JWT, Email Domain Filtering  


## Installation

1. Clone the repo
```bash
  git clone 
  cd StudyMart
```

2. Set up environment variables
- In root of server
```bash
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-secret>
PORT:3000
```    
- In root of client
```bash
VITE_API_BASE_URL=http://localhost:3000/api/
VITE_API_SOCKET_URL=http://localhost:3000/
```

3. In split terminals
```bash
    cd server
    npm install
    nodemon server.js
```
```bash
    cd client
    npm install
    npm run dev
```

## Usage Workflow

### Students

- Sign up using institution email (domain restricted)  
- Complete profile with avatar and course details  
- Upload study materials or Request materials from peers  
- Chat in real-time with the requested peer
- Approve or reject requests  
- Rate the content and its sharer  
## Future Improvements

- Email notifications for request approvals  
- Multiple images support 
- Material versioning or updates  
- Group chat or discussion forums  
- Admin dashboard for analytics and moderation  
- AI-powered content suggestions


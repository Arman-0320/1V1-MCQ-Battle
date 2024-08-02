# 1v1 MCQ Battle Arena

## Introduction

The MCQ Battle App is an engaging and interactive mobile application designed to provide users with a competitive and educational platform for multiple-choice questions (MCQs). This app aims to enhance learning through gamification, allowing users to test their knowledge, challenge friends, and climb the leaderboard while enjoying a fun and stimulating experience.

## Features

- Real-time MCQ battles
- authentication and validation
- CRUD operations for APIs.
- Game lobby system for managing sessions and real-time user interactions
- User-friendly UI using React and CSS.

## Technologies Used

- **Backend:** Django, Django REST Framework, djangorestframework-simplejwt, SQLite (or other SQL database)
- **Frontend:** React, CSS
- **Real-time Communication:** Pusher WebSockets
  

## Setup Instructions

### Prerequisites

- Python 3.x
- Node.js
- npm or yarn
- Pusher account for WebSockets

## Usage

1. **Register a New User:**
   - Visit: [http://127.0.0.1:8000/register](http://127.0.0.1:8000/register)

2. **Login:**
   - Visit: [http://127.0.0.1:8000/login](http://127.0.0.1:8000/login)
   - Use your registered credentials to log in.

3. **Access the Game Lobby:**
   - Start a real-time MCQ battle after logging in.

### API Endpoints

#### Authentication

- **Register a New User:**
  - `POST /register`

- **Login and Obtain JWT Tokens:**
  - `POST /login`

#### MCQ Management

- **List All MCQs:**
  - `GET /mcqs`

- **Create a New MCQ:**
  - `POST /mcqs`

- **Retrieve a Specific MCQ:**
  - `GET /mcqs/<uuid:pk>`

- **Update a Specific MCQ:**
  - `PUT /mcqs/<uuid:pk>`

- **Delete a Specific MCQ:**
  - `DELETE /mcqs/<uuid:pk>`

#### Protected View (Optional)

- **Access a Protected View:**
  - `GET /protected`




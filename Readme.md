
- [Model link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj?origin=share)

# Video Hoster

## Overview
This project is a backend service for hosting and managing videos. It includes functionalities such as uploading videos, user authentication, and video streaming.

## Key Sections

### Routes
- **Video Routes**: Handles video upload, retrieval, and deletion.
  - File: `routes/videoRoutes.js`
  - Example Endpoint: `POST /videos/upload`

### Middlewares
- **Authentication Middleware**: Ensures that only authenticated users can access certain endpoints.
  - File: `middleware/auth.js`
  - Purpose: Checks for valid JWT token.

### Models
- **Video Model**: Defines the schema for video documents in MongoDB.
  - File: `models/Video.js`
  - Key Fields: `title`, `description`, `url`, `user`

### Utilities
- **Date Formatter**: Provides utility functions for date formatting.
  - File: `utils/formatDate.js`
  - Example Function: `formatDate(date)`

## Setup and Run
1. Clone the repository:
   ```sh
   git clone https://github.com/sharmaanikhil/Video_Hoster.git


# Summary of this project

This project is a complex backend project that is built with nodejs, expressjs, mongodb, mongoose, jwt, bcrypt, and many more. This project is a complete backend project that has all the features that a backend project should have. Building a complete backend for video hosting website similar to youtube with all the features like login, signup, upload video, like, dislike, comment, reply, subscribe, unsubscribe, and many more.

Project uses all standard practices like JWT, bcrypt, access tokens, refresh Tokens and many more. I have spent a lot of time in building this project.


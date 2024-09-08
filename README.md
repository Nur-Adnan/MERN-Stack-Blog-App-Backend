# MERN Stack Blog Application

A full-featured blog platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This application enables users to explore and publish blogs, with a range of features designed for an engaging user experience.

## Table of Contents
- [Features](#features)
  - [User Features](#user-features)
  - [Admin Features](#admin-features)
  - [Search Functionality](#search-functionality)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Screenshots](#screenshots)
- [License](#license)

## Features

### User Features
- **Browse Blogs Without Login**: Users can view blogs without needing to sign up or log in.
- **User Authentication**: Users can sign up using their email or Google account. Google integration offers a faster, more seamless login experience.
- **Blog Creation**: Once signed up, users can create and publish their own blogs with:
  - Blog banner images
  - Titles and subtitles
  - Rich text formatting (headings, lists, quotes)
  - Inline image uploads
  - Paragraph reordering
  - Tags for easier search and categorization
- **Dark Mode & Light Mode**: Toggle between dark and light mode for better accessibility and user customization.
- **User Engagement**: Users can leave comments, react to posts with a "love" emoticon, and track the number of reactions received on their own blogs.
- **Notifications**: Authors are notified of comments and reactions on their blogs.
- **Profile Management**: Users can update their profile picture, username, password, bio, and social media links. Password updates are also supported.

### Admin Features
- **Blog Management**: Admins can moderate and manage blogs, including removing inappropriate content if needed.

### Search Functionality
- **Search**: Users can search for blogs by specific words or tags, ensuring they find content that interests them.

## Tech Stack
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Google OAuth2.0, JWT
- **UI/UX Enhancements**: Dark/Light mode, notifications, real-time updates

## Setup and Installation

### Prerequisites
- Node.js and npm installed
- MongoDB instance running locally or on a cloud provider (e.g., MongoDB Atlas)

### Installation

1. Install client-side dependencies:
    ```bash
    git clone https://github.com/Nur-Adnan/MERN-Stack-Blog-App-Frontend.git
    npm install
    ```

3. Install server-side dependencies:
    ```bash
    git clone https://github.com/Nur-Adnan/MERN-Stack-Blog-App-Backend.git
    npm install
    ```

4. Create a `.env` file in the `server` folder with the following variables:
    ```bash
    DB_LOCATION=your-mongodb-connection-string
    SECRET_ACCESS_KEY=your-secret-access-key
    CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
    CLOUDINARY_API_KEY=your-cloudinary-api-key
    CLOUDINARY_API_SECRET=your-cloudinary-api-secret
    ```

5. Create a `.env` file in the `client` folder with the following variables:
    ```bash
    VITE_SERVER_DOMAIN=your-server-domain-url
    VITE_FIREBASE_KEY=your-firebase-api-key
    VITE_AUTH_DOMAIN=your-auth-domain
    VITE_PROJECT_ID=your-project-id
    VITE_STORAGE_BUCKET=your-storage-bucket
    VITE_MESSAGING_SENDER_ID=your-messaging-sender-id
    VITE_APP_ID=your-app-id
    ```

6. Start the development servers:
    - For the backend:
      ```bash
      npm run dev
      ```

    - For the frontend:
      ```bash
      npm run dev
      ```

## Screenshots

![image](https://github.com/user-attachments/assets/0ad0dd10-ad11-449b-81eb-0797243e83c8)
![image](https://github.com/user-attachments/assets/efaaadc5-9c46-4780-947a-716e28d68da0)
![image](https://github.com/user-attachments/assets/7088cde3-045f-41c3-b3f3-9b6480ed0f5a)
![image](https://github.com/user-attachments/assets/26b8880e-054b-4538-9b3c-a09d95268a26)
![image](https://github.com/user-attachments/assets/79b2e4cb-c8f3-4a67-9a16-8ffef7de2b77)
![image](https://github.com/user-attachments/assets/75e5a710-8000-4461-898e-1b2d4b3463eb)
![image](https://github.com/user-attachments/assets/cfa0f284-1c88-49db-833b-e6216c599930)
![image](https://github.com/user-attachments/assets/2ec17eff-805a-4d89-a0ee-0fa7903cc06d)
![image](https://github.com/user-attachments/assets/61c678d6-102c-456c-bf5e-710e1bc425c5)
![image](https://github.com/user-attachments/assets/31708695-d7a6-4dca-9378-d8976a74cd07)
![image](https://github.com/user-attachments/assets/d9c7d2c1-6dbf-4309-90b9-6fc40d0dccd7)
![image](https://github.com/user-attachments/assets/16a6b725-5bba-4e0e-aa30-899b9db03199)
![image](https://github.com/user-attachments/assets/43ea1bb4-2fe0-4270-b13c-ff930a0e9129)

## License
This project is licensed under the MIT License.

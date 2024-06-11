# Blog-Tech

Welcome to Blog-App! This project is a full-stack web application built using the MERN stack – MongoDB, Express.js, React.js, and Node.js. It provides a platform for users to create, read, update, and delete blog posts.

## Features

- **User Authentication:** Secure sign-up, login, and logout functionality.
- **Create and Manage Posts:** Authenticated users can create, edit, and delete their blog posts.
- **Browse and Engage:** Visitors can browse existing blog posts, read content, and interact via comments.
- **Responsive Design:** Ensures seamless experience across devices of all sizes.

## Tech Stack

- **Frontend:** React.js, React Query
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Media Storage:** Cloudinary
- **Authentication:** JSON Web Tokens (JWT)
- **Styling:** Tailwind CSS, ShadCn

## Getting Started

To start with this project, follow these steps:

1. **Clone Repository:** Clone this repository to your local machine.
2. **Install Dependencies:** Navigate to the project directory and install dependencies using `npm install`.
3. **Set up MongoDB:** Set up your MongoDB database and obtain the connection string.
4. **Configure Environment Variables:**

   - **Frontend:**
     - `VITE_BASE_URL`: Backend server link

   - **Backend:**
     - `PORT`: Port number for the server
     - `ACCESS_SECRET_KEY`: User-defined access secret key
     - `CLOUD_NAME`: Cloudinary Cloud name
     - `CLOUD_API`: Cloudinary API
     - `CLOUD_API_SECRET`: Cloudinary API secret
     - `USER_IMAGE`: User image directory (Frontend link + `/user.jpeg`)
     - `URI`: MongoDB URI address

5. **Run Backend Server:** Execute `npm run dev` in the `/server` directory.
6. **Run Frontend Development Server:** Execute `npm run dev` in the `/client` directory.
7. **Access Application:** Open your browser and go to `http://localhost:5173`.


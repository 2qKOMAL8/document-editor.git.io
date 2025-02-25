# document-editor.git.io
RealTimeEdify is a real-time collaborative document editing web application built using the MERN stack (MongoDB, Express.js, React, Node.js), Socket.IO for real-time communication, and Quill as the text editor.
![image alt](https://github.com/2qKOMAL8/document-editor.git.io/blob/main/m1.png?raw=true)
![image alt](https://github.com/2qKOMAL8/document-editor.git.io/blob/main/m2.png?raw=true)
![image alt](https://github.com/2qKOMAL8/document-editor.git.io/blob/main/Screenshot%202025-02-25%20081330.png?raw=true)

- Getting Started

Follow these steps to run Document-editer locally:

1. Clone the repository:

git clone https://github.com/2qKOMAL8/document-editor.git.io.git

2. Install dependencies for frontend:

   cd src
   
   cd client
   
   npm i
   
4. Install dependencies for backend:
   
   cd src
   
   npm i
   
6. Set up .env variables by creating a .env file in the server directory and adding the following variables:
   
-For server side:

 MONGODB_URI=your_mongo_db_uri
 
 JWT_SECRET=your_jwt_secret
 
 PORT=8000
 
 PASSWORD=your_app_password_for_email
 
 EMAIL=your_gmail_email
 
 BACKEND_URL=your_backend_url/api/v1
 
 FRONTEND_URL=your_frontend_url
 
 PRODUCTION=false
 
Replace your_mongodb_connection_string, your_jwt_secret, your_email_username, your_email_password, your_email_host, and your_email_port with your own values.

Note: If you are using Gmail for sending emails, you need to enable "Less secure app access" in your Google account settings.

For client side:
 VITE_APP_BACKEND_URL=your_backend_url/api/v1
 VITE_APP_SOCKET_URL=your_backend_url
Replace your_backend_url with the URL where the backend server is running.

5. Run the frontend
 
    cd src

    cd client
  
    npm run dev

8. Run the backend
   
    cd src
  
    npm run dev
  
10. Access the application in your browser at http://localhost:5173.

11. Create an account and start collaborating on documents!

# Spotify

## Prerequisites

Before you begin, ensure that you have the following installed on your system:

- **Node.js** (version 12 or higher)
- **npm** (Node Package Manager) or **yarn**

## Installation

1. **Clone the repository** to your local machine using the following command:

    ```bash
    git clone [repository-url](https://github.com/sanskriti0606/Spotify06)
    ```

3. **Install the dependencies** by running either of the following commands:

    - Using npm:
          npm install
      ```

    - Using yarn:
yarn install
Configuration

Running the Application
To start the development server, run the following command:

Make sure to set the necessary environment variables in your deployment environment to match the configurations mentioned in the .env file.

**bash**
Copy code
NEXT_PUBLIC_API_BASE_URL=(https://spotifyy-jkai.onrender.com/)/api
Start the development server:

**yarn dev**
npm run dev
Access the app at http://localhost:3000.

Usage

**Login: /login**
**Signup: /signup**
Playlists: Manage playlists

## Backend

**Features**

User authentication (login, signup)

CRUD operations for playlists

Integration with MongoDB

**Technologies**

Node.js: JavaScript runtime for server-side

Express: Web application framework

MongoDB: NoSQL database

Mongoose: ODM for MongoDB

JWT: JSON Web Tokens for authentication

bash
Copy code
MONGO_URI=mongodb://localhost:27017/spotify-app
JWT_SECRET=your_jwt_secret
PORT=8081

**API Endpoints**

POST /api/login: Authenticate a user

POST /api/users: Register a new user

GET /api/playlists: Get all playlists

POST /api/playlists: Create a new playlist

PUT /api/playlists/

## API Documentation : 
**https://documenter.getpostman.com/view/37832607/2sAXjSyoKV**

**Deployement Link** : https://spotify-app-inky.vercel.app/

**Contributing**
Fork the repository.
Create a new branch: git checkout -b feature/your-feature.
Commit your changes: git commit -am 'Add new feature'.
Push to the branch: git push origin feature/your-feature.
Create a Pull Request.

**License**
Licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**
Inspired by Spotify
Thanks to Next.js, Tailwind CSS, MongoDB, Express, and Mongoose for their powerful tools.
Feel free to adjust the URLs and any specific details as necessary for your project.

![image](https://github.com/user-attachments/assets/dd769b0d-788f-4bae-9ac9-d3ec050a9d06)
![image](https://github.com/user-attachments/assets/b1326e35-4ee7-4ae1-a096-624f3a555d4c)
![image](https://github.com/user-attachments/assets/905de550-b348-46da-ab90-eb341aeb5ebc)
![image](https://github.com/user-attachments/assets/0458ff98-a72a-44c2-aab0-dd19acafe11e)





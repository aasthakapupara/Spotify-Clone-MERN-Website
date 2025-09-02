# Spotify Clone

A fully functional Spotify clone built with React, Node.js, Express.js and MongoDB. This project aims to replicate the core functionalities of Spotify, allowing users to browse albums, play songs, and manage playback. 
It includes functionalities for creating, browsing, and removing albums, as well as uploading, viewing, and deleting songs.

##✨ Features

- **Album Management**: Create, list, and delete albums.
- **Song Management**: Upload, list, and delete songs.
- **Play Music**: Users can play, pause, and skip tracks.
- **Responsive Design**: Mobile-friendly design for better accessibility.

##🛠️ Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Cloud Storage**: Cloudinary for image and song storage
- **Tools:** Git, Vite, VSCode
- **State Management**: Context API
- **Other Libraries**: Axios, React Router, React Toastify

##🚀 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/aasthakapupara/Spotify-Clone-MERN-Website.git
    cd Spotify-Clone-MERN-Website
    ```

2. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```plaintext
    MONGO_URI=your_mongodb_uri
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```

3. Run the backend server:
    ```bash
    cd spotify-backend
    npm install
    npm start
    ```
4. Run the backend server:
    ```bash
    cd spotify-admin
    npm install
    npm run dev
    ```

5. Run the frontend:
    ```bash
    cd spotify-frontend
    npm install
    npm run dev
    ```

##🎧 Usage

1. Open your browser and navigate to `http://localhost:5173`.
2. Create new albums and songs on the Spotify Admin page.
3. Browse albums and songs, create playlists, and enjoy music.

##📷 Screenshot

### Admin Add Song Page
<img width="1919" height="963" alt="image" src="https://github.com/user-attachments/assets/a7cf35d5-f7d8-45d9-a3e4-d3c035c10d29" />

### Admin Song List Page
<img width="1919" height="959" alt="image" src="https://github.com/user-attachments/assets/dbf7b11b-fe5a-498e-86d2-df9dc003368e" />

### Home Page
<img width="1919" height="966" alt="image" src="https://github.com/user-attachments/assets/5d4c68fd-1034-4278-91b7-fe9aed8fdf4a" />

### Album Page
<img width="1917" height="966" alt="image" src="https://github.com/user-attachments/assets/e25cbf64-75e6-4a85-a553-6a267791e5e3" />

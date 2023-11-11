
# ConvoSphere

ConvoSphere is a real-time discord clone built using MERN stack, WebRTC, and Socket.IO. 


## Features


- Authentication using JWT
- Create separate voice rooms and chat in real-time with other users
- Video calling , voice calling , screensharing using WebRTC
- Audio only mode
- Friend Adding Functionality
- Easy to use UI

## Tech Stack

- MongoDB
- Express
- React
- Node.js
- WebRTC
- Socket.IO

## Getting Started

### Prerequisites

- Node.js


### Installation

1. Install NPM packages
    ```
    npm install
    ```
2. Add the following environment variables in .env file

    ```
    MONGO_URI= your mongo uri here 
    TOKEN_KEY= your token key here
    ```
3. Start the server side
    ```
    cd discord-backend
    npm start
    ```
4. Start the client side
    ```
    cd discord-frontend
    npm start
    ```

## Screenshots

- Registration Page
<img width="1512" alt="Screenshot 2023-11-11 at 12 13 49 PM" src="https://github.com/DhavalMavani/discord/assets/61201815/06422d67-43f9-4357-8d76-3aaae3dbb17a">

![Create Account](https://user-images.githubusercontent.com/126965816/233789208-127b5968-6f24-4438-a450-47f29338e2c8.png)

- Friend adding functionality

![add friend](https://user-images.githubusercontent.com/126965816/233789287-029339b3-4e2d-4fa6-bfd7-36febc8cc384.png)

- Chat functionality

![homepage frnd request](https://user-images.githubusercontent.com/126965816/233789316-7bc4d50d-ec38-4da1-96f2-0629365f7bbf.png)

- Video room creation and screenshare functionality

![video room creation](https://user-images.githubusercontent.com/126965816/233789377-d03fbb26-a158-429f-9891-846097e87c37.png)

![screenshare functionality](https://user-images.githubusercontent.com/126965816/233789398-37de7dfb-eca5-4f6d-ada0-e12aa95ba86b.png)

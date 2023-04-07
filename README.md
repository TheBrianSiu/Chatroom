# Chatroom
A simple chatroom web application built using React and Socket.IO.

## Features
Real-time chat with multiple users
Create and join chat rooms
See active users in each chat room
View chat history
### Technologies Used
* React
* Socket.IO
* Node.js
* Express.js
* Axios
* HarperDB

## Features
Users can join a chat room with a unique room code
Users can send and receive real-time messages in the chat room
Users can see the list of active users in the chat room
Users can leave the chat room

## Getting Started
To get started with the Chatroom, follow these steps:

##Clone the repository:

```bash
git clone https://github.com/TheBrianSiu/Chatroom.git
```

Install the dependencies for the client and server:
```bash
cd Chatroom/client
npm install
```

```bash
cd ../server
npm install
```

## Set up your HarperDB instance:
Sign up for a free account on HarperDB Cloud.

Create a new database called realtime_chat_app.

Create a new schema in the database called public.

Create a new table in the schema called messages with the following columns:

* id (string, primary key)
* room (string)
* username (string)
* message (string)
* timestamp (integer)
Create a .env file in the server directory with the following content:
``` bash
HARPERDB_URL=<your_harperdb_instance_url>
HARPERDB_PW=<your_harperdb_instance_password>
Replace <your_harperdb_instance_url> and <your_harperdb_instance_password> with the URL and password for your HarperDB instance.
```

### Start the server:
```bash
cd server
npm start
```

### Start the client:
```bash
cd ../client
npm start
```

Open your web browser and navigate to http://localhost:3000 to start using the Chatroom.
License
The Chatroom is licensed under the MIT License. See LICENSE for more information.

## Contact
If you have any questions or comments about the Chatroom, please feel free to contact us me.

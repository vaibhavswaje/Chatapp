
# Talk-A-Tive

Talk-a-tive is a Full Stack Chatting App.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.
## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB
  
## Demo

https://talk-a-tive.herokuapp.com/

![](https://github.com/piyush-eon/mern-chat-app/blob/master/screenshots/group%20%2B%20notif.PNG)
## Run Locally

Clone the project

```bash
  git clone https://github.com/piyush-eon/mern-chat-app
```

Go to the project directory

```bash
  cd mern-chat-app
```

Install dependencies

```bash
  npm install
```

```bash
  cd frontend/
  npm install
```

Start the server

```bash
  npm run start
```
Start the Client

```bash
  //open now terminal
  cd frontend
  npm start
```

  
# Features

### Authenticaton
Users can register and log in securely using their credentials.
Passwords are stored securely using encryption techniques.
JWT (JSON Web Tokens) are used for token-based authentication
### Real Time Chatting with Typing indicators
Chat messages are sent and received in real time using Socket.io.
Typing indicators show when a user is typing a message.
Instant updates ensure a smooth and responsive chat experience.
### One to One chat
Users can initiate one-on-one conversations with other users.
Private messages are displayed in separate chat threads.
Real-time updates keep conversations up to date.
### Search Users
Users can search for other registered users by their usernames.
The search feature enables users to quickly find and start conversations.
### Create Group Chats
Users can create group chats by selecting multiple participants.
Group chats provide a platform for collaborative discussions.
Group names and participant lists can be customized.
### Notifications 
Users receive notifications for new messages, even when the app is not active.
Unread message counts are displayed alongside chats.
Notifications enhance user engagement and keep them informed.
### Add or Remove users from group
Group chat creators can add or remove participants.
This feature allows easy management of group members.
Group members are instantly updated about additions/removals.
### View Other user Profile
Users can view the profile of other users.
Profiles might include usernames, avatars, and status information.
Enhances user interactions by providing context about chat participants.
These features collectively create a dynamic and engaging chat application that enables users to communicate effectively in various scenarios.








  

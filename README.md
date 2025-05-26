# ChatterBox - Omegle Clone

ChatterBox is a web application that allows users to chat with random strangers through text and video, similar to Omegle.

## Features

- Random matching with other online users
- Text chat functionality
- Video chat with WebRTC
- Ability to skip to the next user
- Toggle video and audio during video chats

## Technologies Used

- **Frontend**: React with Styled Components
- **Backend**: Node.js and Express
- **Real-time Communication**: Socket.io
- **Video Chat**: WebRTC for peer-to-peer video communication

## Installation

1. Clone the repository:
```
git clone <repository-url>
cd chatterbox
```

2. Install all dependencies (server and client):
```
npm run install-all
```

3. Start the development servers (both client and server):
```
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

### Network Access

To make ChatterBox accessible to other devices on your local network:

1. Run the network script:
```
npm run network
```

2. The script will display your local IP addresses
3. Other devices on the same network can access the app at:
```
http://<your-local-ip>:3000
```

## Project Structure

- `/server` - Backend Node.js/Express server with Socket.io
- `/client` - React frontend application

## Available Scripts

- `npm start` - Starts the server only
- `npm run server` - Starts the server with nodemon (auto-restart)
- `npm run client` - Starts the React development server
- `npm run dev` - Runs both server and client concurrently (localhost only)
- `npm run network` - Runs both server and client for network access
- `npm run build` - Builds the React app for production
- `npm run install-all` - Installs dependencies for both server and client
- `npm run find-ip` - Displays your local IP addresses for network access

## How to Use

1. Choose between text chat or video chat mode
2. Wait to be matched with another user
3. Start chatting!
4. Click "Skip" to end the current chat and find a new partner
5. During video chats, you can toggle your video and audio using the buttons provided

## Production Deployment

For production deployment:

1. Build the React app:
```
npm run build
```

2. Set the environment variable `NODE_ENV=production`
3. Start the server:
```
npm start
```

## Notes

- For video chat to work properly, you need to allow camera and microphone permissions in your browser
- For production deployment, consider adding TURN servers to improve WebRTC connectivity behind NATs and firewalls
- This application is for educational purposes only

## License

MIT# CHATTER_BOX-zen-
# CHATTER_BOX-zen-

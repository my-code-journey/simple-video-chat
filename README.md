# Video Chat with WebRTC and Firebase



WebRTC facilities realtime audio/video communication on the web using a peer-to-peer protocol, allowing you to build apps like Zoom, Skype, etc.

The following builds a 1-to-1 video chat, where each peer streams directly to the other peer - there is no need for a middle-man server to handle video content. However, a 3rd party server is required for signaling that stores shared data for stream negotiation. Firestore is an excellent choice for WebRTC because it is easy to listen to updates to the database in realtime.

## Usage

installation
```
git clone <this-repo>
npm install

npm run dev
```

Update the firebase project config in the main.js file. 
```
const firebaseConfig = {
    // your config
};
```

start
```
npm run dev
```

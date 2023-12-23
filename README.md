# UpForCoffee Web App

Welcome to the UpForCoffee Web App – a platform designed for students to connect and build meaningful relationships on campus. Discover the features of this web application and get ready to join a community that values authentic connections and shared stories.

## Table of Contents
- [Features](#features)
- [Navigation](#navigation)
- [Animation](#animation)
- [Firebase Integration](#firebase-integration)

## Features
1. **Smooth Form Submission:** Submit your details seamlessly with the provided form to pre-register for UpForCoffee.
2. **Dynamic Element Movement:** Experience dynamic movement of elements on the page, adding a visually appealing touch to the web app.
3. **Navigation Menu:** Convenient navigation menu to explore different sections of the web app effortlessly.

## Navigation
Easily navigate through the web app with the responsive navigation menu. Toggle the menu using the navigation icon and explore various sections, including Home, About, Features, and Join Us.

## Animation
Engage with a visually appealing and interactive interface. Elements on the page are animated, creating an enjoyable user experience. The navigation menu and content sections gracefully appear on the screen.

## Firebase Integration
UpForCoffee Web App integrates with Firebase to store user information securely. When users submit their details through the form, the data is saved to the Firebase Realtime Database for further processing.

### Firebase Configuration
```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  databaseURL: "your-database-url",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-messaging-sender-id",
  appId: "your-app-id",
  measurementId: "your-measurement-id"
};

firebase.initializeApp(firebaseConfig);
```

### Firebase Database Reference
```javascript
const joinUsFormDB = firebase.database().ref("joinUsForm");
```

---
Feel free to explore the UpForCoffee Web App and pre-register to be part of a vibrant student community.
*UpForCoffee - Connecting Students, Fostering Friendships.*

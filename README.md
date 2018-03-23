firebase-auth
=======
Simple web application to generate firebase token


Prerequisite
-----
Make changes to `public/index.html`
```javascript
var config = {
    apiKey: "<API_KEY>",
    authDomain: "<PROJECT_ID>.firebaseapp.com",
    databaseURL: "https://<DATABASE_NAME>.firebaseio.com",
    storageBucket: "<BUCKET>.appspot.com",
    messagingSenderId: "<SENDER_ID>",
  };
```

How to Deploy
-----
Setup Hosting
- Install firebase command line tools using npm.
  - `$npm install -g firebase-tools`
- Sign in to Google:
  - `$ firebase login`
  
Development Environment
- `$ firebase serve`

Production Environment
- `$ firebase deploy`
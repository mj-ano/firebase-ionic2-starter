This is a starter template for [Ionic](http://ionicframework.com/docs/) with [Firebase](https://firebase.google.com).

## How to use this template

To use this template, clone this repository into your system.

### With CLI:

The first thing you’ll do is to make sure you have node.js installed, get V6.

The second thing you’ll do is make sure you have Ionic, Cordova and Typescript installed, you’ll do that by opening your terminal and typing:

```bash
$ sudo npm install -g ionic cordova typescript
```

Then, to run it, cd into `firebase-ionic2-starter` and update firebaseConfig from firebase website for web in  

```bash
/src/app/app.module.ts
 ```
 
 ```js
export const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  storageBucket: "",
  messagingSenderId: ""
};
 ```
Then, run below commands : 

```bash
$ npm install
$ ionic serve --lab
```

To add Android & ios support read more in Ionic website.

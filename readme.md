# Firebase

In many cases, new features and bug fixes are available only with the latest version of the Firebase CLI and the firebase-functions SDK. It's a good practice to frequently update both the Firebase CLI and the SDK with these commands inside the functions folder of your Firebase project:

```
npm install firebase-functions@latest firebase-admin@latest --save
npm install -g firebase-tools
```

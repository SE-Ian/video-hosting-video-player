#  🚀recapio


Recapio is a Next.js application with a fully functional authentication system using Firebase v9, Typescript, React, ChakraUI & Jotai.

# Features
- Firebase v9 for External provider Auth (Google) and Email/Password native providers
- Sign-in with Google
- Sign-in with Email/Password
- Confirm password
- Password strength protections
- Ability to view the password in plaintext
- "Forgot your password?" Flow
- Sign-out
- Styling with ChakraUI
- Global state management for the Auth modal with Jotai

# Getting Started
1. Clone this repo and install the dependencies

```
npm install
#or
yarn install
```

2. Create a new project in [Firebase](https://firebase.google.com/) and set it up for Firebase Auth.
3. Set the .env variables and set each variable with your own unique values from the config file.
4. Install the Firebase CLI
```
npm install -g firebase-tools
#or
yarn global add firebase-tools
```
5. Run the dev server
```
npm run dev
#or
yarn dev
```
6. Open [localhost](http://localhost:3000) and taaaddddaaaaaaaaaaa!

![Preview page](/public/images/page.png)

*View Live [here](https://recapioz.vercel.app/)*

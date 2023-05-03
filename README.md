# ChatGpt client

This is simple ChatGPT client using Flutter, Firebase and the ChatGPT API.

## Preview

<img src="https://github.com/ahmedalmubarak/ChatGpt-client/blob/main/chatgpt_flutter/assets/screen1.jpg?raw=true"  width="" height="500">

## Getting Started

This project contains 2 directories:

1. `chatgpt_flutter` - The Flutter client

2. `chatgpt_firebase` - The Firebase functions implanting using [Node.js](https://nodejs.org/) with typeScript

### Folders structure

    chatgpt_firebase
     ┣ functions
     ┃ ┣ src
     ┃ ┃ ┗ index.ts
     ┃ ┣ .env
     ┃ ┣ .eslintrc.js
     ┃ ┣ .gitignore
     ┃ ┣ package-lock.json
     ┃ ┣ package.json
     ┃ ┣ tsconfig.dev.json
     ┃ ┗ tsconfig.json
     ┣ .firebaserc
     ┣ .gitignore
     ┣ firebase.json
     ┣ firestore.indexes.json
     ┗ firestore.rules


    lib
     ┣ data
     ┃ ┣ chat_message.dart
     ┃ ┣ chat_message.freezed.dart
     ┃ ┣ chat_message.g.dart
     ┃ ┗ role.dart
     ┣ pages
     ┃ ┗ chat_page.dart
     ┣ providers
     ┃ ┗ messages_provider.dart
     ┣ services
     ┃ ┗ database_service.dart
     ┣ widgets
     ┃ ┣ chat_empty.dart
     ┃ ┣ chat_header.dart
     ┃ ┣ chat_message_item.dart
     ┃ ┗ chat_text_field.dart
     ┣ app.dart
     ┗ main.dart

### Pre-requisites

1. [Install the Flutter SDK](https://flutter.dev/docs/get-started/install)

2. Follow the instructions [here to install Firebase CLI](https://firebase.google.com/docs/cli#install_the_firebase_cli)

3. Install the FlutterFire CLI: `flutter pub global activate flutterfire_cli`

4. You will need a Firebase project. If you don't have one, create one [here](https://console.firebase.google.com/).

5. You will need a ChatGPT API key. If you don't have one, create one [here](http://chat.openai.com/auth/login).

6. Put your ChatGPT API key & organization ID in [`functions/.env`](./chatgpt_firebase/functions/.env).

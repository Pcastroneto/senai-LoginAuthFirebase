# senai-LoginAuthFirebase

### ExemploTabRoute

Aplicativo criado em React Native Expo com o recurso de Stack Navigation e Firebase Authentication

###COMANDOS PARA EXECUTAR ANTES DE INICIAR
```bash
npx expo install firebase
npm install @react-navigation/native @react-navigation/native-stack
npx expo install react-native-screens react-native-safe-area-context
```

```bash
npx expo customize metro.config.js
```
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
const firebaseConfig = {
  apiKey: "AIzaSyCAtctXHjFjnDyh12hdSecOumVdLPR6iUE",
  authDomain: "senai-auth-pcastroneto.firebaseapp.com",
  projectId: "senai-auth-pcastroneto",
  storageBucket: "senai-auth-pcastroneto.appspot.com",
  messagingSenderId: "818175914144",
  appId: "1:818175914144:web:44ccffc2d80b02c8a559c5"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);

# Steps for dev

## 1.Create an appwrite account

- create a new app - jsm_rn_movie_app

REF: https://www.youtube.com/watch?v=f8Z9JyB2EIE

## 2.Create empty folder 'REACT-NATIVE-APP'

## 3. Initialize an react native app, inside of the 'REACT-NATIVE-APP' folder

`npx create-expo-app@latest ./`

## 4. Setup a new Expo.dev account

## 5. Start the app. In project terminal, run

```
npx expo start
```

## 6. Scan QR code from console, view it via Expo Go app from mobile phone.

## 7. Reset to minimum

```
npm run reset-project
```

then start the app again.
- It does not work, crashing.
- Install dev client
```
npx expo install expo-dev-client
```
- Configure Expo development build
- Create app build using EAS (Expo Account)
    - Install EAS cli
        ```
        npm i -g eas-cli
        ```
    - Check install
        ```
        eas -v
        ```
    - eas login
        ```
        eas login
        ```
    - Check logged In user
        ```
        eas whoami
        ```
    - Check eas commands
        ```
        eas -h
        ```
    - Initialize an eas project
        ```
        eas init
        ```
    - Build the project
        ```
        eas build:configure
        ```
    





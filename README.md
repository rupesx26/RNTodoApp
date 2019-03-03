# RNTodoApp

Is my first react native app using Expo

you will find all info here https://expo.io/


# Setup

Go to https://facebook.github.io/react-native/docs/getting-started
you will find 2 methods to setup env for react native. Quick start and Building project with native code. I prefered quick start. 

Note:- your machine might lag while installing expo package if you have low configurations.

#Steps
1. Go to terminal and run npm install -g expo-cli
Note:- you may get error while "unhandle rejection error:- command failed: C:\Program Files\Git\cmd\git.EXE clone --depth=1..." etc and due to that "lottie-react" package get stuck. You can install maually with this "npm install lottie-react"

2. expo init YourProjectName
cd YourProjectName
npm start


Expo will create react-native boilerplate and run localhost:19002

[if you don't have android or ios simulater]

download expo in your device scan QR code and BOOM!


#Generate APK 
https://docs.expo.io/versions/latest/distribution/building-standalone-apps/

update in App.json

"ios": {
      "bundleIdentifier": "com.yourcompany.yourappname"
    },
    "android": {
      "package": "com.yourcompany.yourappname"
    }
    
  expo build:android or expo build:ios
  
  you will get apk download link!!!!
  
  Happy Coding :D







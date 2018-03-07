# React Native Web Starter

![Starting Point](docs/master.png)

### Introduction

This repo is intending to provide an easy starting point for developers looking to make fully cross platform applications across both web with [React Native Web](https://github.com/necolas/react-native-web) and mobile with [Expo](https://github.com/react-community/create-react-native-app).

It is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) so you can run `yarn web` in order to start up the development web server with all the hot reloading goodness you've come to expect.

It has then been integrated with [Create React Native App](https://github.com/react-community/create-react-native-app) and running `yarn ios` or `yarn android` will start the Expo packager. (You can also run the project from the Expo XDE program).

### Get Started
Clone the branch with the starting point you want and just rename the project, set a new upstream and you're good to go. 🙂

A full list of the scripts defined in `package.json` is shown below.

| Script              | Action                                                  |
|---------------------|---------------------------------------------------------|
| `yarn web`          | Start CRA Development Build                             |
| `yarn build-web`    | Create production build for web                         |
| `yarn eject-web`    | Eject from CRA                                          |
| `yarn start-native` | Start the Expo packager                                 |
| `yarn eject-native` | Eject from Expo                                         |
| `yarn android`      | Start expo packager and install app to Android Emulator |
| `yarn ios`          | Start expo packager and install app to iOS Simulator    |
| `yarn test-native`  | Run testing script for mobile app                       |
| `yarn test-web`     | Run testing script for web app                          |
| `yarn test`         | Run both testing scripts                                |


### Future Plans for this Library

The aim for this library is to make several branches that have different starting points i.e. Redux, Navigation, Auth etc.

Master branch will always be the most minimal starting point.

I'm also toying with the idea of doing a starting point with React Native CLI instead of Expo however that will mean the UI for mobile will less predictiable than developing with Expo.

#### Tasks
- Get jest working properly
- Redux starting point (no middleware just basic)

### Credit

- Huge thanks to [Nicolas Gallagher](https://github.com/necolas) for making React Native Web
- Thanks to [Expo](https://expo.io/) for making it so easy to get started with React Native development
- Thanks to [Yannick Spark](https://twitter.com/yannickdot) for writing [this great article](https://medium.com/@yannickdot/write-once-run-anywhere-with-create-react-native-app-and-react-native-web-ad40db63eed0) which inspired me to get started with React Native Web
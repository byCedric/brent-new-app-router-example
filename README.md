## expo-router@1.0.0-rc2 / React Native 0.71.1

This repo demonstrates integration of `expo-router` with a new React Native project generated with `npx react-native` init with `react-native@0.71.1`.

You can see the steps in each commit:

- [`d355d1e`](https://github.com/brentvatne/new-app-router-example/commit/d355d1ed328cab4af8a57f9aceda811707c9310d) → Initialize app with `npx react-native init`
- [`8c34cc2`](https://github.com/brentvatne/new-app-router-example/commit/8c34cc2675ae305805db5aee5b0dff6d1f605193) → Install Expo Modules API. This also changes entry point to `main`.
- [`c2ae28c`](https://github.com/brentvatne/new-app-router-example/commit/c2ae28c32f85b58dfb5583122c8fcd379c259345) → Install Expo Router and `react-native-gesture-handler`. See steps from [Expo Router docs](https://expo.github.io/router/docs/)
- [`9e40c09`](https://github.com/brentvatne/new-app-router-example/commit/9e40c09e326bcc45edfa6764a6e8b6032e06489d) → Replace **package.json** scripts `android` and `ios` to use Expo CLI. 

## How to run

- `$ git clone https://github.com/brentvatne/new-app-router-example.git`
- `$ yarn install`
- `$ yarn ios` or `$ yarn android`

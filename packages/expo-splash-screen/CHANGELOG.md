# Changelog

## master

### 🛠 Breaking changes

- `SplashScreen.show()` native method changes it's signature. Its third argument is now a `Boolean` flag that tells the system whether the `StatusBar` component should be `translucent`. Pass `false` to preserve previous behavior.
- `expo-splash-screen-command` is now replaced by `@expo/configure-splash-screen`. Functionality is not affected.

### 🎉 New features

### 🐛 Bug fixes

- add polyfill for usage within managed workflow

## 0.2.0

### 🎉 New features

- expo-splash-screen-command is now bundled with expo-splash-screen and helps you to automatically configure your splash screen in bare React Native apps. Install expo-splash-screen in your project then run `yarn expo-splash-screen --help` for more information.

# Changelog

## Unpublished

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- @mczernek/app loader migration ([#8438](https://github.com/expo/expo/pull/8438) by [@mczernek](https://github.com/mczernek))

## 1.1.0 — 2020-05-27

### 🐛 Bug fixes

- Fixed `appLoaderRegisteredForName` to not only check if a loader class name is in the cache for the provided name but also verifies that the cached and current class name match. When migrating from managed to bare, the class name cache needs to be updated. ([#8292](https://github.com/expo/expo/pull/8292) by [@thorbenprimke](https://github.com/thorbenprimke))

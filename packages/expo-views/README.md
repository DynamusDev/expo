# expo-views

An official package for common views in Expo apps that run on Android, iOS, and web. This is similar to [`react-primitives`](https://github.com/lelandrichardson/react-primitives) or [`@emotion/primitives`](https://emotion.sh/docs/@emotion/primitives) for Expo.

This exports five components:

- `View`
- `ScrollView`
- `Text`
- `TextInput`
- `Image`

and `StyleSheet`.

# API documentation

- [Documentation for the master branch](https://github.com/expo/expo/blob/master/docs/pages/versions/unversioned/sdk/views.md)
- [Documentation for the latest stable release](https://docs.expo.io/versions/latest/sdk/views/)

# Installation in managed Expo projects

For managed [managed](https://docs.expo.io/versions/latest/introduction/managed-vs-bare/) Expo projects, please follow the installation instructions in the [API documentation for the latest stable release](#api-documentation). If you follow the link and there is no documentation available then this library is not yet usable within managed projects &mdash; it is likely to be included in an upcoming Expo SDK release.

# Installation in bare React Native projects

For bare React Native projects, you must ensure that you have [installed and configured the `react-native-unimodules` package](https://github.com/unimodules/react-native-unimodules) before continuing.

### Add the package to your npm dependencies

```
npm install expo-views
```

# Contributing

Contributions are very welcome! Please refer to guidelines described in the [contributing guide]( https://github.com/expo/expo#contributing).

|                          | |  |   |   |
| --------------------------------------- | -------- | ---------- |---------- |---------- |
| <a href="https://www.npmjs.com/package/expo-skeleton">![NPM VERSION](https://img.shields.io/npm/v/expo-skeleton?style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/expo-skeleton">![NPM WEEKLY DOWNLOADS](https://img.shields.io/npm/dw/expo-skeleton?color=%232CA215&label=WEEKLY%20DOWNLOADS&style=for-the-badge)</a> | <a href="https://github.com/mmusaib/expo-skeleton/stargazers">![GITHUB STAR](https://img.shields.io/github/stars/mmusaib/expo-skeleton?label=Give%20Us%20A%20Star&style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/expo-skeleton">![NPM LIFETIME DOWNLOADS](https://img.shields.io/npm/dt/expo-skeleton?color=%232CA215&style=for-the-badge)</a>

<h1 align="center">
 expo-skeleton
</h1>

<div align="center">

-Skeleton Loading Component for Expo mobile applications



-   Fully customizable, custom shapes, colors
-   Smooth and fast




# Compatibility


|  iOS  | Android | React Native Cli |
--------|---------|------|
|  ✅  |    ✅    |  ✅  |



# 🔌 Installation

```sh
$ npm install expo-skeleton
```

OR

```sh
$ yarn add expo-skeleton
```




#  Displaying the skeleton loading
All you need is to just import the skeleton loading component, and in between the
closing and ending tags, you can design the UI of your skeleton loading screen
as shown in the code snippet below:

```jsx
import SkeletonLoading from 'expo-loading'

const App = () => {

  return(
    <SkeletonLoading background={"#adadad"} highlight={"#ffffff"}>
        <View style={{ flexDirection: 'row', justifyContent: 'space-between' }}>
          <View style={{ width: 100, height: 100, backgroundColor: "#adadad", borderRadius: 10 }} />

          <View style={{ flex:1, marginLeft: 10 }}>
              <View style={{ backgroundColor: "#adadad", width: "50%", height: 10, marginBottom: 3, borderRadius: 5 }} />
              <View style={{ backgroundColor: "#adadad", width: '20%', height: 8, borderRadius: 5 }} />
              <View style={{ backgroundColor: "#adadad", width: '15%', height: 8, borderRadius: 5, marginTop: 3 }} />
          </View>
        </View>
    </SkeletonLoading>
  )

};
```




# ⭐ Props  for  the component
| Name | Type | Description |
| ---- | ----------- | ----------- |
| background | hex color string | Hex color string for the background of loading component
| highlight | hex color string | Hex color string for the highlight of loading component


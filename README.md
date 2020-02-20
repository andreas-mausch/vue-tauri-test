# vue-tauri-test

This is an example project to show how to combine vue and tauri to build a native app.

## Requirements

- npm
- tauri (see [here](https://github.com/tauri-apps/tauri/wiki))

## Project setup
```
npm install
```

### Compiles and minifies for production
```
npm run build
```

### Build native app
```
tauri build
```

## How this project has been created

```
# settings for vue create: node-sass, babel, typescript, eslint
vue create .
npm install
npm run build
tauri init
tauri build
```

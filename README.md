# react-app-template
This is a template repo for a react app

## Init
### Create package.json
```
npm init
```

### Install webpack
```
npm i --save-dev webpack-cli webpack webpack-dev-server
```

### Install loaders
```
npm i --save-dev @babel/core @babel/preset-env @babel/preset-react babel-loader
npm i --save-dev css-loader style-loader
```

### Install plugin
```
npm i html-webpack-plugin
```

### Install react
```
npm i react react-dom
```

### Add scripts to package.json
```
"scripts": {
  "build": "webpack",
  "dev": "webpack serve"
}
```
### Run build
```
npm run build
```

### Run dev
```
npm run dev
```

### Open project on localhost
```
http://localhost:9000/
```

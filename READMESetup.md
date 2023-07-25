# Install 
1. npm install gh-pages --save-dev
yarn add gh-pages -D

2.  add belwo in package.json file  
  "homepage": "https://deveshksrivastava.github.io/my-react-app-github-action",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
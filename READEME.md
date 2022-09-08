How to install Bootstrap via npm and how to add a custom scss style to projects. --> https://www.youtube.com/watch?v=gdn9B0LCiI4

1. install https://getbootstrap.com/---> "npm i bootstrap@5.2.1" 
2. npm init -y
3. npm install --save-dev parcel --> https://parceljs.org/getting-started/webapp/
4. src --assets--js--main.js
        |       |scss--main.scss
        |            |abstracts--_variables.scss
        |
        |--index.html
5. package.json ---> source -->./src/index.js
6. "scripts": {
    "dev": "parcel",
    "build": "parcel build"
  },
import custom scss
https://getbootstrap.com/docs/5.2/customize/sass/
Sass variables 
https://getbootstrap.com/docs/5.2/components/buttons/#sass-variables
# Project: npm-run-dev

Welcome to **npm-run-dev**! Our platform aims to promote sustainable practices by showcasing recycled products, their reuse history, carbon footprint details, and nearby recyclable shops, empowering users to make eco-conscious consumer choices.

## Installation

Follow these steps to set up the project:



For Frontend (Port: 3000):
```
cd client
npm install --legacy-peer-deps      or yarn
npm start
```

For Backend (Port: 8080):
```
cd server
npm install --legacy-peer-deps       or yarn
npm start
```
#NOTE : 
if getting error similar to : 
ERROR in ./node_modules/@fortawesome/react-fontawesome/index.es.js 1:0-64
Module not found: Error: Can't resolve '@fortawesome/fontawesome-svg-core' in '/Users/dhawansolanki/DEV/npm-run-dev-devsprints/client/node_modules/@fortawesome/react-fontawesome'
run : 
```npm install --save @fortawesome/react-fontawesome @fortawesome/free-brands-svg-icons```

for the error related to node-sass:
npm ERR! gyp ERR! command "C:\\Program Files\\nodejs\\node.exe" "D:\\office\\project\\snaprr\\client\\node_modules\\node-gyp\\bin\\node-gyp.js" "rebuild" "--verbose" "--libsass_ext=" "--libsass_cflags=" "--libsass_ldflags=" "--libsass_library="
npm ERR! gyp ERR! cwd D:\office\project\snaprr\client\node_modules\node-sass
run this command:
```npm install node-sass --ignore-scripts```
after this try npm install


Technologies
Our project utilizes the following technologies:

ReactJS
NodeJS
ExpressJs
MongoDB
AWS
Tailwind CSS
Flow Bite React


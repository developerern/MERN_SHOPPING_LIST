[ npm i -D nodemon ]

[ cd client ]

if not installed <br>
[ npm i -g create-react-app ]

[ create-react-app . ]

add in package.json of client folder<br>
"proxy": "http://localhost:5000"

[ cd .. ]

add in package.json of root<br>
"client": "npm start --prefix client"<br>
OR<br>
"client": "cd client && npm start"

add in package.json of root<br>
"dev": "concurrently \"npm run server\" \"npm run client\""

add in package.json of root<br>
"client-install": "npm install --prefix client"


cd client <br>
[ npm i bootstrap reactstrap uuid react-transition-group ]

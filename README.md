### Gabo Hurtado
[gabohurtado1991@gmail.com](mailto:gabohurtado1991@gmail.com)

    NOTE: These syntaxes run from the directory where this README is located
    
  * Necesary package
    `npm i -g http-server`

  * Steps to run the server  
    `cd server && npm install && npm start`
    * The server is available in https://127.0.0.1:3001/api

  * Build client app
    `cd client && npm install && npm run build && http-server build -p 3000 -S -C cert.pem -o`
    * The client is available in https://127.0.0.1:3000

  * Steps to test the apps  
    `npm run test`  
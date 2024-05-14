# steps-to-deploy-mern-stack-on-render
deploying mern stack:
1. run front end and backend on local host
2. check for bugs and cors errors
3. Create a cluster on mongodb and generate a connection string and put it in backend files.
4. upload the backend file on github
5. connect to render and 
build command: npm install
start command: nodemon server.js
6. check for environment varibles if any
7. create web services
8. use the generated link for backend api and link it to frontend


1. run front end on local host and backend on render and check for bugs
2. then upload the frontend on github and 
build command: npm install && npm run build
start command: npx serve -s build
3. take the generated link and put it in cors in backend to allow cross origin sharing
4. create web service and done

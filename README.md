

# Steps to Deploy MERN Stack on Render

## Deploying Backend

1. Run frontend and backend on localhost.
2. Check for bugs and CORS errors.
3. Create a cluster on MongoDB and generate a connection string; put it in the backend files.
4. Upload the backend files on GitHub.
5. Connect to Render and set up the following:
   - Build Command: `npm install`
   - Start Command: `nodemon server.js`
6. Check for environment variables if any.
7. Create web services.
8. Use the generated link for the backend API and link it to the frontend.

## Deploying Frontend

1. Run frontend on localhost and backend on Render; check for bugs.
2. Upload the frontend on GitHub and set up the following:
   - Build Command: `npm install && npm run build`
   - Start Command: `npx serve -s build`
3. Take the generated link and put it in the CORS in the backend to allow cross-origin sharing.
4. Create web service and you're done.

## Very Important

1. Handle CORS origin correctly with suitable syntaxes.
2. Link frontend to backend using the right API link.
3. After deploying frontend, update the backend CORS origin with the deployed frontend link.

---

Feel free to adjust the formatting or add more details if needed.

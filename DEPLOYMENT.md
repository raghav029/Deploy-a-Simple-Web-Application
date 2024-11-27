# Deployment on Render
Steps to Deploy
Sign Up and Log In

Go to Render and create an account if you don’t have one.
Log in to your Render dashboard.
Create a New Web Service

Click on the New + button and select Web Service.
Connect your GitHub repository to Render.
Configure Deployment

Environment: Python
Build Command: Render automatically installs dependencies from requirements.txt.
Start Command: Set the start command to:
bash

gunicorn app:app
Deploy

Click Deploy to start the build process.
Wait for Render to build and deploy your application.
Access the Application

Once deployed, Render provides a public URL where your application is live.


# Public URL
Your application is now live and can be accessed at:
https://deploy-a-simple-web-application.onrender.com

# Deployment Guide

This document provides comprehensive deployment guides for hosting the project using various platforms.  

## GitHub Pages
1. Make sure your project is in a GitHub repository.
2. Go to the repository settings.
3. Under the "Pages" section, select the branch you want to deploy (e.g., `main`).
4. Click on "Save".
5. Your site will be published at `https://<username>.github.io/<repository-name>/`.

## Netlify
1. Go to [Netlify](https://www.netlify.com/) and sign up or log in.
2. Click on "New site from Git".
3. Choose your Git provider and authorize Netlify.
4. Select your repository.
5. Set the build command (if any) and the publish directory (usually `dist` or `public`).
6. Click on "Deploy site". Your site will be live on a unique Netlify URL.

## Vercel
1. Go to [Vercel](https://vercel.com/) and sign up or log in.
2. Click on "New Project".
3. Import your GitHub repository.
4. Configure the deployment settings (if needed).
5. Click on "Deploy". Your project will be hosted on a Vercel subdomain.

## Firebase Hosting
1. Ensure you have the Firebase CLI installed. If not, run:
   ```
   npm install -g firebase-tools
   ```
2. Log in to Firebase:
   ```
   firebase login
   ```
3. Initialize your project:
   ```
   firebase init hosting
   ```
4. Select your Firebase project.
5. Set your public directory (usually `public`) and configure for SPA if necessary.
6. Deploy your site:
   ```
   firebase deploy
   ```
7. Your site will be available at `https://<project-id>.firebaseapp.com/`.  

Feel free to reach out if you encounter any issues during deployment!
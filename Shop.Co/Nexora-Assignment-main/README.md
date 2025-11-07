# SHOP.CO

This repository contains the SHOP.CO frontend and backend applications.

Quick setup (development)

1. Install dependencies

   Frontend:
   ```
   cd frontend
   npm install
   ```

   Backend:
   ```
   cd backend
   npm install
   ```

2. Create environment files

   Do NOT commit your .env files. Create them locally with the required secrets.

   Example backend `.env` (do not commit):
   ```ini
   PORT=4000
   MONGODB_URI=your-mongodb-uri
   EMAIL_USER=you@example.com
   EMAIL_PASSWORD=your-email-password
   RAZORPAY_KEY_ID=...
   RAZORPAY_KEY_SECRET=...
   JWT_SECRET=...
   ```

3. Run development servers

   Frontend:
   ```cmd
   cd frontend
   npm run dev
   ```

   Backend:
   ```cmd
   cd backend
   npm run dev
   ```

Pushing to GitHub (professional)

- Ensure `.gitignore` excludes all sensitive files (this repo includes a top-level `.gitignore`).
- Commit meaningful messages and use a main branch as the default.

Example commands (run locally):

```cmd
# initialize (only if repo not initialized)
# git init

git add .
git commit -m "chore: initial project files"

git branch -M main
# add your remote (replace with your repo)
git remote add origin https://github.com/<your-username>/<your-repo>.git
# push
git push -u origin main
```

If you want, I can attempt to create a local commit here and set the remote — but I will not push (to avoid requiring credentials) unless you confirm and provide appropriate access.

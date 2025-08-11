# React + Firebase Starter Project

## Features
- Admin product upload with image storage in Firebase Storage
- Customer product listing from Firestore
- Floating WhatsApp contact button with pulse animation
- Firebase config using environment variables for security
- Ready for deployment on Netlify

## Setup

1. Clone this repo or download the files.
2. Create a `.env` file in the root with your Firebase config keys:

```
REACT_APP_API_KEY=your_api_key
REACT_APP_AUTH_DOMAIN=your_auth_domain
REACT_APP_PROJECT_ID=your_project_id
REACT_APP_STORAGE_BUCKET=your_storage_bucket
REACT_APP_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_APP_ID=your_app_id
```

3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Build with `npm run build` for production.
6. Deploy to Netlify by connecting your GitHub repo and setting environment variables on Netlify dashboard.

## Notes
- Ensure Firebase Firestore and Storage are enabled in your Firebase console.
- The admin product upload is accessible via `/admin` route.
- Customer product listing is accessible via `/` route.
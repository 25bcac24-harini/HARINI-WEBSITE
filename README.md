# Harini Portfolio

A modern, professional portfolio website built with Node.js, Express, and vanilla JavaScript.

## Features

- 🎨 Modern, responsive design with particle effects
- 📸 Drag-and-drop photo gallery
- 📧 Contact form with email notifications
- 🚀 Professional animations and transitions
- 📱 Mobile-friendly responsive layout

## Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Configure environment variables:**
   Create a `.env` file in the root directory:
   ```
   EMAIL_USER=your-gmail@gmail.com
   EMAIL_PASS=your-app-password
   PORT=3000
   ```

   **Important:** For Gmail, you need to generate an App Password:
   - Go to Google Account settings
   - Enable 2-factor authentication
   - Generate an App Password for "Mail"
   - Use that password in EMAIL_PASS

3. **Start the server:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Navigate to `http://localhost:3000`

## Project Structure

```
harini-portfolio/
├── server.js          # Express server
├── index.html         # Main HTML file
├── package.json       # Dependencies
├── .env              # Environment variables
├── public/           # Static files
│   └── uploads/      # Uploaded images
└── README.md         # This file
```

## API Endpoints

- `GET /` - Serve the main page
- `GET /api/photos` - Get list of uploaded photos
- `POST /api/upload` - Upload a new photo
- `POST /api/contact` - Send contact form message

## Technologies Used

- **Backend:** Node.js, Express.js
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **File Upload:** Multer
- **Email:** Nodemailer
- **Styling:** Custom CSS with modern design patterns

## Deployment

This application can be deployed to any Node.js hosting service like Heroku, DigitalOcean, or Vercel.

Make sure to set the environment variables in your deployment platform's settings.
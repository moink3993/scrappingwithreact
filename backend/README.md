# Waqf Scraper Backend

This is the backend server for the Waqf Document Scraper application. It handles web scraping, PDF generation, and ZIP file creation.

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Start the server:
   ```
   npm start
   ```

## API Endpoints

- `POST /scrape` - Start the scraping process
- `POST /abort` - Abort the scraping process
- `POST /create-zip` - Create a ZIP file from a folder
- `GET /stream` - Server-sent events endpoint for real-time logging

## Requirements

- Node.js (v14 or higher)
- Chrome browser
- ChromeDriver (compatible with your Chrome version)

## Deployment to Render

This application has been configured for deployment to Render.com.

### Deployment Steps

1. Push this repository to GitHub
2. Connect your GitHub account to Render
3. Create a new "Blueprint" on Render and select the repository
4. Render will automatically create the backend and frontend services using the `render.yaml` configuration

### Environment Variables

The following environment variables are used:

- `NODE_ENV` - Set to "production" in the Render environment
- `PORT` - The port on which the backend server runs
- `REACT_APP_API_URL` - URL of the backend API (set in frontend build)

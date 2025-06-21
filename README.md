# Waqf Document Scraper

A modern web application for scraping Waqf document data, generating PDFs, and creating ZIP archives.

## Features

- Document scraping from multiple URLs
- PDF generation and download
- ZIP file creation
- Real-time logging with color-coded messages
- Dark mode toggle
- Responsive design

## Project Structure

- **Frontend**: React application
- **Backend**: Express server with Selenium for web scraping

## Setup

### Prerequisites

- Node.js (v14 or higher)
- Chrome browser
- ChromeDriver (compatible with your Chrome version)

### Installation

1. Install frontend dependencies:
   ```
   npm install
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

### Running the Application

1. Start the backend server:
   ```
   cd backend
   npm start
   ```

2. In a separate terminal, start the frontend:
   ```
   npm start
   ```

3. Access the application at http://localhost:3000

## Environment Configuration

The application uses environment variables for configuration:

- Frontend: `REACT_APP_API_URL` - URL of the backend API
- Backend: `PORT` - Port number for the server, `NODE_ENV` - Environment setting

## Deployment to Render

This application has been configured for deployment to Render.com.

### Deployment Steps

1. Push this repository to GitHub
2. Connect your GitHub account to Render
3. Create a new "Blueprint" on Render and select the repository
4. Render will automatically create the frontend and backend services using the `render.yaml` configuration

## Development

### Building for Production

```
npm run build
```

### Running Tests

```
npm test
```
# scrappingwithreact

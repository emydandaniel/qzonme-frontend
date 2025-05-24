# QZonMe Frontend

This is the frontend application for QZonMe, built with React, Vite, and TailwindCSS.

## Features
- Interactive Quiz Creation
- Quiz Sharing
- Quiz Taking
- Results Dashboard
- Responsive Design

## Project Setup

1. Install dependencies:
```bash
npm install
```

2. Create a `.env` file in the root directory with:
```
VITE_API_URL=your_backend_url
```

3. Run the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Deployment on Vercel

1. Make sure your repository is up to date
2. Go to your Vercel dashboard
3. If the project exists:
   - Go to Project Settings
   - Under Git, click "Force Push"
   - Trigger a new deployment
4. If the project doesn't exist:
   - Click "Add New Project"
   - Import your GitHub repository
   - Configure the following:
     - Framework Preset: Vite
     - Build Command: `npm run build`
     - Output Directory: `dist`
   - Add environment variables:
     - `VITE_API_URL`: Your backend API URL
5. Deploy! 
# Video Backend API

A Node.js backend for a video platform built with Express, MongoDB, JWT authentication, and Cloudinary uploads.

## Setup

1. Install dependencies

```bash
npm install
```

2. Create a `.env` file from `.env.example` (or manually) and add your configuration.

3. Start the server in development mode

```bash
npm run dev
```

## Recommended environment variables

```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## Project structure

- `src/` - application source code
- `src/routes/` - route definitions
- `src/controllers/` - request handlers
- `src/models/` - Mongoose models
- `src/middlewares/` - middleware functions
- `src/utils/` - helpers and error handling

## Notes

- `node_modules/` and `.env` files should not be committed to Git.
- If you use a local `.eve` folder for environment files, exclude it from Git too.

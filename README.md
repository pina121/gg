# Dynamic Sticker Maker

A modern web application for creating custom stickers with advanced image manipulation features.

## Features

- Drag and drop image upload
- Real-time image preview
- Adjustable effects:
  - Brightness
  - Contrast
  - Saturation
- Text overlay support
- Mobile-responsive design
- Beautiful dark theme UI
- Smooth animations and transitions
- Easy download functionality

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd dynamic-sticker-maker
```

2. Install backend dependencies:
```bash
npm install
```

3. Install frontend dependencies:
```bash
cd client
npm install
cd ..
```

## Running the Application

1. Start the backend server:
```bash
npm run dev
```

2. In a new terminal, start the frontend development server:
```bash
npm run client
```

3. Open your browser and navigate to `http://localhost:3000`

## Usage

1. Drag and drop an image or click to select one
2. Adjust the image effects using the sliders
3. Add text overlay if desired
4. Click "Create Sticker" to process the image
5. Download your sticker using the download button

## Technologies Used

- Frontend:
  - React
  - Material-UI
  - Framer Motion
  - React Dropzone
  - Axios

- Backend:
  - Node.js
  - Express
  - Sharp (for image processing)
  - Multer (for file uploads)

## License

MIT 
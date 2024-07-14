```markdown
# AI Image Generator

This project is an AI-powered image generator built using React for the frontend and Node.js with Express for the backend. The backend uses the OpenAI API to generate images based on text prompts provided by the user. Cloudinary is used to store the generated images.

## Features

- Generate images from text prompts
- Responsive design for a seamless user experience on all devices
- Uses styled-components for styling
- Stores generated images on Cloudinary

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm (or yarn)
- MongoDB (or a MongoDB Atlas account)
- Cloudinary account

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Sukhhh/ai_img_generator.git
cd ai_img_generator
```

2. Install dependencies for both the frontend and backend:

```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

3. Create a `.env` file in the `server` directory and add your MongoDB connection string, OpenAI API key, and Cloudinary configuration:

```env
MONGODB_URL=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Running the Application

1. Start the backend server:

```bash
cd server
npm start
```

2. Start the frontend development server:

```bash
cd ../client
npm start
```

3. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

```plaintext
ai_img_generator/
├── client/                  # React frontend
│   ├── public/
│   └── src/
│       ├── components/      # React components
│       ├── pages/           # React pages
│       ├── App.js           # Main App component
│       └── index.js         # Entry point for React
├── server/                  # Express backend
│   ├── controllers/         # Controllers for handling requests
│   ├── routes/              # Route definitions
│   ├── .env                 # Environment variables
│   ├── index.js             # Entry point for Express server
│   └── error.js             # Error handling module
└── README.md                # This file
```

## Usage

1. Enter a text prompt in the input field.
2. Click the "Generate Image" button.
3. Wait for the AI to generate an image based on your prompt.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://openai.com/) for providing the image generation API
- [React](https://reactjs.org/) for the frontend framework
- [Express](https://expressjs.com/) for the backend framework
- [styled-components](https://styled-components.com/) for CSS-in-JS styling
- [Cloudinary](https://cloudinary.com/) for image storage
```

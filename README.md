# debatorsam

🛠️ Installation

Clone the repository:


    git clone https://github.com/ashuuu77/debatorsam.git

Navigate to the project directory:


    cd Debator Sam

Install dependencies:

Frobtend

    cd Frontend
    npm install
    npm i framer-motion lucide-react react react-dom react-icons react-redux react-router-dom react-speech-recognition react-toastify wav-encoder


    cd Backend
    npm install

    npm i @google/generative-ai axios bcrypt concurrently cookie-parser cors dotenv express jsonwebtoken mongodb mongoose multer nodemon prettier

Set up environment variables:

Create a .env file in the backend directory and replace with actual values

PORT=8000
MONGODB_URI=

ACCESS_TOKEN_SECRET=

ACCESS_TOKEN_EXPIRY=

REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRY=

CORS_ORIGIN=*

GOOGLE_API_KEY=

HUGGINGFACE_API_KEY=

Run the application:

Frontend


    npm run dev

Backend


    npm run server

Use concurrently - for both Backend and Frontend


    cd Backend
    npm run dev


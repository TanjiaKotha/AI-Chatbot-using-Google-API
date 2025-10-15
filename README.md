AI Chatbot powered by Google's Gemini API
A simple, clean, and responsive web-based chatbot that leverages the power of the Google Gemini API to provide intelligent and conversational responses. This project is built with vanilla HTML, Tailwind CSS, and JavaScript, making it lightweight and easy to deploy.

Live Demo: https://ai-chatbot-using-google-api.vercel.app/

Features
Conversational AI: Get human-like responses from Google's powerful Gemini model.

Responsive Design: A clean and modern user interface that works seamlessly on desktops, tablets, and mobile devices.

Real-time Feel: Includes a typing indicator to improve the user experience while waiting for the AI's response.

Zero Dependencies: Built entirely in a single HTML file with no complex setup or build process required.

Easy to Deploy: Can be deployed to any static web host, such as Vercel or GitHub Pages, in minutes.

Technologies Used
HTML5

Tailwind CSS (via CDN)

JavaScript (ES6+)

Google Gemini API

Getting Started
To run this project on your local machine, follow these simple steps.

Prerequisites
You just need a modern web browser.

Setup
Clone the repository or download the index.html file:

git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)

Get a Google Gemini API Key:

Visit Google AI Studio.

Click "Create API key" and copy the generated key.

Add the API Key to the project:

Open the index.html file in a text editor.

Find the following line (around line 105):

const apiKey = "YOUR_API_KEY_GOES_HERE";

Replace "YOUR_API_KEY_GOES_HERE" with the key you copied from Google AI Studio.

Run the application:

Simply open the index.html file in your web browser.

Deployment
This project can be easily deployed to Vercel:

Push your code to a GitHub repository.

Go to Vercel and sign up with your GitHub account.

Click "Add New... > Project" and select your repository.

Vercel will automatically detect the settings. Just click Deploy.

Note: For security reasons, it's not recommended to expose your API key on the client-side for a production application. For more advanced projects, consider using a backend proxy or serverless function to protect your key.

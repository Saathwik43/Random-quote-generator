# Getting Started
🤖 AI-Powered Poetic Quote Generator
<p align="center">
<img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
<img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
</p>

<p align="center">
A creative web application that generates a unique, Oscar Wilde-style poetic quote paired with a beautiful background image from Unsplash. Just provide your name and a few of your favorite things, and let the AI work its magic!
</p>

<p align="center">
<img src="https://i.imgur.com/your-screenshot.png" alt="Project Screenshot" width="700">
<br>
<em>(Note: Replace the URL above with a real screenshot of your project.)</em>
</p>

📋 Table of Contents
✨ Features

🛠️ Tech Stack

🚀 Getting Started

🏗️ Building for Production

🤝 Contributing

📄 License

🙏 Acknowledgments

✨ Features
Dynamic Quote Generation: Utilizes the OpenAI API to create unique, poetic phrases on demand.

Themed Background Images: Fetches high-quality, relevant images from Unsplash to match your favorite place.

Personalized Content: Tailors the output based on your name, favorite activity, and favorite place.

Customizable AI: Easily adjust the "temperature" setting to control the creativity and randomness of the generated quote.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES Modules)

Build Tool: Vite - For a blazing fast development experience.

APIs:

OpenAI API (via Scrimba's proxy) for text generation.

Unsplash API (via Scrimba's proxy) for image fetching.

🚀 Getting Started
<details>
<summary>Click to expand installation and usage instructions</summary>

Prerequisites
Make sure you have Node.js (v16 or higher) installed on your machine.

Installation
Clone the repository to your local machine:

git clone https://github.com/your-username/your-repository-name.git

Navigate to the project directory:

cd your-repository-name

Install the necessary dependencies using npm:

npm install

Usage
Open the index.js file in your favorite code editor.

Customize the following variables with your own information:

let name = "Your Name";
let favoriteActivity = "your favorite activity";
let favoritePlace = "your favorite place";
let temperature = 0.5; // A value from 0 (deterministic) to 1 (creative)

Optionally, you can replace the avatar.jpg file in the root directory with a photo of yourself.

Start the development server:

npm start

Open your browser and navigate to the local address provided (usually http://localhost:5173/). The page will automatically reload when you make changes.

</details>

🏗️ Building for Production
To create a static, production-ready build of the application, run the following command:

npm run build

This will create a dist folder containing the optimized and minified files, which you can then deploy to any static hosting service.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have suggestions for improvements, please fork the repository and create a pull request. You can also simply open an issue with the tag "enhancement".

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is distributed under the MIT License. See LICENSE.txt for more information.

🙏 Acknowledgments
This project was created as part of a learning module from Scrimba.

A big thank you to the Scrimba team for providing the tools and platform to build fun, creative projects like this one. 

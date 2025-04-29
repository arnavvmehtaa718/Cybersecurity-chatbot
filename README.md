#cybersecurity chatbot
AI Hacker - Cybersecurity Chatbot

Welcome to Cybersecurity chatbot Hacker Mode, an AI-powered cybersecurity chatbot designed to provide answers to your cybersecurity-related questions. It uses cutting-edge AI technology to simulate a hacker's perspective, allowing you to engage in a conversation with "Gemini AI" while experiencing a thrilling hacker-like UI.
Features

    AI Chatbot: Get answers to your cybersecurity queries powered by Gemini AI.

    Cybersecurity-Themed UI: A hacker-inspired interface with binary rain and neon green text.

    Real-Time Interaction: Type questions and receive near-instant answers from the AI.

    Responsive Design: The interface adjusts beautifully to all screen sizes, providing a seamless experience on mobile and desktop.

Installation
Prerequisites

    API Key: To access the AI-powered responses, you need to obtain an API key from Google Cloud's Generative Language API. Insert your API key in the script section of the HTML file.

Clone the repository

git clone https://github.com/yourusername/gemini-ai-hacker-mode.git
cd gemini-ai-hacker-mode

Open the HTML File

After cloning the repository, you can open the index.html file directly in your browser to see the chatbot in action.

open index.html

API Integration

    In the script tag of the index.html, replace the "API KEY" placeholder with your valid API key to enable AI functionality.

const apiKey = "YOUR_API_KEY_HERE";

Usage

Once the page is loaded:

    Enter your question: Type a cybersecurity-related question in the input field.

    Click "Ask": Press the "Ask" button to send the query to Gemini AI.

    View the response: The AI's response will appear in the chat box, simulating a real-time conversation.

The interface also displays a binary rain effect to immerse you in the hacker-themed environment.
Code Explanation
UI Design

    Binary Rain Effect: The background includes an animated binary rain effect created using HTML and CSS. Each binary column falls from the top, and the column is generated at random intervals, simulating the famous hacker look.

    Responsive Chat Interface: The chat container is styled to mimic a terminal, with a neon green theme and clean typography.

JavaScript Functionality

    askGemini(): This function handles the interaction with the Gemini AI API. It checks if the user has entered a question, sends the query to the API, and updates the page with the AI's response.

    Error Handling: If no question is entered or if there is an error in fetching the response, appropriate error messages are displayed.

Customization

    Change the AI response style: Modify the response-box class in the CSS to customize the response box (e.g., change background color, font size).

    Binary Rain Speed: Adjust the fall animation duration in the @keyframes rule to change the speed of the binary rain.

Contributing

We welcome contributions to enhance this project! If you have suggestions for new features, improvements, or bug fixes, feel free to fork this repository and create a pull request.

To contribute:

    Fork the repository.

    Create a new branch (git checkout -b feature/your-feature-name).

    Commit your changes (git commit -am 'Add new feature').

    Push to the branch (git push origin feature/your-feature-name).

    Open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

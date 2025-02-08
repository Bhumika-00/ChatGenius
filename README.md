# 🤖 Chatbot Web Application - ChatGenius

## 📌 Overview
ChatGenius is a simple chatbot web application that integrates with Google's Gemini AI model to generate responses based on user input. The chatbot supports text and file uploads, and includes emoji input functionality for a richer user experience.

## ✨ Features
- 💬 Send text messages to ChatGenius and receive AI-generated responses.
- 📂 Upload files to enhance conversations with additional context.
- 😀 Emoji picker for easy insertion of emojis into messages.
- 🔄 Smooth UI interactions, including scrolling and typing indicators.
- ⚠️ Error handling for API responses.

## 🛠 Technologies Used
- 📝 JavaScript (Vanilla JS)
- 🎨 HTML & CSS
- 🌐 Google Gemini API
- 📜 FileReader API
- 😀 EmojiMart for emoji selection

## 🚀 Setup Instructions
### 📋 Prerequisites
- 🖥 A web browser (Chrome, Firefox, etc.)
- 🔑 A valid Google API key with access to Gemini AI

### 📂 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/chatbot-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd chatbot-app
   ```
3. Open `index.html` in your browser to run ChatGenius.

## ⚙️ Configuration
- Replace the `API_KEY` in `script.js` with your Google API key:
  ```js
  const API_KEY="YOUR_GOOGLE_API_KEY";
  ```

## 🎯 Usage
1. ⌨️ Type a message in the input field and press Enter or click the send button.
2. 📁 Upload an image or file by clicking the file upload button.
3. 😃 Use the emoji picker to insert emojis into your messages.
4. 📩 View ChatGenius responses in real time.

## 📁 File Structure
```
chatbot-app/
│── index.html          # Main HTML file
│── style.css           # Stylesheet for chatbot UI
│── script.js           # Main JavaScript logic for chatbot functionality
│── assets/             # Contains images, icons, and other assets
```

## 🔧 Known Issues & Future Improvements
- 🖼 Improve response formatting for better readability.
- 🔐 Implement user authentication for a personalized chat experience.
- 📂 Enhance file handling to support multiple file types.

## 📜 License
This project is licensed under the MIT License. Feel free to modify and use it as needed.

## 📞 Contact
For any questions or contributions, please open an issue or submit a pull request on GitHub.


# 🤖 AI Assistant - Urdu & English

A simple, beautiful AI chatbot that understands both **Urdu** and **English** languages. Powered by Google Gemini AI.

## ✨ Features

- 💬 Chat interface with modern design
- 🇵🇰 Full Urdu language support
- 🇬🇧 English language support
- 🎨 Dark theme with smooth animations
- 📱 Fully responsive (works on mobile, tablet, desktop)
- ⚡ Real-time responses using Gemini API
- 🎯 Intelligent conversation handling

## 🚀 Quick Start

### Step 1: Get Your API Key
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account (create one if needed)
3. Click **"Create API key"**
4. Copy the API key

### Step 2: Setup the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/saim2652/ai-assistant.git
   ```

2. Open `index.html` in a text editor

3. Find this line:
   ```javascript
   const API_KEY = "YOUR_GEMINI_API_KEY_HERE";
   ```

4. Replace it with your API key:
   ```javascript
   const API_KEY = "paste_your_api_key_here";
   ```

5. Save the file

### Step 3: Run
- Simply open `index.html` in your web browser
- Start chatting!

## 📖 How to Use

1. Type your message in the input field
2. Press **Enter** or click **Send**
3. Wait for the AI to respond
4. You can write in:
   - **Urdu**: "Mujhe gravity samjhao"
   - **English**: "What is artificial intelligence?"
   - **Mix of both**: "AI ka matlab kya hota hai?"

## ⚙️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling & Animations
- **JavaScript** - Functionality
- **Google Gemini API** - AI responses

## 🔒 Security Note

⚠️ **IMPORTANT**: Never share your API key publicly!
- The API key in the code is exposed to anyone who views the page source
- For production use, set up a backend server to handle API calls
- The API key should be stored securely on the server side

## 🐛 Troubleshooting

### "API Key Not Set!" Error
- Make sure you've replaced `YOUR_GEMINI_API_KEY_HERE` with your actual API key
- Refresh the page after making changes

### Connection Error
- Check your internet connection
- Verify your API key is correct
- Check if the Gemini API is working at [Google AI Studio](https://makersuite.google.com/)

### No Response from AI
- Wait a few seconds (first request may be slower)
- Check browser console for errors (F12 → Console)
- Verify API key has no extra spaces

## 📝 Language Support

| Language | Examples |
|----------|----------|
| **Urdu** | "Salam", "Mujhe padha karo", "Gravity kya hai?" |
| **English** | "Hello", "Teach me", "What is AI?" |
| **Roman Urdu** | "Mujhe chemistry samjhao" |

## 🎨 Customization

You can customize the chatbot by editing:
- Colors in the `<style>` section
- System prompt in the `sendMessage()` function
- Header text in the HTML

## 📜 License

This project is open source and available for anyone to use.

## 💡 Tips

- Ask educational questions
- Use it for language learning
- Test different prompts to see AI capabilities
- Keep conversations natural and friendly

## 🤝 Contributing

Feel free to fork, modify, and improve this project!

---

**Made with ❤️ by Saim**

Questions? Issues? Feel free to create a GitHub issue or contact me!

# Hello Virtual Assistant


A **browser-based voice-activated personal assistant** built with HTML, CSS, and vanilla JavaScript. Speak commands to open websites, get weather, time, jokes, calculate math, and more! No installation required – just open in your browser.

## 🚀 Features

- **Voice Commands** (~25 supported):
  | Category | Examples |
  |----------|----------|
  | Greetings | \"hello\", \"who are you\" |
  | Open Sites | \"open youtube\", \"open google/facebook/instagram/whatsapp/chatgpt\" |
  | Info | \"time\", \"date\", \"weather\" |
  | Utilities | \"calculate 2+2\", \"generate password\", light/dark mode |
  | Fun | \"tell me a joke\", \"horoscope\", \"play music\" |
  | Search | \"search for [topic]\", \"nearest restaurant\", \"news\" |

- Real-time **speech recognition** & **TTS** (Web Speech API).
- Live **weather** display (geolocation + OpenWeatherMap).
- Responsive dark theme with animations.

## 🎯 Demo
Click the mic button, grant mic permission, and speak!

```
Click here to talk to me → [Mic activates → Speak command → Assistant responds]
```

## 📱 Browser Support
- Chrome, Edge, Safari (SpeechRecognition required).
- HTTPS for geolocation (use GitHub Pages/Netlify).

## 🛠️ Quick Start

1. Clone/Download: `git clone https://github.com/YOUR_USERNAME/voice-assistant.git`
2. Open `index.html` in browser.
3. **Add your API keys** (optional, for full features):
   - OpenWeatherMap: Replace `97c78979b82a50a5563a0578e6c832a0` in `script1.js` ([Get free key](https://openweathermap.org/api)).
   - NewsAPI: Replace `40e5f487c9504b768c1883a6dd9beb11`.

## 🔧 Customization

- **Your Assistant Name**: Edit `<span id="name">Hello</span>` in `index.html`.
- **Add Commands**: Extend `takeCommand()` in `script1.js`.
- **Styling**: Modify `style.css`.

## 🐛 Issues & Improvements
- Secure API keys (use env vars/backend proxy).
- Replace `eval()` for calc (security).
- Add command history, offline mode.

## 📄 License
MIT – Free to use/fork!

**Made with ❤️ using Web Speech API. Star ⭐ if useful!**


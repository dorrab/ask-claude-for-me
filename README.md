# Let Me Ask Claude For You 🤖

A playful single-page website that helps people discover Claude AI - inspired by "Let Me Google That For You". When someone visits with a question, it types it out with a smooth animation, copies it to their clipboard, and redirects them to Claude.ai.

Perfect for when someone asks you a question that Claude could answer instantly! 😊

## 🌐 Live Demo

Visit: [https://dbouchiha.github.io/ask-claude-for-me/](https://dbouchiha.github.io/ask-claude-for-me/)

## ✨ Features

- **Smooth Typing Animation**: Character-by-character typing effect (50ms per character)
- **Auto-Copy to Clipboard**: Automatically copies the question when typing completes
- **Auto-Redirect**: Redirects to Claude.ai after 2 seconds
- **Manual Controls**:
  - "Open in Claude" button for immediate access
  - "Copy Question" button with visual feedback
- **Responsive Design**: Works beautifully on mobile and desktop
- **Modern UI**: Glassmorphic design with smooth animations
- **No Dependencies**: Single self-contained HTML file

## 🚀 Quick Start

### Creating Shareable Links

Simply add your question as a URL parameter:

```
https://dbouchiha.github.io/ask-claude-for-me/?q=Your question here
```

### Example URLs

**For technical questions:**
```
https://dbouchiha.github.io/ask-claude-for-me/?q=Why is PostgreSQL throwing connection errors?
```

**For debugging help:**
```
https://dbouchiha.github.io/ask-claude-for-me/?q=How do I debug a 503 error in our API?
```

**For optimization tips:**
```
https://dbouchiha.github.io/ask-claude-for-me/?q=What's the best way to optimize Oracle read performance?
```

**For general help:**
```
https://dbouchiha.github.io/ask-claude-for-me/?q=How do I center a div in CSS?
```

## 📖 How It Works

1. **User clicks your link** with a question in the `?q=` parameter
2. **Typing animation** displays the question character by character
3. **Auto-copy** copies the question to clipboard when typing completes
4. **Status updates** show "Typing your question..." → "Ready to ask Claude!"
5. **Auto-redirect** opens Claude.ai/new after 2 seconds
6. **User pastes** the question (already in clipboard) into Claude

## 🎨 Design

- **Color Scheme**: Dark gradient background with #cc785c (Wealthsimple copper) accent
- **Typography**: System font stack for optimal performance
- **Effects**: Backdrop blur, smooth transitions, hover animations
- **Responsive**: Stacks buttons vertically on mobile devices

## 🛠️ Technical Details

### Technologies Used
- Pure HTML5
- Vanilla JavaScript (no frameworks)
- Modern CSS with flexbox
- Clipboard API with fallback

### Browser Compatibility
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Key Features Implementation
- **Typing Animation**: Uses `setTimeout` recursion for smooth character rendering
- **Clipboard Copy**: Uses modern Clipboard API with `document.execCommand` fallback
- **URL Parsing**: `URLSearchParams` API for query string handling
- **Responsive Design**: CSS media queries and `clamp()` for fluid typography

## 📦 Deployment

This site is deployed using GitHub Pages from the `main` branch.

### Deploy Your Own

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from main branch"
4. Your site will be live at `https://yourusername.github.io/ask-claude-for-me/`

## 🎯 Use Cases

- **Team Communication**: Send colleagues helpful nudges to use AI
- **Support Forums**: Help people discover Claude for their questions
- **Educational**: Teach people about AI assistants
- **Fun**: Playfully redirect friends who ask basic questions

## 🤝 Contributing

Found a bug or have a feature request? Feel free to open an issue or submit a pull request!

## 📝 License

MIT License - feel free to use and modify as needed.

## 💡 Credits

Inspired by "Let Me Google That For You" (LMGTFY), adapted for the AI era with Claude.

Made with ❤️ for people who ask before searching.

---

**Note**: This is an unofficial fan project and is not affiliated with Anthropic or Claude AI.

# Let Me Ask Claude For You 🤖

A playful single-page website that helps people discover Claude AI - inspired by "Let Me Google That For You". Users can type their question, and with one click it copies to their clipboard and redirects them to Claude.ai.

Perfect for when someone asks you a question that Claude could answer instantly! 😊

## 🌐 Live Demo

Visit: [https://dorrab.github.io/ask-claude-for-me/](https://dorrab.github.io/ask-claude-for-me/)

## ✨ Features

- **Interactive Text Input**: Type or edit your question in a sleek textarea
- **URL Pre-fill Support**: Share links with pre-filled questions via `?q=` parameter
- **One-Click Copy & Redirect**: "Ask Claude" button copies and opens Claude.ai
- **Manual Copy Option**: Separate "Copy Question" button with visual feedback
- **Keyboard Shortcut**: Press Enter to submit (Shift+Enter for new lines)
- **Input Validation**: Helpful messages if you try to submit without a question
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
https://dorrab.github.io/ask-claude-for-me/?q=Why is PostgreSQL throwing connection errors?
```

**For debugging help:**
```
https://dorrab.github.io/ask-claude-for-me/?q=How do I debug a 503 error in our API?
```

**For optimization tips:**
```
https://dorrab.github.io/ask-claude-for-me/?q=What's the best way to optimize Oracle read performance?
```

**For general help:**
```
https://dorrab.github.io/ask-claude-for-me/?q=How do I center a div in CSS?
```

## 📖 How It Works

1. **User visits** the site (optionally with a `?q=` parameter to pre-fill)
2. **Type or edit** their question in the textarea
3. **Click "Ask Claude"** (or press Enter)
4. **Auto-copy** copies the question to clipboard
5. **Auto-redirect** opens Claude.ai/new
6. **User pastes** the question (already in clipboard) into Claude

### Alternative: Direct Share Mode

Share a link with the `?q=` parameter:
- Question is pre-filled in the textarea
- Recipient can edit if needed
- One click to copy and open Claude

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
- **Text Input**: HTML5 textarea with custom styling and focus states
- **Clipboard Copy**: Uses modern Clipboard API with `document.execCommand` fallback
- **URL Parsing**: `URLSearchParams` API for query string handling and pre-filling
- **Keyboard Shortcuts**: Enter to submit, Shift+Enter for multi-line input
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

# ⌨️ TypeTest

A fast, beautiful typing speed test with real-time analytics.

**[Try it live →](https://claytondb.github.io/typetest/)**

![TypeTest Screenshot](https://via.placeholder.com/800x400/0f0f1a/10b981?text=TypeTest)

## Features

- 🚀 **Real-time WPM tracking** - See your words per minute update live as you type
- 🎯 **Accuracy monitoring** - Track your error rate with visual feedback
- ⏱️ **Multiple durations** - 15s, 30s, 60s, or 120s tests
- 📝 **Three modes**:
  - **Quotes** - Inspirational quotes and famous sayings
  - **Code** - JavaScript snippets for developers
  - **Words** - Common English words for pure speed
- ⌨️ **Keyboard heatmap** - See which keys trip you up most
- 🔊 **Typing sounds** - Optional audio feedback (toggleable)
- 📊 **History tracking** - Your last 50 tests saved locally
- 🏆 **Personal best** - Tracks your highest WPM
- 🌙 **Beautiful dark theme** - Easy on the eyes
- 📱 **Responsive design** - Works on mobile and desktop

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Tab` + `Enter` | Restart test |
| `Escape` | Close results / Reset |
| Any key | Start typing (when focused) |

## Stats Explained

- **WPM** (Words Per Minute) - Correct characters ÷ 5 ÷ minutes elapsed
- **Raw WPM** - Total characters typed ÷ 5 ÷ minutes (includes errors)
- **Accuracy** - Correct characters ÷ total typed × 100

## Tech Stack

- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks
- Web Audio API for typing sounds
- LocalStorage for persistence
- GitHub Pages for hosting

## Local Development

```bash
# Clone the repo
git clone https://github.com/claytondb/typetest.git
cd typetest

# Open in browser (no build step needed!)
open index.html
# or
python -m http.server 8000
```

## Contributing

Feel free to open issues or submit PRs!

## License

MIT

---

Built with ☕ by [Nero](https://github.com/claytondb)

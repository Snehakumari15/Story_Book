# 📖 Story World

A cozy, interactive storybook web app built with **pure HTML & CSS** — read inspiring moral stories, click on tricky words to see their meaning, listen to stories being read aloud, and personalize your reading experience with dark mode, adjustable font size, and more.

🔗 **Live Demo:** [snehakumari15.github.io/Story_Book](https://snehakumari15.github.io/Story_Book/)

---

## ✨ Features

- 📚 **17 Illustrated Moral Stories** — classic tales like *The Lion and the Mouse*, *The Hare and the Tortoise*, *The Honest Woodcutter*, and more, each with its own moral lesson.
- 🔊 **Listen / Stop Listen** — every story can be read aloud using the browser's built-in text-to-speech, no external audio files needed.
- 💡 **Click-to-See Word Meaning** — difficult English words are highlighted; click on one to instantly see its Hindi meaning in a popup.
- 🌙 **Dark Mode** — toggle a full dark theme across the entire site.
- 🔤 **Font Size Control** — switch between small, medium, and large text for comfortable reading.
- 🏷 **Category Filter** — filter stories by theme: Courage, Honesty, Kindness, Wisdom, Greed, and more.
- ⭐ **Favorites** — bookmark your favorite stories and switch to a "My Favorites Only" view.
- 🎨 **Hover Preview Cards** — hover over a story title in the sidebar to see a quick one-line preview.
- 📖 **Flip-Book Page Animation** — a realistic 3D page-turn effect when switching stories.
- 🔵 **Page-Dots Navigation** — quickly jump between all 17 stories using dot indicators.
- 🖨 **Print-Friendly View** — a dedicated Print button generates a clean, distraction-free printout of any story.
- 📊 **Story Info Panel** — each story has its own category, theme, moral value, and reading-time indicator.
- ✍ **Drop Caps** — stylized first letters for a classic storybook feel.

---

## 🛠 Tech Stack

- **HTML5** — semantic structure and content
- **CSS3** — all interactivity (theming, filtering, favorites, animations) is built using pure CSS tricks like the checkbox/radio hack and the modern `:has()` selector
- **Minimal Vanilla JavaScript** — used only for two things that genuinely require it:
  - Text-to-speech (`SpeechSynthesis` API) for the Listen button
  - Triggering the browser's print dialog for the Print button

No frameworks, no build tools, no external libraries — just a browser and these two files.

---

## 📂 Project Structure

```
Story_Book/
├── index.html      # All 17 stories, structure & content
├── style.css        # All styling, theming & interactivity logic
└── images/           # Story illustrations
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `index.html` in any modern browser (Chrome, Edge, or Safari recommended for full `:has()` support).
3. Pick a story from the sidebar, click words to see meanings, hit Listen to hear it read aloud, and explore the theme toggles up top!

---

## 🔭 Future Improvements

- Search bar for stories
- More stories & glossary words
- Reading progress tracker
- Multi-language voice support

---

## ✍ Author

**Sneha Kumari**
Made with ❤️ to make moral stories fun, accessible, and interactive for readers of all ages.

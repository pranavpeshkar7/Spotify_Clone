# 🎧 Spotify Web Player UI Clone

A static, pixel-conscious recreation of the Spotify Web Player home screen, built with **pure HTML and CSS**. This mini project focuses on layout techniques, dark-theme styling, and custom-styled form controls.

> ⚠️ This is a UI-only project. There is no audio playback or JavaScript logic; the player bar, sliders, and buttons are visual only.

## 📸 Preview

<!-- Add a screenshot: put it in /assets and update the path below -->
![Spotify Web Player Clone](./assets/logo.png)

## ✨ Features

- **Three-panel layout**: sidebar (navigation + library), scrollable main content, and a fixed bottom music player
- **Sticky top navigation** with Explore Premium, Install App, and profile icon
- **Card sections** for *Recently Played*, *Trending now near you*, and *Featured Charts*, built with Flexbox and wrapping
- **Library empty-state boxes** ("Create your first playlist", "Browse podcasts")
- **Custom-styled range sliders** for the progress bar and volume using `::-webkit-slider-runnable-track` and `::-webkit-slider-thumb`
- **Hover effects** on nav items, icons, cards, and player controls
- **Responsive tweak**: secondary buttons are hidden below 1000px using a media query
- Spotify-style dark palette (`#000`, `#121212`, `#232323`) with green accent (`#1bd760`)

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| HTML5 | Page structure |
| CSS3 | Flexbox, sticky positioning, media queries, pseudo-elements |
| Font Awesome 7 | Icons (loaded via CDN) |
| Google Fonts (Montserrat) | Typography |

## 📁 Project Structure

```
spotify-clone/
├── index.html
├── style.css
├── assets/
│   ├── logo.png
│   ├── library_icon.png
│   ├── card1img.jpeg … card6img.jpeg
│   ├── player_icon1.png … player_icon5.png
│   ├── backward_icon.png, forward_icon.png
│   └── mini_player.png, mike.png, stack.png, pc.png, volume.png
└── README.md
```

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the folder
   ```bash
   cd <repo-name>
   ```
3. Open `index.html` in your browser (or use the VS Code **Live Server** extension).

An internet connection is needed for Font Awesome and Google Fonts.

## 📚 What I Learned

- Building multi-panel layouts with Flexbox and `position: fixed` / `sticky`
- Styling native `<input type="range">` elements with vendor pseudo-elements
- Structuring reusable card components with consistent spacing
- Using media queries to adapt UI at smaller widths

## 🔮 Future Improvements

- [ ] Make the layout fully responsive for tablets and mobile
- [ ] Add JavaScript for play/pause, progress, and volume control
- [ ] Add real audio playback with the HTML5 Audio API
- [ ] Add a working search view and playlist creation
- [ ] Style range sliders for Firefox (`::-moz-range-*`)

## ⚖️ Disclaimer

This project is for **educational purposes only**. Spotify and its logo are trademarks of Spotify AB. This project is not affiliated with or endorsed by Spotify.

## 👤 Author

**Pranav**
GitHub: [@your-username](https://github.com/pranavpeshkar7)

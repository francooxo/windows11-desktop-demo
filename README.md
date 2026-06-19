# Windows 11 Pro — Desktop Demo

A single-file HTML/CSS/JS recreation of the Windows 11 desktop experience, built as a learning project. No frameworks, no build step — just open `index.html` in a browser.

## Live Demo

Open `index.html` directly in any modern browser, or enable GitHub Pages for this repo to view it online.

## Features

- **Desktop** with clickable icons (Recycle Bin, Edge, This PC, Notepad)
- **Start menu** with pinned app tiles, a live search filter, and a Recommended section
- **Taskbar** with a working Start button, app shortcuts, system tray, and a live clock
- **Draggable windows** that can be opened, minimized, maximized, and closed
- **Working mini-apps**:
  - 🧮 Calculator (real arithmetic)
  - 📝 Notepad (typeable text area)
  - ⚙️ Settings (dark/light mode toggle, accent color picker, Wi-Fi/Bluetooth toggles)
  - 📁 File Explorer (sidebar + file grid)
  - 🌐 Edge (mock browser window)
  - 💻 System Properties (Windows 11 Pro specs)
- **Power menu** with Sleep, Shut down, and Restart (includes a shutdown animation and reboot)
- **Toast notifications** for tray icons and unbuilt apps
- Keyboard support (`Esc` closes open menus) and visible focus states for accessibility

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (no dependencies)

## Project Structure

```
.
├── index.html   # Entire app: markup, styles, and script in one file
└── README.md
```

## Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/francooxo/windows11-desktop-demo.git
   ```
2. Open `index.html` in your browser, or use a tool like VS Code's **Live Server** extension for auto-reload.

## Status

This is a work-in-progress learning project built while studying HTML fundamentals. Some apps (Mail, Store, Camera, Word, Excel, etc.) are placeholders that show a notification rather than opening a full window.

## License

This project is for educational purposes.
# Winaborator

**A Windows desktop workspace for building with multiple AI agents.**

Winaborator gives you an infinite canvas where you can open terminals, browse files, edit code, and manage multiple AI agent workflows — all in one place.

> ⚠️ **Early Beta** — This is early-stage software. Expect bugs and rough edges. [Create an issue](https://github.com/jakeefr/winaborator-ai/issues) if you run into something.

---

![Winaborator Canvas](inside.png)

---

## What is Winaborator?

Winaborator is a Windows-native desktop app built for developers who work with multiple AI agents at the same time. Instead of juggling separate terminal windows, editors, and file browsers, everything lives on one shared infinite canvas you can pan, zoom, and organize freely.

> **Inspired by [Collaborator](https://github.com/collaborator-ai/collab-public)** — I wanted to use it, but it wasn't available for Windows. So I built a Windows-native version from the ground up.

---

## Screenshots

| Welcome Screen | Canvas with Terminals | File Tree/Baackground |
|---|---|---|
| ![Welcome](welcome.png) | ![Canvas](canvas.png) | ![Inside](inside.png) |

---

## Features

- **Infinite canvas** — Pan and zoom a dot-grid workspace with snap-to-grid positioning
- **Terminal tiles** — Open multiple terminals directly on the canvas
- **Code editor tiles** — Edit source files without leaving the app (Monaco Editor)
- **Note / Markdown tiles** — Write and preview markdown on the canvas
- **Image tiles** — View image files inline
- **File browser** — Left-side panel with full file tree for your workspace
- **File search** — `Ctrl+K` to search across your project instantly
- **Sessions panel** — Right-side panel showing live status of all open terminals
- **Workspace graph** — Visual graph of your project's file structure
- **Background presets** — Plain, Midnight, Slate, Ember, Ocean
- **Persistent state** — Window size, layout, tiles, and background saved automatically

---

## Download

> **Windows only** — requires Windows 10 or later.

👉 **[Download the latest release →](https://github.com/jakeefr/winaborator-ai/releases/latest)**

1. Download `Winaborator-Setup-x.x.x.exe` from the latest release
2. Run the installer
3. Launch Winaborator from your desktop or Start menu

No Node.js or other prerequisites needed — the installer bundles everything.

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Shift+O` | Add workspace |
| `Ctrl+K` | Open file search |
| `Ctrl+=` | Zoom in |
| `Ctrl+-` | Zoom out |
| `Ctrl+0` | Reset zoom |
| `F2` | Rename selected file |
| `Delete` | Move selected file(s) to recycle bin |
| `Escape` | Close viewer or search |

---

## Built With

- [Electron](https://www.electronjs.org/)
- [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [xterm.js](https://xtermjs.org/) + [node-pty](https://github.com/microsoft/node-pty)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- [D3](https://d3js.org/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [electron-vite](https://electron-vite.org/)
- [electron-builder](https://www.electron.build/)

---

## Reporting Bugs

This is early beta software — bugs are expected. If you find one:

1. [Open an issue](https://github.com/jakeefr/winaborator-ai/issues/new)
2. Include your Windows version, what you were doing, and what happened
3. Screenshots or screen recordings are very helpful

---

## License

© 2025 Jake. All rights reserved.  
This software is provided as-is for personal use. Source code is not publicly available.

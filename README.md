# 📖 Narrative Tale Studios

### A Professional Visual Story Builder with Node-Based Story Mapping

---

## 📚 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [User Guide](#user-guide)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Theme System](#theme-system)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [FAQ](#faq)

---

## 🎯 Overview

**Narrative Forge Pro** is a professional-grade visual story builder designed for game developers, writers, and narrative designers. It combines an intuitive node-based story mapping system with a powerful scene editor, making it easy to create, visualize, and manage complex branching narratives.

**Inspired by tools like Twine and Arcweave**, this tool is perfect for:
- 🎮 **Game Developers** - Create branching dialogue and quest structures
- 📝 **Writers** - Visualize complex narrative paths
- 🎭 **Interactive Fiction Creators** - Design choose-your-own-adventure stories
- 🧠 **Story Designers** - Map out character arcs and plotlines

---

## ✨ Features

### 🗺️ **Visual Node-Based Story Map**
- **Drag & Drop Nodes** - Intuitive node positioning
- **Color-Coded Nodes** - Visual distinction between node types
- **Real-Time Connections** - See story flow at a glance
- **Auto-Layout** - Automatically arrange nodes for optimal viewing
- **Zoom & Pan** - Navigate large story structures with ease

### 📝 **Powerful Scene Editor**
- **Scene Creation** - Add unique IDs, speakers, and dialogue
- **Branching Choices** - Create complex decision trees
- **Continue System** - Linear story progression
- **Timer Support** - Auto-advance scenes with timers
- **Quick Scene Creation** - Create linked scenes on the fly

### 🎨 **Visual Feedback System**
- **Connection Highlighting** - Click any node to see its connections
- **Parent/Child Detection** - See both incoming and outgoing connections
- **Glow Effects** - Color-coded connection indicators
- **Particle Effects** - Visual flow indicators
- **Fade Effects** - Non-connected nodes fade to black and white

### 🎭 **Professional Theme System**
- **6 Beautiful Themes** - Dark, Light, Ocean, Forest, Sunset, Purple
- **Persistent Preferences** - Your theme choice is saved
- **Color-Coordinated UI** - Everything adapts to your theme

### 💾 **Data Management**
- **Export Story JSON** - Save your work as structured data
- **Import Stories** - Load existing narratives
- **Auto-Save** - Optional automatic saving
- **Import from HTML** - Convert Twine/Arcweave compatible formats

### 🖱️ **Interactive UI**
- **Custom Cursor Trail** - Premium cursor effects
- **Smooth Animations** - Professional feel
- **Responsive Design** - Works on desktop and tablet
- **Keyboard Shortcuts** - Power-user friendly

---

## 🚀 Installation

### Option 1: Direct Download
1. Download the `index.html` file from the repository
2. Open it in any modern web browser
3. Start building your story!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/narrative-forge.git
cd narrative-forge
# Open index.html in your browser
```

### Option 3: Use a Local Server (Recommended)
For the best experience, use a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

### Browser Compatibility
- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Edge (Latest)
- ✅ Safari (Latest)
- ✅ Opera (Latest)

---

## 🎬 Quick Start

### 1. Creating Your First Scene
```
1. Enter a unique Scene ID (e.g., "start")
2. Add a Speaker (e.g., "Narrator")
3. Write the Dialogue
4. Choose Interaction Type: "Continue" or "Choices"
5. Click "Save Scene"
```

### 2. Building a Branching Story
```
1. Create your first scene (e.g., "start")
2. Switch to "Choices" mode
3. Add choices with target scene IDs
4. Create new scenes for each choice
5. Save and watch the node map update!
```

### 3. Visual Navigation
```
1. Click any node to highlight its connections
2. Purple lines = Parent connections (incoming)
3. Colored lines = Child connections (outgoing)
4. Click blank canvas to clear focus
5. Drag nodes to rearrange the map
```

---

## 📖 User Guide

### 🏗️ Scene Editor Panel

#### **Scene ID**
A unique identifier for your scene. Use letters, numbers, underscores, or hyphens.
- ✅ Valid: `start`, `forest_entrance`, `scene-1`
- ❌ Invalid: `start scene`, `scene@1`

#### **Speaker**
The character or narrator speaking in this scene.

#### **Dialogue**
The main text content of the scene. This can be narration, dialogue, or descriptive text.

#### **Interaction Type**
- **🎲 Choices** - Branching narrative with multiple options
- **➡️ Continue** - Linear story progression to the next scene

#### **Timer**
Auto-advance the scene after X seconds. Use `0` for no timer.

### 🗺️ Node Map Panel

#### **Node Types**
- 🟢 **Start Node** - Entry point of the story
- 🔵 **Choice Node** - Has branching options
- 🟣 **Continue Node** - Linear progression
- 🔴 **End Node** - Terminal point

#### **Connection Types**
- 🔵 **Continue** - Blue line (standard flow)
- 🟢 **Choice** - Green dashed line (branching)
- 🟡 **Loop** - Yellow dashed line (cyclical)
- 🔴 **End** - Red line (termination)
- 🟣 **Parent** - Purple dashed line (incoming)

#### **Node Interactions**
- **Click Node** - Highlight all connections
- **Click Again** - Clear focus
- **Click Blank Canvas** - Clear focus
- **Drag Node** - Reposition on the map
- **Scroll** - Zoom in/out
- **Drag Canvas** - Pan the view

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + S` | Save current scene |
| `Ctrl + Shift + A` | Toggle Auto-Save |
| `L` | Auto-Layout Nodes |
| `0` | Reset Map View |
| `Esc` | Clear Node Focus |
| `Mouse Wheel` | Zoom In/Out |
| `Drag Canvas` | Pan Map |

---

## 🎨 Theme System

### Available Themes

| Theme | Icon | Description |
|-------|------|-------------|
| **Dark** | 🌙 | Sleek dark mode (default) |
| **Light** | ☀️ | Clean bright interface |
| **Ocean** | 🌊 | Calming blue tones |
| **Forest** | 🌲 | Earthy green theme |
| **Sunset** | 🌅 | Warm orange/red |
| **Purple** | 🔮 | Elegant purple palette |

### How to Change Themes
1. Click the **Theme** button in the navbar
2. Select your preferred theme from the dropdown
3. The theme changes immediately and persists

---

## 📁 Project Structure

```
narrative-forge/
├── index.html          # Main application file
├── README.md          # This file
├── LICENSE            # MIT License
└── assets/            # Optional assets folder
    ├── screenshots/   # Screenshots for documentation
    └── icons/         # Custom icons
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Bug Reports
1. Check if the issue already exists
2. Create a new issue with:
   - Clear description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots if applicable

### Feature Requests
1. Check if the feature already exists
2. Create a new issue with:
   - Clear description
   - Use case
   - Mockups or examples

### Pull Requests
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

---

## ❓ FAQ

### General Questions

**Q: Is this tool free to use?**
A: Yes! Narrative Forge Pro is completely free and open-source under the MIT license.

**Q: Do I need an internet connection?**
A: No, the offline version works entirely in your browser.

**Q: Where is my data stored?**
A: Your story data is stored locally in your browser. Export your story as JSON to save it permanently.

### Troubleshooting

**Q: The node map is not showing nodes.**
A: Try clicking the "Layout" button to auto-arrange nodes. Make sure you've saved at least one scene.

**Q: My nodes fly away when dragging.**
A: This has been fixed in v3.0. Make sure you're using the latest version.

**Q: The theme isn't changing.**
A: Try clearing your browser cache or refreshing the page.

**Q: I can't export my story.**
A: Make sure you have at least one scene saved. The export button only works when scenes exist.

---

## 🔮 Future Roadmap

- [ ] **Collaborative Editing** - Real-time multi-user editing
- [ ] **Cloud Storage** - Save and sync stories online
- [ ] **Export Formats** - Twine, Ink, JSON, etc.
- [ ] **Undo/Redo** - Full history management
- [ ] **Search & Replace** - Find and edit across all scenes
- [ ] **Story Statistics** - Word count, branch count, etc.
- [ ] **Preview Mode** - Play through your story
- [ ] **Custom Themes** - Create your own color schemes

---

## 🙏 Acknowledgments

- **Inter Font** - Beautiful typography
- **Font Awesome** - Icons
- **PeerJS** - P2P networking (for collaborative version)
- **All Contributors** - Your feedback and contributions make this better!

---

## 📞 Contact & Support

- **GitHub Issues**: [Create an issue](https://github.com/yourusername/narrative-forge/issues)
- **Discussions**: [Join the discussion](https://github.com/yourusername/narrative-forge/discussions)

---

**Built with ❤️ for storytellers everywhere.**

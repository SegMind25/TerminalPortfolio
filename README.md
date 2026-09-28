# Terminal Portfolio — creative experience update

The single-file `index.html` now includes an animated boot, command typewriter,
five themes (matrix, cyberpunk, vaporwave, monochrome, solarized), and eight UI
languages (en, fr, ar, ja, zh, es, de, pt), including Arabic RTL support.

New commands include `theme`, `lang`, `play` (ASCII Snake), `hack`, `cat resume`,
and `sudo hire me`. Existing filesystem commands, history, completion, content,
and social links are preserved. `projects` now displays an interactive gallery
with modal details and the original GitHub destination. `resetfs confirm` restores
the virtual filesystem. File operations affect only the in-memory simulation.

Open `index.html` directly in a modern browser, or serve it over HTTP. No build
step is required. GSAP 3.13, Three.js r168, Tone.js 15.1.22, and fonts load from
CDNs. Advanced effects degrade to WAAPI/CSS/Canvas when unavailable; core commands
work without those network resources. WebGPU falls back to WebGL2, then Canvas.
Signals and function decorators use browser-compatible JavaScript helpers.

Sound is off by default; enable it with the title-bar audio button. The yellow
window button toggles effects. Reduced-motion settings suppress animations.
Escape skips boot or exits Snake; Ctrl+C cancels an operation; Ctrl+L clears.
Project dialogs support Escape and restore keyboard focus.

Owner contact configuration is near the start of the inline script. No email
address or downloadable resume was supplied, so their availability is stated
honestly until `owner.email` and `owner.resume` are configured.

Validation: Chromium/Brave direct-file and HTTP browser checks covered existing
commands, file mutations, all themes and languages, Arabic RTL, Snake, dialogs,
completion/history, reduced motion, blocked CDNs, live libraries/audio, and
320px/mobile/tablet layouts. No uncaught page errors in these checks. Native
WebGPU hardware, Safari, Firefox, and physical mobile keyboards were not tested.

The original project documentation is retained below.

---

# 🚀 SegMind25 | Advanced Terminal Portfolio v2.0

Welcome to **SegMind25's Interactive Terminal Portfolio** — a fully-featured, browser-based terminal emulator that showcases my work, skills, and projects in the most authentic Linux terminal experience possible.

## ✨ Features

### 🖥️ **Realistic Terminal Emulator**
- **20+ Authentic Commands**: Full support for real Linux commands with proper flags and arguments
- **Virtual File System**: Navigate through directories, create files, and manage a simulated filesystem
- **Tab Completion**: Smart autocomplete for commands and file paths
- **Command History**: Navigate through previous commands using ↑/↓ arrow keys
- **Premium Design**: Modern dark theme with smooth animations and glowing effects

### 💻 **Supported Commands**

#### Navigation
- `ls [-l] [-a] [path]` — List directory contents (supports long format and hidden files)
- `cd [path]` — Change directory (supports `.`, `..`, `~`, absolute/relative paths)
- `pwd` — Print working directory
- `tree` — Display directory tree structure with visual branches

#### File Operations
- `cat [file]` — Display file contents
- `touch [file]` — Create empty file
- `mkdir [dir]` — Create directory
- `rm [file/dir]` — Remove file or directory

#### Utilities
- `echo [text]` — Print text to terminal
- `clear` — Clear terminal screen
- `history` — Show command history with line numbers
- `date` — Display current date and time
- `whoami` — Display user information

#### Portfolio Commands
- `help` — Show comprehensive command list
- `about` — About SegMind25 with formatted presentation
- `skills` — Display technical skills categorized by area
- `contact` — Show contact information with clickable social links
- `socials` — Alias for contact command
- `neofetch` — System information display (terminal-style)

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5, CSS3 (no frameworks)
- **Typography**: JetBrains Mono (Professional monospace font)
- **JavaScript**: Vanilla JS with advanced terminal emulation
- **Design**: Modern CSS with variables, gradients, and animations
- **Architecture**: State-driven file system simulation

## 📂 Virtual File System

```
/home/segmind/
├── README.md          # Portfolio introduction
├── about.txt          # Detailed about information
├── skills.txt         # Technical skills overview
├── contact.txt        # Contact information
└── projects/          # Projects directory
    └── README.md      # Projects overview with GitHub link
```

## ⌨️ Keyboard Shortcuts

- **Tab** — Autocomplete commands and filenames
- **↑/↓ Arrows** — Navigate command history
- **Ctrl+L** — Clear screen (same as `clear` command)
- **Ctrl+C** — Cancel current input
- **Enter** — Execute command

## 🎨 Design Features

- **Glassmorphism Effects**: Modern blur and transparency
- **Smooth Animations**: Fade-in effects and slide animations
- **Color-Coded Output**: 
  - Green: Success messages, user prompt
  - Red: Error messages
  - Yellow: Warnings and section headers
  - Cyan: Info messages and clickable links
  - Purple: Current directory path
  - Blue: Directory names
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Traffic Lights**: macOS-style window controls
- **Real-time Clock**: Live time display in header and footer

## 🚀 Quick Start

1. **Open the Terminal**
   ```bash
   # Simply open index.html in any modern browser
   open index.html
   ```

2. **Try These Commands**
   ```bash
   help              # View all available commands
   ls -la            # List all files in long format
   tree              # View directory structure
   cat README.md     # Read the portfolio introduction
   cd projects       # Navigate to projects folder
   about             # Learn about SegMind25
   skills            # View technical skills
   contact           # Get social media links (clickable!)
   neofetch          # Display system info
   ```

3. **Explore the File System**
   ```bash
   pwd               # See current directory
   cd ~              # Go to home directory
   ls                # List files
   cat about.txt     # Read about file
   cat skills.txt    # Read skills file
   ```

## 🔗 Connect with SegMind25

| Platform | Link |
| :--- | :--- |
| **YouTube (Gaming)** | [@SegMind25](https://www.youtube.com/@SegMind25) |
| **YouTube (Coding)** | [@SegError](https://www.youtube.com/@SegError) |
| **TikTok** | [@segmind25](https://www.tiktok.com/@segmind25) |
| **Discord** | [Join Community](https://discord.gg/WeUYH3x9Cr) |
| **GitHub** | [SegMind25](https://github.com/SegMind25) |

## 🎯 What Makes This Special?

Unlike typical portfolio websites, this terminal provides:

✅ **Authentic Terminal Experience** — Feel like you're using a real Linux terminal  
✅ **Interactive File System** — Create, navigate, and explore directories  
✅ **Full Command Support** — 20+ working commands with proper flags  
✅ **Tab Completion** — Productivity features like a real terminal  
✅ **Command History** — Never retype commands again  
✅ **Gorgeous Design** — Premium aesthetics with smooth animations  
✅ **Fully Responsive** — Works perfectly on any device  
✅ **Zero Dependencies** — Pure vanilla JavaScript, no frameworks needed  

## 📜 Command Examples

```bash
# Basic navigation
ls                    # List files in current directory
ls -l                 # Long format with details
ls -a                 # Show hidden files
cd projects           # Move to projects folder
pwd                   # Show current path
cd ..                 # Go up one directory

# File operations
cat README.md         # Read a file
touch newfile.txt     # Create a file
mkdir newfolder       # Create a directory
rm newfile.txt        # Remove a file

# Portfolio commands
about                 # About me
skills                # My technical skills
contact               # Social media (clickable links!)
neofetch              # System display

# Utilities
echo "Hello World!"   # Print text
history               # View command history
date                  # Current date/time
clear                 # Clear screen
```

## 🌟 Features Roadmap

Current version: **v2.0** (Fully Functional Terminal Emulator)

Possible future enhancements:
- vi/vim editor simulation
- grep command for searching
- Pipe support (`|`)
- Command aliases
- Downloadable resume/CV
- Easter eggs and hidden commands

## 📄 License

MIT License - Feel free to fork and customize for your own portfolio!

---

**© 2026 SegMind25. All Rights Reserved.**  
*Built with ❤️ for the Linux community and terminal enthusiasts.*

**Live Demo**: Just open `index.html` in your browser!

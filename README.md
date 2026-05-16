# 🦉 Owlnest

**Your mental context, preserved.**

A lightweight desktop application that automatically captures your progress, plans, and thoughts the moment you step away from your work—so you never lose your flow again.

[![Owlnest Release](https://img.shields.io/github/v/release/ascxiao/owlnest-releases?color=22c55e&label=Latest%20Beta&style=for-the-badge)](https://github.com/ascxiao/owlnest-releases/releases/latest)


<img width="1252" height="789" alt="image" src="https://github.com/user-attachments/assets/00e17ec4-a64e-4f8a-b401-6b96e60d75aa" />

## Table of Contents

- [The Problem](#the-problem)
- [The Solution](#the-solution-owlnest)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Perfect For](#perfect-for)
- [Why Owlnest?](#why-owlnest)
- [Status](#-status-beta)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Philosophy](#philosophy)
- [Privacy](#privacy)
- [Feedback & Support](#feedback--support)
- [License](#license)

<img width="1913" height="1016" alt="image" src="https://github.com/user-attachments/assets/7a5eda00-8755-4bbf-8530-7fd6b21436f7" />

## The Problem

You're deep in the zone. Three hours into a Stardew Valley farming session, and you've just mapped out an entire seasonal strategy. New farm layout, crop rotation, building plans. You close the game with confidence.

Two days later, you boot it up again. Your brain is blank.

**Where exactly were you going with the farm? What was that one thing you needed to build first?** You spend 20 minutes just remembering where you left off—and half that time, you're clicking around hoping muscle memory kicks in.

This isn't just a gaming problem.

You're halfway through a Photoshop design. Client mockups scattered across your workspace. You've made specific adjustments that took hours to dial in—color grading, layer masks, font adjustments. It's 11 PM. You close Photoshop.

A week later, you open the file again. **Did I use this font? What was the exact hex color I landed on? What was my next design iteration supposed to be?** You're not working—you're **remembering**.

Or you're deep in a coding session. You've fixed three bugs, refactored a module, and identified the next optimization opportunity. You close your IDE. A few days pass. When you come back, you've lost the thread. The context is gone. Now you're context-switching instead of **code-switching**.


## The Solution: Owlnest

**Owlnest is a "save state" for your brain.**

The moment you close any application you're tracking—a game, design software, IDE, creative tool—a sleek modal pops up with two simple questions:

- **"Where did you leave off?"**
- **"What's your next step?"**

Type a quick note. Hit Enter. The modal disappears.

The next time you open that application, your notes appear instantly, restoring your mental context so you can pick up exactly where you left off.

No friction. No extra steps. Just a tiny moment of capture that saves you from hours of context-switching later.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7cb8d101-1983-4373-9fa0-29ef2558dbaa" />


## Key Features

### 🎯 **Instant Context Capture**
The moment you close a tracked application, Owlnest intercepts you with a frictionless modal. Jot down where you left off and what's next—takes 10 seconds.

### 🧠 **Automatic Context Restoration**
Open the same application again? Your notes appear instantly. No searching, no digging through folders. Your context is right there.

### 📊 **Beautiful Dashboard**
See all your tracked applications, your latest notes, and how many times you've recalled each context. A bird's-eye view of everything you're juggling.

### 🔐 **Completely Local**
All notes are stored on your machine in SQLite. No cloud, no servers, no privacy concerns. Works offline, instantly.

### 📱 **Cross-Platform**
Windows, macOS. One codebase. Same beautiful experience everywhere.

### ⚙️ **Lightweight & Fast**
Built with Tauri and React. ~5MB footprint. Runs quietly in your system tray. Zero impact on performance.


## How It Works

### 1. **The Setup**
Add the applications you want to track (Stardew Valley, Photoshop, VS Code, etc.) to Owlnest.

### 2. **The Capture**
Close any tracked app. A modal pops up asking where you left off and what's next.

### 3. **The Recall**
Open that app again. Your notes appear automatically, restoring your mental context in seconds.

### 4. **The Dashboard**
Browse all your notes, see patterns in your work, and never lose context again.

## Perfect For

🎮 **Gamers** - Remember farm layouts, quest lines, building strategies, and long-term goals between sessions.

🎨 **Designers** - Capture design decisions, color schemes, client feedback, and next iteration plans in Photoshop, Figma, etc.

💻 **Developers** - Save your debugging progress, refactoring notes, and next optimization targets before closing the IDE.

✍️ **Writers** - Preserve story arcs, character notes, and plot development ideas between writing sessions.

🔧 **Makers** - Document your progress on projects, tooling decisions, and next steps for any creative work.


## Why Owlnest?

Owls symbolize wisdom and memory. They see in the dark and catch what others miss. Owlnest is your wise companion, catching the details you'd otherwise forget and nesting them safely until you need them again.


## 🚀 Status: Beta

Owlnest is currently in **active beta development**. Core functionality is stable and ready for everyday use, but we're continuously improving the experience based on user feedback.

**What's working:**
- ✅ Process detection for tracked applications
- ✅ Capture modal with instant saving
- ✅ Automatic context recall on app launch
- ✅ Dashboard with full history
- ✅ Local SQLite storage


## Installation

### Requirements
- Windows 10+ or macOS 10.13+
- 10MB disk space

### Download
Get the latest release for your platform:
- **[Windows](https://github.com/ascxiao/owlnest-releases/releases/latest)**
- **[macOS](https://github.com/ascxiao/owlnest-releases/releases/latest)**

### First Time Setup

#### **Windows**

1. Download the `.msi` installer from the releases page
2. Run the installer and follow the setup wizard
3. Launch Owlnest from your Start Menu or desktop shortcut
4. Add your applications to track
5. You're ready to go

#### **macOS**

1. Download the `.dmg` file from the releases page
2. Open the `.dmg` file (double-click)
3. Drag the Owlnest app into the Applications folder
4. Open Applications folder and double-click Owlnest

**⚠️ macOS Security Warning**

On first launch, you may see a security warning: *"Owlnest cannot be opened because the developer cannot be verified."*

This is normal for beta apps. Here's how to bypass it:

**Option 1: Right-Click Method (Easiest)**
1. In Finder, navigate to Applications
2. Right-click on Owlnest
3. Select "Open" from the menu
4. Click "Open" in the security dialog
5. The app will now run

**Option 2: System Preferences Method**
1. Try to open Owlnest normally (you'll get the security warning)
2. Go to **System Preferences** → **Security & Privacy**
3. Click the **General** tab
4. Look for "Owlnest was blocked..." message
5. Click **"Open Anyway"**
6. Owlnest will now launch

**Option 3: Terminal Method (Advanced)**
```bash
xattr -d com.apple.quarantine /Applications/Owlnest.app
```
Then launch Owlnest normally.

After the first launch, you won't see this warning again. We're working on getting a proper code signature for future releases.


## Quick Start

1. **Open Owlnest** and look at the Dashboard
2. **Add an application** you want to track (e.g., StardewValley.exe, Photoshop.exe, Code.exe)
3. **Open and close** the app once with Owlnest running
4. When the modal appears, jot down where you left off and what's next
5. **Next time you open it**, your context appears instantly


## Philosophy

Owlnest is built on a simple principle: **friction kills context.**

Every extra step you have to take to capture or retrieve context is a step away from actual work. Owlnest eliminates that friction by:

- ✨ Intercepting you at the exact moment you're leaving
- ✨ Asking just two simple questions
- ✨ Storing everything locally for instant access
- ✨ Showing your context the moment you return

No logging in. No organizing. No searching. Just smart, automatic context preservation.


## Privacy

Your data is yours. All notes are stored locally on your machine in a SQLite database. Owlnest never phones home, never tracks you, and never sends your data anywhere.


## Feedback & Support

We love hearing from our users! If you run into issues or have ideas for new features:
*   **In-App Feedback**: Use the "Send Feedback" button inside the Owlnest sidebar.
*   **Direct Support**: If the app is not launching, please feel free to open a [GitHub Issue](https://github.com/ascxiao/owlnest-releases/issues) here.
*   **Discussions**: [Join the community](https://github.com/ascxiao/owlnest-releases/discussions)

---

## License

Copyright (c) 2026 kaluroos/ascxiao. All rights reserved. This binary is provided as-is for personal use only.

---

**Made with 🦉 by kaluroos/ascxiao**

*Your context is sacred. Owlnest preserves it.*
.

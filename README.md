# Zecy

**Your Bengali AI Companion for macOS and Windows**

A Bengali-first voice AI desktop companion designed for natural conversations, intelligent assistance, and hands-free desktop automation.

**Platforms:** macOS · Windows  
**Voice Language:** Bengali  
**License:** MIT

[Download Latest Release](https://github.com/sohan-dev-0/Zecy/releases/latest) · [Features](#features) · [Installation](#installation) · [Usage](#usage) · [Troubleshooting](#troubleshooting)

---

## Overview

Zecy is an AI-powered desktop companion built to make computer interaction more natural through Bengali voice communication.

Unlike traditional voice assistants that rely on rigid commands and robotic responses, Zecy focuses on natural Bengali conversations with a warm and expressive companion personality.

More than just a voice assistant, Zecy lives on your desktop as an interactive animated character. It combines conversational AI, desktop automation, and expressive animations to create a unique personal assistant experience.

Zecy is designed for both macOS and Windows, bringing the same Bengali-first experience to users across desktop platforms.

### Bengali-First by Design

Zecy communicates exclusively in Bengali through voice interaction. From everyday conversations and intelligent responses to greetings and voice commands, the entire experience is designed around natural spoken Bengali.

---

## Features

### Natural Bengali Voice AI

- Intelligent Conversations: Ask questions, discuss ideas, and have natural everyday conversations in Bengali.
- Companion Personality: A warm and attentive personality designed to make interactions feel more personal.
- Context-Aware Greetings: Automatically delivers appropriate Bengali greetings based on the time of day.

### Hands-Free Desktop Automation

- Application Control: Register applications in Settings and open or close them using voice commands.
- Music Control: Control supported music playback without manually interacting with your computer.
- Instant Screenshots: Capture your desktop screen using simple voice instructions.

### Interactive Desktop Character

- Flexible Positioning: Drag and position Zecy anywhere on your desktop, including over the macOS Dock.
- Animated Expressions: Click Zecy to trigger reactions such as blinking, smiling, clapping, and pouting.
- Autonomous Walking: Zecy can independently stand up, walk across the screen, wave, and return to her seated position.
- Quick Context Menu: Right-click to access Settings, trigger walking animations, or play a greeting.

---

## Supported Platforms

Zecy is available for the following desktop operating systems:

| Operating System | Support |
|---|---|
| macOS | Available |
| Windows | Available |

Download the latest release and select the installation package corresponding to your operating system.

**Official Download:**  
https://github.com/sohan-dev-0/Zecy/releases/latest

---

## Installation

### macOS

Zecy is distributed independently without an Apple Developer ID certificate or Apple notarization.

As a result, macOS Gatekeeper may prevent the application from opening and display a security warning.

This is expected for applications distributed without Apple's developer signing and notarization process.

Follow the steps below to install Zecy successfully.

#### Step 1 — Download

1. Visit the official [Zecy Releases](https://github.com/sohan-dev-0/Zecy/releases/latest) page.
2. Download the latest `Zecy.dmg` file.
3. Open the downloaded DMG file.

#### Step 2 — Install the Application

1. Locate `Zecy.app` inside the opened DMG window.
2. Drag `Zecy.app` into your Applications folder.
3. Wait for the copying process to finish.
4. Eject the mounted DMG.

#### Step 3 — Remove the macOS Quarantine Attribute

Since Zecy is not signed and notarized with an Apple Developer ID, macOS may block its first launch.

To resolve this, open Terminal and execute:

```bash
xattr -cr /Applications/Zecy.app
```

This removes the quarantine attribute from the application so macOS will no longer block it solely because of that attribute.

Only run this command if you downloaded Zecy from the official GitHub repository and trust the release.

#### Step 4 — Launch Zecy

1. Open your Applications folder.
2. Locate Zecy.
3. Double-click the application.
4. Grant the required permissions when prompted.

Zecy is now installed and ready to use.

**Important:** Removing the quarantine attribute does not sign or notarize the application. It bypasses one Gatekeeper check, so only use trusted releases.

### Windows

Installing Zecy on Windows is straightforward.

1. Visit the official [Zecy Releases](https://github.com/sohan-dev-0/Zecy/releases/latest) page.
2. Download the latest Windows installation package.
3. Open the downloaded installer.
4. Follow the on-screen installation instructions.
5. Launch Zecy after installation.

If Windows SmartScreen displays a warning, verify the downloaded file's source before proceeding.

---

## First-Time Setup

After launching Zecy for the first time:

1. Complete the initial application configuration.
2. Allow microphone access when requested.
3. Open Zecy's Settings.
4. Register the applications you want to control through voice commands.
5. Start speaking naturally in Bengali.

---

## Usage

### Voice Conversations

Talk to Zecy naturally in Bengali. Ask questions, request information, or simply have a conversation.

### Application Management

Register your applications in Settings and use voice instructions to open or close them.

### Character Interaction

- Left-click to trigger animated expressions.
- Drag to change Zecy's desktop position.
- Right-click to open the context menu.
- Select the walking option to trigger movement immediately.

### Desktop Assistance

Use voice commands to control supported music playback and capture screenshots.

---

## Troubleshooting

### macOS Cannot Verify the Application

Ensure that you downloaded Zecy from the official GitHub repository. Follow the macOS installation instructions and execute the quarantine-removal command.

### Microphone Access Denied

Open your operating system's privacy settings and grant microphone permission to Zecy.

### Application Control Not Working

Check Zecy's Settings and ensure the target application has been registered correctly.

### Voice Interaction Not Responding

Check your microphone, internet connection, and the availability of any required AI services.

---

## Project Details

| Property | Information |
|---|---|
| Project | Zecy |
| Category | AI Desktop Companion |
| Platforms | macOS, Windows |
| Primary Language | Bengali |
| License | MIT |
| Source Code | GitHub |

**Repository:**  
https://github.com/sohan-dev-0/Zecy

**Latest Release:**  
https://github.com/sohan-dev-0/Zecy/releases/latest

---

## License

Zecy is open-source software distributed under the MIT License.

You are free to use, modify, and distribute this project in accordance with the terms of the license.

---

<p align="center">
  <strong>Zecy</strong>
  <br>
  A More Natural Way to Experience AI.
  <br>
  Built for Bengali. Designed for Your Desktop.
</p>

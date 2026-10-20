# Athena AI

### Your AI. Your Workspace. Your Intelligence.

Athena AI is an AI-powered desktop assistant designed to bring intelligent conversations and useful AI capabilities into a single, modern application. With a sleek interface, customizable appearance, flexible model integrations, and a new **Screen Assistant overlay**, Athena aims to make AI accessible wherever you work.

This repository contains the official downloadable builds of Athena AI. The application's source code is maintained separately and is not included in this repository.

---

## Downloads

[**Download the Latest Release**](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases/latest)

Choose the installer compatible with your operating system and processor.

| Operating System | Installer Format |
|---|---|
| Windows | `.exe` or `.msi`, depending on the release |
| Linux | `.AppImage` or `.deb`, depending on the release |
| macOS | `.dmg`, depending on the release |

Available platforms and processor architectures depend on the published release. Check the release notes before downloading.

---

## Features

### AI Conversations
Interact with supported AI models through Athena's dedicated chat interface.

### Screen Assistant Overlay
Access AI assistance through a dedicated on-screen overlay without having to keep switching back to the main Athena window.

The Screen Assistant is designed to make context-aware assistance more convenient while you work.

Depending on the implemented functionality and platform support, the overlay can provide:

- **Quick Access:** Open the Screen Assistant using its configured keyboard shortcut.
- **Screen-Aware Assistance:** Designed to capture or use screen content to help answer questions about what you're viewing.
- **Dedicated Overlay Interface:** Access the assistant through a compact panel designed to fit between the top of the screen and the Windows taskbar.
- **Contextual Help:** Get assistance with information displayed on your screen, subject to the application's implementation and configuration.

**Screen Assistant availability:** The feature is experimental and may not be available on every platform or build. Screen capture, permissions, keyboard shortcuts, and other functionality may vary. Consult the release notes for known limitations.

### Model Flexibility
Configure supported AI models and providers through the application's available settings.

### Modern Interface
Use a dedicated desktop application with a clean interface designed for convenient AI interaction.

### Customizable Appearance
Personalize Athena's appearance using the themes and interface settings available in your version.

### Configurable AI Integration
Set up supported providers and credentials through the application's settings.

Features may vary between versions and operating systems.

---

## Installation

### Windows

1. Visit the [Latest Releases](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases/latest) page.
2. Download the available Windows installer.
3. Open the downloaded installer and follow the instructions.
4. Launch Athena AI from the Start menu or desktop shortcut, if provided.

If Windows displays a security warning, verify that the installer came from the official release repository before proceeding.

### Linux

1. Download the available `.AppImage` or `.deb` package.
2. For an AppImage, open a terminal in the download directory and run:

   ```bash
   chmod +x Athena*.AppImage
   ```

3. Run the AppImage, or install the `.deb` package using your distribution's package manager.

**Note:** Screen Assistant is not currently supported in the Linux build described by the project's development configuration.

### macOS

1. Download the compatible `.dmg` file, if available.
2. Open the disk image.
3. Follow the installation instructions.
4. Launch Athena AI.

Check the release notes for Intel or Apple Silicon compatibility. Screen Assistant support on macOS may be experimental and should be verified against the specific release.

---

## Getting Started

1. Install and launch Athena AI.
2. Complete the initial setup, if required.
3. Open the model or provider settings.
4. Configure a supported AI provider and enter any required API credentials.
5. Save your settings and start chatting.

Some AI providers require an API key, an internet connection, or a separate account. Usage limits and pricing depend on the provider.

---

## Using the Screen Assistant Overlay

The Screen Assistant is designed to provide faster access to Athena while you are working in other applications.

### How to use it

1. Launch Athena AI.
2. Open **Settings → Screen Assistant**.
3. Check the configured keyboard shortcut.
4. Press the shortcut to open the overlay.
5. If screen-aware features are available, test them with content that you are comfortable sharing with your configured AI provider.

The overlay is intended to remain accessible without requiring you to return to the main Athena chat window every time.

### Troubleshooting the overlay

**The Screen Assistant setting says the feature is unavailable**

You may be using a build that does not include the feature. Check the release notes and download the appropriate supported build.

**The keyboard shortcut does not work**

- Check the shortcut shown in Settings.
- Confirm that another application is not intercepting the same shortcut.
- Restart Athena and try again.

**The overlay opens but does not capture the screen**

- Check whether screen capture is supported by your operating system and build.
- Review any relevant operating-system permissions.
- Remember that the feature is experimental and may have limitations.

**The overlay is positioned incorrectly**

Check for application updates and try restarting Athena. If the problem persists, report the operating system, Athena version, screen resolution, and steps that reproduce the issue.

### Platform support

- **Windows:** Intended target for the current Screen Assistant implementation.
- **macOS:** Support may be experimental and requires verification against the published build.
- **Linux:** Screen Assistant is excluded from the described Linux build.
- **Android:** Not supported by the current Screen Assistant implementation.

Platform support may change in future releases.

---

## Getting a Free Google Gemini API Key

Athena AI can use Google's Gemini models when the relevant integration is available in your version.

1. Visit [Google AI Studio](https://aistudio.google.com/apikey).
2. Sign in with your Google account.
3. Open the API Keys section.
4. Create an API key and select an appropriate Google Cloud project.
5. Copy the key.
6. Open Athena AI and navigate to its model or provider settings.
7. Select Google Gemini, enter your API key, and save your settings.

### Important notes

- Google offers free usage tiers for eligible Gemini models, subject to current quotas, eligibility, and terms.
- Free usage is not unlimited. Some models or usage levels may require billing.
- Keep your API key private. Never publish it in a repository or share it with others.
- Usage is subject to Google's current pricing and rate limits.

Official documentation: [Gemini API Key Guide](https://ai.google.dev/gemini-api/docs/api-key)

---

## Privacy and Security

Athena AI's data handling depends on the features you use and the providers you configure.

- Messages sent to external AI providers may be processed by those providers.
- Screen Assistant functionality may involve capturing screen content. Treat screenshots and visible information as potentially sensitive.
- Avoid exposing passwords, banking details, confidential documents, or private messages to screen-aware features.
- Review your selected provider's data-handling policies.
- Keep API keys and other credentials private.

A desktop application does not automatically mean all data stays on your device. Review the application's available privacy information before using it with sensitive material.

---

## Troubleshooting

### The installer will not open

- Confirm that you downloaded the correct installer for your operating system and processor.
- Download the file again if it appears incomplete.
- Check whether your operating system is blocking an unsigned or unnotarized application.

### The AI is not responding

- Check your internet connection when using an online provider.
- Verify your model and provider settings.
- Check your API credentials, account limits, and provider availability.

### A feature is unavailable

- Check your Athena version.
- Review the release notes for platform and feature limitations.
- Confirm that the feature is included in the build you installed.

### The application is incompatible

Check the installer filename and architecture, then download a compatible release if one is available.

---

## Updates

New versions, installers, and fixes are published in the [Athena AI Downloads Releases](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases) section.

Check the release notes before updating. Back up important local data before installing a new version.

---

## Legal and Usage

Athena AI is distributed as a compiled desktop application. Downloading the application does not transfer ownership of its intellectual property.

Third-party components may be subject to their own licences. Applicable third-party notices should accompany the relevant distribution where required.

AI-generated responses may be inaccurate or incomplete. Verify important information independently before relying on it.

---

## Source Code

This repository is dedicated to distributing Athena AI installers and release information. The application's source code is maintained separately and is not provided here.

---

**Athena AI**

*Intelligence, shaped around your workspace.*

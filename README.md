# ⚔️ Athena AI

### Your AI. Your Workspace. Your Intelligence.

Athena AI is an AI-powered desktop assistant designed to bring intelligent conversations, hands-free voice interaction, screen-aware assistance and local AI capabilities into a single, modern application.

With a sleek interface, customizable appearance, flexible AI model integrations and a dedicated Screen Assistant overlay, Athena aims to make AI accessible wherever you work.

Choose between cloud-based AI providers and locally running models, interact with Athena using your voice, and access AI assistance without constantly switching between applications.

This repository contains the official downloadable builds of Athena AI. The application's source code is maintained separately and is not included in this repository.

---

## Downloads

**[Download the Latest Release](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases/latest)**

Choose the installer compatible with your operating system and processor.

| Operating System | Installer Format |
|---|---|
| Windows | `.exe` or `.msi`, depending on the release |
| Linux | `.AppImage` or `.deb`, depending on the release |
| macOS | `.dmg`, depending on the release |
| Android | `.apk`, if available in the release |

Available platforms and processor architectures depend on the published release. Check the release notes before downloading.

---

## Features

### 🎙️ Voice Assistant

Interact with Athena naturally using your voice instead of typing every prompt.

- **Wake Word Activation:** Activate Athena using its configured wake phrase.
- **Hands-Free Interaction:** Speak to Athena without manually entering messages.
- **Voice Responses:** Listen to AI-generated responses through text-to-speech.
- **ElevenLabs Integration:** Support for configurable ElevenLabs voice synthesis.
- **Custom Voice Settings:** Configure available voice and speech options.
- **Stop Phrase:** Stop the current interaction without completely disabling the voice assistant.
- **Kill Phrase:** Completely deactivate the voice assistant until manually enabled again.
- **Listening Controls:** Manage voice activation, listening and playback.
- **Voice Feedback:** Receive spoken responses from supported AI providers.

The voice assistant is designed to make Athena feel more like a personal desktop assistant rather than just another chatbot.

*Voice features and wake-word functionality depend on the installed build, configuration and platform.*

### 🖥️ Screen Assistant Overlay

Access AI assistance through a dedicated on-screen overlay without constantly switching back to the main Athena window.

The Screen Assistant is designed to make context-aware assistance more convenient while you work.

Depending on the implemented functionality and platform support, the overlay can provide:

- **Quick Access:** Open the Screen Assistant using its configured keyboard shortcut.
- **Screen-Aware Assistance:** Capture or use screen content to help answer questions about what you're viewing.
- **Dedicated Overlay Interface:** Access the assistant through a compact floating panel.
- **Contextual Help:** Get assistance understanding information displayed on your screen.
- **Workspace Integration:** Access AI assistance while working in other applications.

**Screen Assistant availability:** The feature is experimental and may not be available on every platform or build. Screen capture, permissions, keyboard shortcuts and other functionality may vary. Consult the release notes for known limitations.

### 🧠 Athena Local

Run compatible AI models directly on your computer using local inference.

Athena Local provides a dedicated interface for discovering, downloading and managing supported local AI models.

Features include:

- **llama.cpp Integration:** Run compatible GGUF models through the llama.cpp inference runtime.
- **GGUF Model Support:** Work with supported quantized language models.
- **Model Discovery:** Explore supported model repositories.
- **Hugging Face Integration:** Discover models and inspect repository contents.
- **Repository Inspection:** View available files before downloading.
- **Selective Downloads:** Download specific model files instead of entire repositories.
- **Model Management:** Import, organise and manage compatible downloaded models.
- **Runtime Management:** Install and manage the supported local inference runtime.
- **Inference Configuration:** Configure supported model parameters and runtime settings.
- **Offline Inference:** Use compatible local models without sending prompts to a cloud AI provider.

Local inference performance depends on the model size, quantization, available memory, processor and graphics hardware.

*Local model support and runtime availability vary by operating system and release.*

### 💬 AI Conversations

Interact with supported AI models through Athena's dedicated chat interface.

- Dedicated AI conversation workspace.
- Multiple conversations.
- Persistent conversation history.
- Streaming responses where supported.
- Markdown response rendering.
- Model selection.
- Conversation context and memory support.
- File and attachment support where supported by the selected provider.
- Agent and Chat interaction modes.

### ⚡ Multiple AI Providers

Configure different AI providers and switch between supported models.

- OpenAI-compatible API providers.
- Google Gemini integration.
- Groq integration.
- Ollama support.
- Local GGUF models through llama.cpp.
- Custom AI endpoints where supported.
- Configurable API credentials.
- Provider and model selection.

Provider availability depends on the configured integration, model and application version.

### 📊 Token Usage Estimation

Get an approximate idea of prompt size before sending a message.

- **Input Token Estimation:** Display an approximate token count for the current request.
- **Live Updates:** Update the estimate as you compose messages.
- **Model-Aware Estimation:** Use model-specific tokenization where supported.
- **Context Awareness:** Help understand how much of a model's context window is being used where supported.
- **Optional Display:** Enable or disable the counter through Settings → General.
- **Local Processing:** Token estimation does not require sending chat content to an external counting service.

*Estimated token counts are not guaranteed to match provider billing or actual usage. Actual usage is displayed when supported by the provider.*

### 🔊 Text-to-Speech

Listen to AI responses instead of reading every message.

- Read-aloud functionality.
- ElevenLabs voice integration.
- Configurable voice settings.
- Playback controls.
- Stop speech playback when required.

### 🧩 Tools & Integrations

Extend Athena beyond ordinary AI conversations.

- Integrated tool and plugin architecture.
- Tool-assisted AI workflows.
- Configurable integrations.
- Voice and screen assistant integration.
- Support for compatible external services.

### 🎨 Modern & Customizable Interface

Use a desktop application with a modern interface designed for convenient AI interaction.

- Customizable application themes.
- Obsidian Waves theme.
- Appearance settings.
- Background customisation where supported.
- Configurable assistant behaviour.
- Dedicated settings and guides.
- Responsive interface layouts.

### 🔐 Privacy & Security

Athena provides different ways to configure how AI requests are processed.

- Local inference through supported runtimes.
- Configurable cloud AI providers.
- Application-managed settings and storage.
- User-controlled provider credentials.
- Local processing for supported local models.

**Important:** Using a desktop application does not automatically mean all data stays on your device. Cloud AI providers may process messages sent to them. Review the selected provider's data-handling policies.

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

### Android

1. Visit the [Latest Releases](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases/latest) page.
2. Download the Android APK if one is published.
3. Install the APK using Android's installation process.
4. Grant permissions when required.
5. Launch Athena AI.

Android feature availability differs from desktop versions. Desktop-specific functionality such as the Screen Assistant overlay and desktop automation is not supported by the current implementation.

---

## Getting Started

1. Install and launch Athena AI.
2. Complete the initial setup, if required.
3. Open the model or provider settings.
4. Configure a supported AI provider or local model.
5. Enter any required API credentials.
6. Save your settings and start chatting.

Some AI providers require an API key, an internet connection or a separate account. Usage limits and pricing depend on the provider.

For local inference, install the supported runtime and download or import a compatible GGUF model.

---

## Using the Voice Assistant

The Voice Assistant is designed to provide hands-free access to Athena.

### How to use it

1. Launch Athena AI.
2. Open the voice assistant settings.
3. Configure the available voice and wake-word options.
4. Enable the voice assistant.
5. Use the configured wake phrase to initiate an interaction.
6. Speak your request and listen to Athena's response.

### Voice controls

- Use the configured stop phrase to stop the current interaction.
- Use the configured kill phrase to disable the voice assistant.
- Manually enable the assistant again when needed.
- Configure supported speech and playback settings.

Voice recognition and speech synthesis may require an internet connection depending on the selected implementation.

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

Check for application updates and try restarting Athena. If the problem persists, report the operating system, Athena version, screen resolution and steps that reproduce the issue.

### Platform support

- **Windows:** Intended target for the current Screen Assistant implementation.
- **macOS:** Support may be experimental and requires verification against the published build.
- **Linux:** Screen Assistant is excluded from the described Linux build.
- **Android:** Not supported by the current Screen Assistant implementation.

Platform support may change in future releases.

---

## Using Athena Local

Athena Local allows you to run compatible AI models using your computer's available hardware.

### Basic setup

1. Launch Athena AI.
2. Open the Model Hub or Athena Local section.
3. Install the supported llama.cpp runtime if it is not already available.
4. Browse supported model repositories.
5. Inspect the repository and select a compatible GGUF file.
6. Download the model.
7. Import or register the downloaded model.
8. Configure the supported inference settings.
9. Load the model and start a conversation.

### Important notes

- GGUF models can vary significantly in size.
- Larger models require more memory.
- Quantized models can reduce memory requirements.
- GPU acceleration depends on hardware and runtime compatibility.
- Local inference does not require a cloud AI API key, but model downloads require internet access.

---

## Getting a Free Google Gemini API Key

Athena AI can use Google's Gemini models when the relevant integration is available in your version.

1. Visit [Google AI Studio](https://aistudio.google.com/apikey).
2. Sign in with your Google account.
3. Open the API Keys section.
4. Create an API key and select an appropriate Google Cloud project.
5. Copy the key.
6. Open Athena AI and navigate to its model or provider settings.
7. Select Google Gemini, enter your API key and save your settings.

### Important notes

- Google offers free usage tiers for eligible Gemini models, subject to current quotas, eligibility and terms.
- Free usage is not unlimited. Some models or usage levels may require billing.
- Keep your API key private. Never publish it in a repository or share it with others.
- Usage is subject to Google's current pricing and rate limits.

Official documentation: [Gemini API Key Guide](https://ai.google.dev/gemini-api/docs/api-key)

---

## Privacy and Security

Athena AI's data handling depends on the features you use and the providers you configure.

- Messages sent to external AI providers may be processed by those providers.
- Screen Assistant functionality may involve capturing screen content.
- Treat screenshots and visible information as potentially sensitive.
- Avoid exposing passwords, banking details, confidential documents or private messages to screen-aware features.
- Review your selected provider's data-handling policies.
- Keep API keys and other credentials private.
- Local model inference can process prompts on your device when a compatible local model is selected.

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
- Check your API credentials, account limits and provider availability.
- If using a local model, verify that the local inference runtime is available and the model has loaded successfully.

### Voice Assistant is not responding

- Check whether the voice assistant is enabled.
- Verify microphone permissions.
- Check the configured wake phrase.
- Verify your selected speech provider and connection.
- Restart the voice assistant if necessary.

### A feature is unavailable

- Check your Athena version.
- Review the release notes for platform and feature limitations.
- Confirm that the feature is included in the build you installed.

### The application is incompatible

Check the installer filename and architecture, then download a compatible release if one is available.

---

## Updates

New versions, installers and fixes are published in the [Athena AI Downloads Releases](https://github.com/lord-kirby-kirk69/Athena-Ai-Downloads/releases) section.

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

<p align="center">

**Athena AI**

*Intelligence, shaped around your workspace.*

</p>

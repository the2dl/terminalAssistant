# 🤖 assist - AI-Powered Command Line Assistant

A sleek command-line tool that provides quick, AI-powered answers to your command-line questions using Google's Gemini API.

## ✨ Features

- 🚀 Quick, focused responses to command-line queries
- 📋 Practical examples for commands
- 🎨 Beautiful, colorized output
- 🔒 Configurable AI model and safety settings
- 📝 Customizable prompt templates

## 🚀 Getting Started

1. Clone the repository
2. Set your Gemini API key in the `config` file
3. Customize the prompt in the `prompt` file
4. Create a directory named /etc/assist and put the `config` and `prompt` files in it
5. Copy the `assist` file to your `/usr/local/bin` directory

## 📚 Usage

```bash
assist
💭 Enter your query: how do you upgrade fedora?

┌──────────────────────────────────────────────────────────
  💡 You can upgrade Fedora using the `dnf` package manager, typically by first
refreshing the package list and then initiating the upgrade.

  📋 Examples:
    • sudo dnf upgrade --refresh
    • sudo dnf system-upgrade download --releasever=39 && sudo dnf system-upgrade
reboot

  📝 Note: The second example shows upgrading to Fedora version 39. Replace '39' with the
desired version.

└──────────────────────────────────────────────────────────
```

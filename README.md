# FPS Console Dev Helper

## Version Info

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**Current Core Version:**`v1.7`

Official Extensions/Changes


### Next Version

***1.7.2 / 1.8 / 2.0***

---

## 📌 Features

- ✅ **Webhook Integration** — Send status, info, or custom messages to a Discord channel.
- 🕒 **Time & Uptime** — Get system uptime and Discord-friendly timestamps.
- ⚙️ **Cross-Platform** — Works on Windows, Linux, and macOS.
- 💬 **Custom Commands** — Easily extend or modify commands.
- 🛑 **Safe Exit** — Cleanly stop the helper with `!Exit`.
- 📖 **Built-In Help** — `!Help` shows all available commands.

---

## 🚀 Quick Start

### 1️⃣ Clone the Repo

git clone https://github.com/FPSDevelops/FPSConsole.git
cd FPSConsole

### 2️⃣ Install Dependencies

pip install requests

### 3️⃣ Configure Your Webhook

Open the script and replace:

Webhook URL In = "WEBHOOK_URL_HERE"
Never share your webhook URL publicly!

### 4️⃣ Run the Script
bash
Copy
Edit
python script.py

---

## 💡 Available Commands
Command	Description	Example

!Alive	Confirms the script is running and sends an alive ping to the webhook.	!Alive
!Version	Shows the current script version.	!Version
!Time	Sends the current UTC time & Discord relative timestamp to the webhook.	!Time
!Uptime	Displays system uptime. Uses net stats srv (Windows) or uptime (UNIX).	!Uptime
!Msg	Sends a custom message to the webhook.	!Msg Hello, Discord!
!Help	Prints a help guide in the console.	!Help
!Exit	Stops the script safely.	!Exit

---

## 📃 License
### This project is licensed under the MIT License.

MIT License

Copyright (c) 2025 FPSDevelops

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

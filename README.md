[![🛡️ License: MIT 🟡](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# 📝 wordpad-installer
A simple WordPad installer to bring the lightweight text editor back to newer systems!

## 🚀 Overview

This installer was created to address a growing issue with newer Windows updates where the classic **WordPad** application has been removed or is no longer included by default. For users who miss this simple and useful text editor, this installer provides an easy way to restore WordPad on your system.

## ⚙️ What It Does

- 📂 Copies the WordPad executable and its associated `en-US` language folder into `C:\Program Files\WordPad`.
- 🖥️ Creates a shortcut to WordPad in the Windows Start Menu for easy access.
- 🗑️ Provides an **Uninstall WordPad** shortcut to completely remove WordPad and clean up shortcuts.
- 🧹 Cleans up installation files after completion.

## 🧳 Portable Edition

A **Portable edition** of this installer is also available, which extracts all files to the system’s temporary folder (`%TEMP%`) instead of `Program Files`.  
This means the files are stored in a temporary location that is cleaned up automatically after use.  
It allows you to use WordPad without installation or admin rights, making it ideal for quick testing, running on restricted systems, or carrying on a USB drive without leaving traces on the host computer.

## ℹ️ Important Notes

- 📦 This installer is packaged as a **Self-Extracting Archive (SFX)** for simple distribution.
- 🔒 Administrative privileges are required for full installation (except the Portable edition).
- 📜 The source code of the installer script is uploaded alongside this project if you wish to review or customize it.

## 🎯 Usage

1. ▶️ Run the installer as Administrator (except Portable edition).
2. ✔️ Follow any prompts during installation.
3. 🏃‍♂️ Access WordPad from your Start Menu after installation.
4. 🧹 Use the **Uninstall WordPad** shortcut in the Start Menu to remove it.

## 🤔 Why This Was Made

Microsoft’s recent Windows updates have removed WordPad from some editions, causing inconvenience for users who rely on it for lightweight text editing without installing third-party software. This project restores WordPad quickly and cleanly, keeping your system simple and familiar.

---

If you have any questions, issues, or suggestions, feel free to open an issue or contribute! 💬

---

🙏 *Thank you for using this installer!*

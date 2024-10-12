# Dark Mode Login Page for Code-Server

This repository provides a dark mode theme for the login page of [code-server](https://github.com/coder/code-server), along with VS Code logos. The theme enhances the login experience with a sleek, dark interface.

## Preview

![Preview Image](./screenshot.png)

## Features
- Dark Mode design
- Integrated VS Code branding for a consistent feel
- Customizable login page text (e.g., app name and welcome message)

## Installation Instructions

Follow the steps below to install the dark mode theme on your code-server instance. Please note that after each code-server update or upgrade, this process will need to be repeated as code-server will overwrite the theme files.

### Step-by-Step Installation

1. **Download the repository archive** and extract it into the root (`/`) directory. This will replace the original template files located in the `code-server` installation folder.

   ```bash
   # Download the theme
   wget https://github.com/sickplanet/code-server-dark-mode-login-page/archive/refs/heads/main.zip

   # Extract the archive into the root directory
   sudo unzip main.zip -d /

   # Remove the downloaded zip file
   rm main.zip

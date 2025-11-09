# Forseen – Polymarket Copy Trading Bot

A powerful and flexible software application that allows you to automatically copy trades from any user address on Polymarket. This bot provides extensive configuration options, giving you complete freedom to customize how you want to execute copy trading strategies.

## Features

- **Copy Trading**: Automatically replicate trades from any Polymarket user address
- **Highly Configurable**: Extensive settings to customize your trading behavior
- **Cross-Platform**: Available for macOS, Windows, and Linux
- **Real-time Execution**: Follow and execute trades in real-time

## Installation

### Download

Download the latest release from the [Releases page](https://github.com/Saliencee/copytrading-bot-polymarket/releases).

Choose the appropriate version for your operating system:
- **macOS**: `Forseen-macOS.zip`
- **Windows**: `Forseen-Windows.zip`
- **Linux**: `Forseen-Linux.zip`

### First-Time Launch - Security Permissions

When you launch the application for the first time, your operating system may block it for security reasons. Here's how to allow it on each platform:

#### macOS

1. **First Launch**: When you try to open the app, macOS will show a security warning
2. **Open System Settings**:
   - Go to **System Settings** → **Privacy & Security**
   - Scroll down to the **Security** section
3. **Allow the App**:
   - You'll see a message saying: *"[App Name] was blocked from use because it is not from an identified developer"*
   - Click **"Open Anyway"** or **"Allow Anyway"** button
4. **Confirm**: You may need to enter your administrator password
5. **Alternative Method**:
   - Right-click on the application
   - Select **"Open"** from the context menu
   - Click **"Open"** in the security dialog that appears

#### Windows

1. **SmartScreen Warning**: Windows Defender SmartScreen may show a warning
2. **Click "More info"** on the warning dialog
3. **Click "Run anyway"** to proceed
4. **Windows Defender** (if needed):
   - Go to **Windows Security** → **Virus & threat protection**
   - Click **"Manage settings"** under Virus & threat protection settings
   - Add the application folder to exclusions if needed

#### Linux

1. **AppImage Permission**: If using AppImage format, make it executable:
   ```bash
   chmod +x Forseen-*.AppImage
   ```

2. **Firewall/AV Warnings**: Some Linux distributions may show security warnings
   - Click **"Trust"** or **"Allow"** when prompted
   - You may need to add the application to your firewall exceptions

3. **For AppImage specifically**:
   - Right-click the file → Properties → Permissions
   - Check "Allow executing file as program"

## Usage

1. **Extract** the downloaded zip file
2. **Launch** the application
3. **Configure** your settings:
   - Enter the Polymarket user address you want to copy
   - Adjust trading parameters and preferences
   - Set up your wallet and trading limits
4. **Start** copy trading
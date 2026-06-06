# Habit Flow

Habit Flow is a simple and elegant habit tracker for macOS that helps you build consistency and stay on top of your daily goals.

## Download

Download the latest release from GitHub:

https://github.com/rahul-thatipamula/habit-flow/releases/latest

## Installation

### Option 1: Install from DMG

1. Download the latest `.dmg` file from the Releases page.
2. Open the `.dmg` file.
3. Drag **Habit Flow.app** into the **Applications** folder.
4. Eject the disk image.

### Option 2: Install with Homebrew

If you have Homebrew installed, you can install Habit Flow directly from the terminal:

```bash
brew tap rahul-thatipamula/habit-flow
brew install --cask habit-flow
```

To update Habit Flow later:

```bash
brew update
brew upgrade --cask habit-flow
```

## Installing Homebrew

If you do not have Homebrew installed, open **Terminal** and run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Verify the installation:

```bash
brew --version
```

## First Launch

Since Habit Flow is distributed directly outside the Mac App Store, macOS may prevent it from opening on first launch.

**No need to worry — Habit Flow is a completely offline application and does not collect or transmit any personal data.**

Open **Terminal** and run:

```bash
xattr -rd com.apple.quarantine /Applications/Habit\ Flow.app
open /Applications/Habit\ Flow.app
```

You only need to do this once after installing the app.

## Updating

When installing a newer version of Habit Flow, replace the existing application in the Applications folder. If macOS blocks the updated version, run the Terminal command above again.

If installed through Homebrew:

```bash
brew update
brew upgrade --cask habit-flow
```

## Requirements

* macOS 13 Ventura or later
* Apple Silicon (M1, M2, M3, M4) or Intel Mac

## Support

If you encounter any issues, please create an issue on the GitHub repository:

https://github.com/rahul-thatipamula/habit-flow

## Repository

https://github.com/rahul-thatipamula/habit-flow

# OSX-Knowledge
The OSX knowledge of a developer

Table of Contents
<!-- TOC -->

- [OSX-Knowledge](#osx-knowledge)
    - [Cycle Count](#cycle-count)
    - [Close window vs Quit app](#close-window-vs-quit-app)
    - [OSX App](#osx-app)
    - [System Tweak & Productivity Tips](#system-tweak--productivity-tips)
            - [Make key repeat as fast as possible:](#make-key-repeat-as-fast-as-possible)
            - [Try to open everything from Terminal](#try-to-open-everything-from-terminal)
            - [Copy current file path](#copy-current-file-path)
            - [Install MySQL](#install-mysql)
            - [Quickly navigate through line](#quickly-navigate-through-line)
            - [Hide the 'annoying' guest user](#hide-the-annoying-guest-user)
            - [Clean tutorial](#clean-tutorial)
            - [Thermal Compound](#thermal-compound)

<!-- /TOC -->

## Cycle Count

One Cycle Count is counted as one fully battery charged

If I lost 50% battery then charge it to 100%, it will be counted as 1/2 cycle count (NOT 1 cycle count)

Depending on cycle count, you will know when your battery need to be replaced, the Macbook Pro model from 2009 has cycle count up to 1000

So, the question is: how can I reduce my cycle count as much as possible?

The answer: your laptop should always be plugged in (always keep it in 100% battery)

Why? Because when your laptop is always in 100% state, your adapter will be used, not your battery

[Reference](https://support.apple.com/en-us/HT201585)

## Close window vs Quit app

In order to close a window (for example, Chrome tab), use the shortcut: Cmd + W

In order to completely quit an app, use the shortcut: Cmd + Q

## OSX App

This is the selective list of OSX app that I chose. The choice is based on: best free and open source

- Terminal: [iterm2](https://www.iterm2.com/)
- Spotlight alternative: [alfred](https://www.alfredapp.com/)
- Shell: [zshell and oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- Package Manager: [homebrew](https://brew.sh/)
- Code editor: [Visual Studio Code](https://code.visualstudio.com/)
- Uninstaller: [AppCleaner](https://freemacsoft.net/appcleaner/)
- Change Icon Easier: [LiteIcon](https://freemacsoft.net/liteicon/)
- Icon Pack: [FlatIcon](http://flaticns.com/)
- Browser: [Google Chrome](https://www.google.com/intl/chrome/browser/desktop/)
- Chat app: [Skype](https://www.skype.com/en/download-skype/skype-for-computer/)
- IDE: [Intellij Idea](https://www.jetbrains.com/idea/download/)
- [Feedly](https://feedly.com/)
- [Memory Cleaner 2](https://itunes.apple.com/us/app/memory-clean-2-monitor-and-free-up-memory/id1114591412?mt=12)
- Video player: [VLC](http://www.videolan.org/vlc/)
- Torrent Client: [Transmission](https://transmissionbt.com/download/)

## System Tweak & Productivity Tips

#### Make key repeat as fast as possible:

- System Preferences -> Keyboard
- Key Repeat: maximum scroll bar to **Fast**
- Delay Until Repeat: maximum scroll bar to **Short**

#### Try to open everything from Terminal

With Visual Studio Code, if I want to open current directory from terminal, I just need to type "code ." in the terminal

- Open Visual Studio Code
- Cmd + Shift + P
- Type (without quote): "Shell Command: Install 'code' command in PATH"

With Intellij Idea, if I want to open current directory from terminal, I just need to type "idea ." in the terminal

- Open Intellij Idea
- Tools -> Create Command-line launcher

#### Copy current file path

Use Cmd+C and Cmd+V to on file to copy and paste its path to the terminal

#### Install MySQL

Note: you can use homebrew to install MySQL as a package, but I prefer install the official binary from home page

- Download MySQL at: [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/)
- **Note that after you've just installed, a dialog will show you root password (1) for the first login**
- Use the password (1) to login as root, then feel free to change by follow this article: [https://dev.mysql.com/doc/refman/5.7/en/resetting-permissions.html](https://dev.mysql.com/doc/refman/5.7/en/resetting-permissions.html)

#### Quickly navigate through line

- To go to the top and bottom of the line: Cmd + Right arrow, Cmd + Left Arrow
- To nagivate through word: Alt/Option + Right Arrow/Left Arrow 

#### Hide the 'annoying' guest user

- System Preferences -> Users & Groups -> Click the lock the make changes -> Select 'Guest User' -> un-tick the 'Allow guest to login this computer'

#### Clean tutorial

The materials used to make Apple products vary; in some cases, each product might have specific cleaning requirements which vary by the part you're cleaning. To get you started, here are some tips that apply to all products:
- Use only a soft, lint-free cloth. Avoid abrasive cloths, towels, paper towels, and similar items that might cause damage. 
- Unplug all external power sources, devices, and cables.
- Keep liquids away from the product.
- Don't get moisture into any openings.
- Don't use aerosol sprays, solvents, or abrasives.
- Don't spray cleaners directly onto the item.

[Reference](https://support.apple.com/en-us/HT204172)

#### Thermal Compound

I used **Phanteks Nano Diamond** and its feel very good

### Recovery Mode

"The utilities in macOS Recovery help you restore from Time Machine, reinstall macOS, get help online, repair or erase a hard disk, and more."

Reboot -> Right after startup sound -> **Cmd + R**

[Reference](https://support.apple.com/en-us/HT201314)

### Apple Hardware Test (AHT)

"Apple Hardware Test (AHT) contains a suite of diagnostics that test the hardware of your Mac."

Reboot -> Right after startup sound -> **press and hold the D key**

[Reference](https://support.apple.com/en-us/HT201257)

### Reset NVRAM

"NVRAM (nonvolatile random-access memory) is a small amount of memory that your Mac uses to store certain settings and access them quickly. Settings that can be stored in NVRAM include sound volume, display resolution, startup-disk selection, time zone, and recent kernel panic information. The settings stored in NVRAM depend on your Mac and the devices you're using with your Mac."

Reboot -> Right after startup sound -> **Option + Cmd + P + R**

[Reference](https://support.apple.com/en-us/HT204063)

### Screenshot to clipboard

**Cmd + Control + Shift + 4** (press Space if you want to capture entire window)

You can change shortcut at **Keyboard -> Shortcuts -> Screen Shots**

### Toggle iTunes to Mini Player

** Cmd + Shift + M

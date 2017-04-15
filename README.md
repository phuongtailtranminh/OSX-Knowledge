# OSX-Knowledge
The OSX knowledge of a developer

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

## System Tweak

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
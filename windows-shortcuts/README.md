# Windows Keyboard Shortcuts

## With AutoHotkey ⌨️

Welcome to a collection of handy shortcuts meticulously crafted with AutoHotkey. Explore an array of time-saving scripts and automation tools designed to streamline your workflow and enhance your productivity. Simplify repetitive tasks and customize your computing experience with these efficient shortcuts. Dive in and discover the power of automation at your fingertips.

## Getting Started

### Installing AutoHotkey

If you haven't already installed AutoHotkey on your computer, you have two options:

1. **Download and Install**: You can download the latest version of AutoHotkey from the [official website](https://www.autohotkey.com/). Simply follow the instructions provided on the website to install AutoHotkey on your system.

2. **Using Included Installer**: Alternatively, I have included the `AutoHotkey_1.1.37.02_setup.exe` file in this repository. This is the executable installer file that I used to install AutoHotkey. You can simply run this installer to set up AutoHotkey on your system.

Choose whichever method is most convenient for you to install AutoHotkey on your computer.

### Setting Up Shortcut Scripts

Duplicate the **constants.example.ahk** file and rename it to **constants.ahk**. Then, fill in the values with your own.

### Testing Shortcuts

To test the shortcuts, simply double-click on `CapsLockCtrlEscape.ahk` or `Shortcuts.ahk`. However, to have them run automatically, you'll need to make some small configurations:

1. Press the "Win + R" keys simultaneously. This will open the "Run" dialog.

2. In the "Run" dialog, type "shell:startup" (without the quotes) and press Enter or click "OK".

3. The current user's Startup folder will open. This is where you can place shortcuts to programs or scripts you want to run when you log in to your Windows account.

4. Now, simply copy the files you want to run at startup (`CapsLockCtrlEscape.ahk`, `Shortcuts.ahk`, and `constants.ahk`) and paste them into this folder. From now on, when you log in to your user account, the .ahk script will run automatically.

### Adding New Shortcuts

If you want to create new shortcuts, you can add them directly in the `Shortcuts.ahk` file or create another .ahk file with your custom shortcuts. AutoHotkey allows you to organize your shortcuts in multiple files for better management and organization.

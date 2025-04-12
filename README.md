# Startup Greeter for Windows

A lightweight batch script that creates a personalized greeting or error-style message at system startup. Add some fun or functionality to your boot process.

## 🚀 Features
- Displays a custom message every time you log in
- Choose between a batch prompt or a Windows-style error dialog
- Optionally remove old startup scripts
- Fully customizable with minimal setup

## 📦 How to Use
1. Run the script by double-clicking the batch file (`startup-welcome.bat`)
2. Follow the prompts:
   - Enter your custom greeting or message
   - Choose your preferred display style (classic prompt or friendly error box)
   - Decide if you want to delete any existing startup script

The script will automatically generate the appropriate file in your Windows startup folder:
```
%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup
```

## 🧹 Uninstall
To remove the greeting, simply delete the generated `.bat` file from your startup folder.

## 🖥 Requirements
- Windows OS
- Ability to run batch scripts

## 🤝 Contributing
Feel free to open an issue or pull request if you find bugs or have improvements in mind.

## 📄 License
This project is open-source and unlicensed. You are free to use, modify, or repurpose the code as you see fit.
```

---

# 📋 System Requirements
- Operating System: Windows 10 or Windows 11
- Python Version: Python 3.7 or higher
- Privileges: Administrator access recommended for installing dependencies

# 📦 Step-by-Step Installation
## 1. ✅ Install Python
If you don’t have Python installed:
- Download it from python.org
- During installation, check the box that says “Add Python to PATH”
To verify installation:
```bash
python --version
```


## 2. 📥 Install Required Python Packages
Open Command Prompt and run:
```bash
pip install PyQt5 PyQtWebEngine
```


This installs the GUI and web rendering components Dive depends on.

## 3. 🚀 Launch Dive
Save the dive_browser.py file to a folder of your choice. Then run:
```bash
python dive_browser.py
```


Dive will open in a new window with a dark-themed interface and a default tab set to Startpage.

# 🧭 Basic Usage
- 🔗 Enter a URL in the top bar and press Enter to navigate
- ➕ Click the plus icon to open a new tab
- 🔄 Click the refresh icon to reload the current tab
- ❌ Close tabs using the “X” on each tab
- 📊 Watch the progress bar for page loading status

# 🧪 Developer Notes
- Dive uses a spoofed Chrome 115 user-agent for each tab
- JavaScript errors related to horizontalAlignment and verticalSpacing are suppressed for cleaner logs
- Compatibility functions are injected automatically after page load

# 🆘 Troubleshooting
- Browser won’t launch?
Make sure PyQtWebEngine is installed correctly. Try reinstalling:
```bash
pip uninstall PyQtWebEngine
```
```bash
pip install PyQtWebEngine
```
- Blank window or crash?
Update your graphics drivers and ensure hardware acceleration is enabled.
- Python not recognized?
Reinstall Python and ensure “Add to PATH” was selected during setup.

# 📎 Related Files
- README.md — Overview and features
- dive_browser.py — Main application
- INSTRUCTIONS.md — You’re reading it!

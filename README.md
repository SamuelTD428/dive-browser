# 🌊 Dive Browser
Dive is a sleek, tabbed web browser built entirely with Python and PyQt5. Designed for Windows 10/11, it offers a minimalist interface, custom user-agent spoofing, and compatibility tweaks for smoother browsing.
# 🚀 Features
- 🧭 Tabbed browsing with closable tabs
- 🛠️ Custom spoofed user-agent per tab (Chrome 115)
- 🎯 JavaScript console filtering for cleaner logs
- 🌐 URL bar with auto-https and live updates
- 🔄 Refresh button and progress bar
- 🎨 Dark-themed UI with translucent toolbar and styled input
# 🖥️ Requirements
- Windows 10 or Windows 11
- Python 3.7 or higher
- Admin privileges (recommended for installing dependencies)
# 📦 Installation
- Install Python
If you don’t have Python installed, download it from python.org and ensure it's added to your system PATH.
- Install Dependencies
Open Command Prompt and run:
pip install PyQt5 PyQtWebEngine
- Run Dive
Save the dive_browser.py file, then launch it with:
python dive_browser.py


# 🧠 How It Works
Dive uses QWebEngineView from PyQt5 to render web pages. Each tab is powered by a custom QWebEnginePage that spoofs the user-agent to mimic Chrome 115. Compatibility functions are injected into pages to suppress common JS errors.
# 🧪 Developer Notes
- Console messages containing horizontalAlignment or verticalSpacing are filtered out for clarity.
- The browser defaults to Startpage for privacy-conscious users.
- UI is styled with Qt stylesheets for a modern, dark aesthetic.
# 🛠️ Troubleshooting
- If the browser fails to launch, ensure PyQtWebEngine is installed correctly.
- For display issues, update your graphics drivers and ensure hardware acceleration is enabled.
# 📁 File Structure
dive_browser.py       # Main application file
README.md             # You're reading it!


# 📜 License
This project is released under the MIT License. Feel free to modify, distribute, or integrate Dive into your own projects.

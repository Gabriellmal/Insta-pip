⚡ Insta Pip

Insta Pip is a powerful, lightweight VS Code extension designed to make Python development faster and easier. With just one click, it scans your code for imports and automatically installs any missing libraries through your terminal.

🚀 Features

One-Click Install: Adds a lightning bolt icon ($(zap)) to your editor's top-right toolbar.

Smart Detection: Automatically identifies third-party libraries while ignoring standard Python built-ins like os and math.

Auto-Translation: Knows that import cv2 means you need to run pip install opencv-python.

Non-Intrusive: Only appears when you are working on Python files.

🛠️ How to Use

The Button: Look for the ⚡ icon in the top-right corner of your Python editor window. Click it to scan and install.

The Menu: Right-click anywhere in your code and select Insta Pip: Install Dependencies.

The Command Palette: Press Ctrl+Shift+P and type Insta Pip.

📦 Installation

Since this extension is in active development, you can install it using the .vsix file:

Download the insta-pip-0.0.2.vsix file from the Releases section.

Open VS Code.

Go to the Extensions view (Ctrl+Shift+X).

Click the "..." (Views and More Actions) menu in the top-right corner of the Extensions sidebar.

Select Install from VSIX... and choose the file you downloaded.

🤖 Supported Mappings

Insta Pip currently handles these tricky package names automatically:

cv2 → opencv-python

sklearn → scikit-learn

PIL → Pillow

bs4 → beautifulsoup4

📄 License

This project is open-source and available under the MIT License.

Created with ❤️ to help Python developers code faster.

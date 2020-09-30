This tool gives users the flexibility to require a screenshot and replica to the clipboard the text content of the screenshot. Works on Windows, macOS, and most Linux distros (some desktop environments may have issues with transparency).
How to Install :
Steps to Install :
1. Install Python 3 
2. Clone this repository, and cd into it 
3. (Optional) Create a virtual environment, as an example with python -m venv .venv 
4. Install the desired packages with pip install -r requirements.txt 
5. Install Google's Tesseract OCR Engine, and make sure that tesseract may be reached from the program line by adding the directory to your system  path.
On Windows, one can accomplish this by using an AutoHotkey script; textshot.ahk contains a sample AHK script which will be used.
Running textshot.py will open an overlay over the screen, where a rectangle may be drawn over the portion of the screen containing the text the user wishes to repeat

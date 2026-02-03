# ScreenOCR

ScreenOCR is a lightweight tool for capturing a portion of your screen and converting it into text on your clipboard. It automatically cleans up the text, and copies it raw if it detects lots of symbols (like math).

# Known Issues

Startup can feel a bit slow on some machines, especially the first time it runs.

Complex images or very small text may not be recognized perfectly.

OCR accuracy can vary depending on screen resolution and font style.

Selecting very tiny areas may result in no text being captured.

Currently only supports Windows (macOS/Linux not tested).

Some antivirus software may flag it as a false positive.

# Tools Used

Tesseract

PyInstaller

Python

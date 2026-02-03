# ScreenOCR

ScreenOCR is a lightweight Windows tool that lets you select a portion of your screen and instantly copy the detected text to your clipboard. It automatically cleans up OCR output, but switches to raw text when it detects heavy symbol usage such as math.

No internet, no accounts, no background services. It runs, it copies, it leaves.

# Download

The executable is about 1.3 GB because Tesseract is fully bundled to keep the app offline and plug-and-play.

Download via Google Drive:
https://drive.google.com/file/d/12fZ5wsnAfdoppdTYvBCjqweBasHR-SRV/view

Yes, it’s big. No, there’s no smaller magic version right now.

# Known Issues

Startup may feel slow on some machines, especially on first launch.

OCR accuracy depends heavily on font style, resolution, and contrast.

Very small selections may result in no detected text.

Complex layouts and images are not handled well.

Math and symbol-heavy content is copied raw and may still be inaccurate.

Windows only. Other platforms are untested.

Some antivirus software may flag the executable as a false positive due to bundling.

# Tools Used

Tesseract
PyInstaller
Python

# Having an Issue?

Open a GitHub issue, or reach out on Discord: @ygvq or @ulw0

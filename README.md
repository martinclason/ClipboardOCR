# ClipboardOCR

## Getting started
- Install homebrew www.brew.sh
- Install tesseract-lang by typing `brew install tesseract-lang` and hitting enter in a Terminal window.
- Then install pngpaste with `brew install pngpaste` in the same way as above.
- Clone this repository by opening a Terminal window and typing `git clone git@github.com:martinclason/ClipboardOCR.git` and hitting enter.
- Navigate into the downloaded repository by running `cd ClipboardOCR`.
- Run install script by typing `sudo bash install.sh` and also typing your password when prompted and hitting enter (this works even though no characters show when you type your password).
- You are now free to close this Terminal window.

## Using script
Copy the image you want to transform to text with the bulit in CMD-SHIFT-4 shortcut in MacOS that stores the resulting image in the clipboard.
Go to a terminal window and type `clipboard_ocr` and hit enter. The clipboard will now contain the text instead and this can be pasted like normal. If you want to do OCR on swedish text use the command `clipboard_ocr_sv` instead.



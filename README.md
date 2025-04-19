# Simple Image OCR

This is a simple Python project that demonstrates how to extract text from an image using Tesseract OCR and OpenCV.

## 📸 What it does

- Loads an image
- Converts it to grayscale
- Applies OCR using `pytesseract`
- Displays the image (for Google Colab)
- Saves the extracted text into a `.txt` file

## 🧰 Requirements

- Python
- OpenCV
- pytesseract
- Google Colab (optional, for running in the cloud)

## 📦 Installation

Install the required Python package:

```bash
pip install pytesseract opencv-python
```

Make sure Tesseract OCR is installed on your system. You can download it from:  
👉 https://github.com/tesseract-ocr/tesseract

If you're using Google Colab, `pytesseract` and `opencv-python` can be installed like this:

```python
!pip install pytesseract
```

## 📁 Output

The OCR result will be saved to:

```
hasil_ocr.txt
```

## 🧠 Notes

- `--psm 6` tells Tesseract to assume a single uniform block of text.
- This script is ideal for quick OCR testing in Jupyter Notebooks or Colab.

## 📄 License

MIT License. Feel free to use, modify, and share!

---

Happy OCR-ing! 🧐
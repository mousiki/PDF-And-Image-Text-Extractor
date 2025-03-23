Text Extraction from PDF and Image in Python


This project provides a solution to extract text from PDF documents and images using Python. It leverages popular libraries such as PyMuPDF (for PDFs) and Pytesseract (for optical character recognition, OCR, in images) to achieve this functionality. The goal is to enable text extraction from various sources, allowing you to automate document processing workflows.

Features
Extract Text from PDF: Using PyMuPDF (also known as Fitz), this tool extracts text from PDF files, including multi-page PDFs.

Extract Text from Images: Using Pytesseract (a Python wrapper for Tesseract OCR), this tool converts images into readable text, supporting various image formats (e.g., JPG, PNG, TIFF).

Supports Multi-page PDFs: If the PDF contains multiple pages, the text from all pages can be extracted seamlessly.

Image Preprocessing: Optional preprocessing for image files (like noise reduction, resizing) can be applied to improve OCR accuracy.

Installation
Prerequisites
Python 3.6+

Install the necessary libraries by running the following commands:

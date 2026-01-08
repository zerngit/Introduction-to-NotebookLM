# Introduction to NotebookLM - Slide Deck Editor

## Overview

This workshop demonstrates how to use Gemini's advanced coding capabilities to separate text from images in NotebookLM-generated PDFs and create editable PowerPoint presentations.

## Method

This method leverages Gemini's AI to perform OCR (Optical Character Recognition), image inpainting, and content merging to transform static PDF slides into editable PowerPoint files.

## Steps

### 1. Get the Code
Retrieve the HTML script provided in the workshop resources (or from the reference video description).

### 2. Open Gemini Canvas
Navigate to the Gemini advanced interface.

### 3. Paste & Upload
- Paste the Python code into the Gemini chat
- Prompt Gemini : "Run the program, dont change anything"
- Upload your NotebookLM PDF file

### 4. Execute
Ask Gemini to run the code. The script performs three key actions:

- **OCR**: Extracts text from the slides
- **Inpainting**: Removes the text from the background image (creating a clean "blank" slide)
- **Merge**: Re-combines the clean background and the extracted text into a new `.pptx` file

### 5. Download
Download the resulting PowerPoint file, which now has editable text boxes over the original background.

## Result

You'll have a fully editable PowerPoint presentation with:
- Clean background images
- Editable text boxes
- Original slide structure preserved

## Acknowledgments

This project was built following a tutorial by :

*   **Video Title:** [Link to the specific video](https://www.youtube.com/watch?v=pDGHg5jHLM8)
*   **Author:** [观点lab](https://www.youtube.com/@%E8%A7%80%E9%BB%9ELAB)

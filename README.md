# Optical Character Recognition with Plagiarism Checker

- This project is an implementation of Optical Character Recognition (OCR) with a built-in plagiarism checker. It was developed collaboratively by me and my project mates.

## Plagiarism Checker

- To begin with, we created a plagiarism checker using the Python programming language. We utilized the scikit-learn library, which provides powerful tools for text analysis and comparison. The plagiarism checker compares each pair of text files within a specified folder and generates a percentage indicating the similarity between them.

## Optical Character Recognition (OCR)

- As an additional feature, we incorporated an open-source OCR engine called Tesseract into our project. This enables us to convert text from image files into text files with the .txt extension. By leveraging the OCR functionality, we can now apply the plagiarism checker code to determine the similarity percentage between text extracted from images.

- To integrate the OCR capabilities into our project, we utilized the pytesseract module in Python. This module allows seamless integration with Tesseract, making it easier for us to extract text from images and include them in our plagiarism analysis.

- Overall, this project combines OCR and a plagiarism checker, offering a comprehensive solution for detecting similarities in both text and image files.
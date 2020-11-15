# Project-NID


## Folder Description
- Documentation: File contains Documentation of all methods and difficulties
+ EAST - DL ==> Deep Learning Based Notebook 
- Easy - OCR ==>  Easy_OCR based text extraction Notebook
- NID- Object Detection ==> NID card Detection based Notebook
+ PYTESSER-OCR ==> Heuristic Algorithm with Tesseract based text extraction Notebook
- Three in One ==> All three method(DL, Easy OCR, Heuristic) are implemented in this Notebook


## To extract NID information from an image we haved used four methods
+ Easy-OCR
- Tesseract-OCR
+ EAST - Deep Learning based method
- Heuristic Algorithm


## Tesseract-OCR: 
Tesseract — is an optical character recognition engine with open-source code, this is the most popular and qualitative OCR-library.
OCR uses artificial intelligence for text search and its recognition on images.
Tesseract is finding templates in pixels, letters, words and sentences. It uses two-step approach that calls adaptive recognition. It requires one data stage for character recognition, then the second stage to fulfil any letters, it wasn’t insured in, by letters that can match the word or sentence context.


## Easy-OCR
The EasyOCR package is created and maintained by Jaided AI, a company that specializes in Optical Character Recognition services.

EasyOCR is implemented using Python and the PyTorch library. If you have a CUDA-capable GPU, the underlying PyTorch deep learning library can speed up your text detection and OCR speed tremendously.

As of this writing, EasyOCR can OCR text in 58 languages, including English, German, Hindi, Russian, and more! The EasyOCR maintainers plan to add additional languages in the future. 

## EAST - Deep Learning based method
OpenCV’s EAST text detector is a deep learning model, based on a novel architecture and training pattern. It is capable of (1) running at near real-time at 13 FPS on 720p images and (2) obtains state-of-the-art text detection accuracy.


## Heuristic Algorithm
Uasing sliding window algorithm object detection and text identification
# OPTICAL-CHARACTER-RECOGNITION

OCR = Optical Character Recognition.
<br>OCR systems transform a two-dimensional image of text, that could contain machine printed or handwritten text from its image representation into machine-readable text. OCR as a process generally consists of several sub-processes to perform as accurately as possible
 In other words, OCR systems transform a two-dimensional image of text, that could contain machine printed or handwritten text from its image representation into machine-readable text. OCR as a process generally consists of several sub-processes to perform as accurately as possible. The subprocesses are:

    * Preprocessing of the Image
    * Text Localization
    * Character Segmentation
    * Character Recognition
    * Post Processing <br>
    
The sub-processes in the list above of course can differ, but these are roughly steps needed to approach automatic character recognition. In OCR software, it’s main aim to identify and capture all the unique words using different languages from written text characters.


## OCR with Pytesseract and OpenCV<br>
**Pytesseract** : Pytesseract is a wrapper for Tesseract-OCR Engine. It is also useful as a stand-alone invocation script to tesseract, as it can read all image types supported by the Pillow and Leptonica imaging libraries, including jpeg, png, gif, bmp, tiff, and others.
<br>**OpenCV** : OpenCV (Open Source Computer Vision Library) is a library of programming functions mainly aimed at real-time computer vision. This is an open source library that includes several hundreds of computer vision algorithms.

## Shortcomings of this project
* *The test in the image should be preferabbly in one column format.*
* *After edge detection using canny edge detector, the OCR often confuses betewwn different characters and special characters like C and ( etc.*

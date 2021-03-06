LicensePlateRecognition
=======================
### Summary
An automated system for car license plate detection and recognition

Thanks to [eevee](https://github.com/eevee/pyhq2x) for the hq2x python module

#### Setup instructions: ####
1. Install Python v2.7.* 32-bit
2. Install OpenCV 2.x (OS X guide [here](https://jjyap.wordpress.com/2014/05/24/installing-opencv-2-4-9-on-mac-osx-with-python-support/))
3. Install [Tesseract 3.02](https://github.com/tesseract-ocr/tesseract/releases/tag/3.02.02) (higher versions don't work with python-tesseract yet)
4. Install the following Python packages:
  * numpy
  * Pillow (fork of PIL)
  * [python-tesseract](https://bitbucket.org/3togo/python-tesseract/downloads)
5. Extract [tessdata](https://drive.google.com/file/d/0B61RgxZKvD2JT011cWluN3JMMUk/view?usp=sharing) in the main folder
6. Place pictures on which to perform detection in the main/images folder, or you can download [my test pictures](https://drive.google.com/file/d/0B61RgxZKvD2JOVZTZjY1OHVMTmc/view?usp=sharing)
7. OPTIONAL, to use the GUI:
  * Install (or build from source) [sip](https://www.riverbankcomputing.com/software/sip/download)
  * Install (or build from source) [PyQt5](https://www.riverbankcomputing.com/software/pyqt/download5)
8. Enter the project directory and run the following commands:
  * export PYTHONPATH=$PYTHONPATH:.
  * python main/main.py

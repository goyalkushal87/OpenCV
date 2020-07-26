#Install  OpenCV
(base) C:\Users\saket>pip install opencv-python==3.4.2.17
Collecting opencv-python==3.4.2.17
  Downloading opencv_python-3.4.2.17-cp37-cp37m-win_amd64.whl (33.8 MB)
     |████████████████████████████████| 33.8 MB 24 kB/s
Requirement already satisfied: numpy>=1.14.5 in c:\anaconda\lib\site-packages (f
rom opencv-python==3.4.2.17) (1.18.1)
Installing collected packages: opencv-python
Successfully installed opencv-python-3.4.2.17

(base) C:\Users\saket>pip install opencv-contrib-python==3.4.2.17
Collecting opencv-contrib-python==3.4.2.17
  Downloading opencv_contrib_python-3.4.2.17-cp37-cp37m-win_amd64.whl (39.6 MB)
     |████████████████████████████████| 39.6 MB 35 kB/s
Requirement already satisfied: numpy>=1.14.5 in c:\anaconda\lib\site-packages (f
rom opencv-contrib-python==3.4.2.17) (1.18.1)
Installing collected packages: opencv-contrib-python
Successfully installed opencv-contrib-python-3.4.2.17




Installation instruction for Windows (source: https://stackoverflow.com/questions/42831662/python-install-tesseract-for-windows-7): 


Step [1] To install tesseract kindly visit
https://github.com/UB-Mannheim/tesseract/wiki
The latest installers can be downloaded from here: e.g., tesseract-ocr-setup-3.05.02-20180621.exe, tesseract-ocr-w32-setup-v4.0.0-beta.1.20180608.exe, tesseract-ocr-w64-setup-v4.0.0-beta.1.20180608.exe (64 bit)

# Step 2 not needed as most probably, you would have compiler
Step [2] Download Microsoft Visual C++ Compiler for Python 2.7 from the link given belowhttps://download.microsoft.com/download/7/9/6/796EF2E4-801B-4FC4-AB28-B59FBF6D907B/VCForPython27.msi
Step [3] Install pytesseract for binding for tesseract using pip
pip install pytesseract
Step [4] Furthermore you can install an image processing library in python, e.g., pillow:
pip install pillow
greetings!! you are done!! :)

While running OCR, give the path of the directory where OCR is present, as stated in the notebook.

Refer: https://github.com/tesseract-ocr/tesseract/wiki
For Installation in MAC:
brew install tesseract

For Ubuntu:
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev



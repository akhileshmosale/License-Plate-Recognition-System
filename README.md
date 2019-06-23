# License-Plate-Recognition-System

The license plate recognition system takes the image as the input. After initial preproccessing Open-CV libraries are used to isolate the license plate. The isolated image is then passed to KNN,OCR,CRNN recognition techniques.The output of the number plate is displayed on the terminal.To run the CRNN users need to install CUDA.

Extract OpenCV_3_License_Plate_Recognition_Python.zip
Run: python3 Main.py The KNN technique is used to detect the plate characters.

Install tesseract-OCR using pip Run: tesseract imgCrop.png/jpg/jpeg stdout The Tesseract OCR displays the output on the terminal.

Create a file called "data" (create another file called models inside the data file) and Download ctpn_vgg16.pb and crnn_raw.pb from https://github.com/Sanster/models , save to data/models.
Rename ctpn_vgg16.pb as ctpn.pb, rename crnn_raw.pb as crnn.pb.
Run: make -C tf_ctpn/lib

After you run python3 Main.py in Opencv the imgCrop.png file is sent to the data1 file (change the destination as per your requirements).





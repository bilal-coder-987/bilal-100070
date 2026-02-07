# 📦 Barcode Detection and Decoding

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv)
![License](https://img.shields.io/badge/License-MIT-orange)

---

## 🧑‍🎓 Student Information
- **Names:** Muhammad Arslan, Muhammad Bilal, Bhezad Farid Khan  
- **Roll Numbers:** 100055, 100070, 100079  
- **Course Name:** Digital Image Processing  

---

## 📖 Table of Contents
1. [Project Description](#project-description)  
2. [Objectives](#objectives)  
3. [Tools & Technologies](#tools--technologies)  
4. [Steps to Run the Code](#steps-to-run-the-code)  
5. [Sample Input and Output](#sample-input-and-output)  
6. [Conclusion](#conclusion)  

---

## 📝 Project Description
This project implements **barcode detection and decoding** using computer vision techniques.  

- Utilizes **OpenCV** for image processing.  
- Uses **Zbar** for barcode recognition.  
- Detects various types of barcodes in images and decodes them to extract encoded information.  
- Provides an efficient solution for **automated barcode reading applications**.  

---

## 🎯 Objectives
- Detect barcodes in images using **image processing techniques**.  
- Decode the detected barcodes to retrieve the **encoded data**.  
- Implement the solution using **Python** and relevant libraries.  
- Evaluate performance on **sample images**.  

---

## 🛠️ Tools & Technologies
- **Python**  
- **OpenCV**  
- **Zbar**  
- **NumPy**  
- **Matplotlib** (optional, if used)  

---

## 🚀 Steps to Run the Code
1. Open your GitHub repository.  
2. Click on **README.md** file (or create new: **Add file → Create new file → Name: README.md**).  
3. Copy **all the content** from this README and **paste** it into the editor.  
4. Scroll down → In **Commit changes** section:  
   - Write commit message: `Updated README with GitHub style`  
   - Click **Commit changes**.  
5. Refresh repository → Your README will now appear **professional and stylish**.  

6. To run the code locally:  
   - Ensure **Python** is installed.  
   - Install required libraries:  
     ```bash
     pip install opencv-python pyzbar numpy matplotlib
     ```  
   - Navigate to `Code/` directory.  
   - Run the script:  
     ```bash
     python barcode_detect_and_decode.py
     ```  
     or  
     ```bash
     python detect_barcode_opencv.py
     ```  
   - Provide input images from `Dataset/`.  
   - View output in `Results/output_images/`.  

---

## 📷 Sample Input and Output
- **Input Image:** Product label with barcode (QR code or linear).  
- **Output Image:** Barcode highlighted with rectangle + decoded text displayed.  
*(Refer to `Results/output_images/` for actual samples.)*  

---

## ✅ Conclusion
- Demonstrates **computer vision for barcode detection and decoding**.  
- Using **OpenCV and Zbar**, accurate detection and decoding achieved.  
- Can be extended to **real-time applications** like inventory management or retail scanning.  
- Future improvements: handle more barcode types and **optimize performance**.  

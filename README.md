# 🚗 Noise Reduction for Car Number Plate using Python

This project demonstrates how to reduce noise from images of car number plates using **OpenCV** in Python, making them clearer for **OCR (Optical Character Recognition)**.
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📌 Features
- Convert image to grayscale for easy processing
- Apply **Bilateral Filtering** to remove noise while preserving edges
- Use **Adaptive Thresholding** to make plate text stand out
- Ready for integration with OCR tools like **Tesseract**
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📂 Project Structure

📁 noise_reduction_number_plate
 ├── car_number_plate.jpg   # Sample input image
 ├── noise_reduction.py     # Main Python script
 └── terescat ocr.txt           # Project documentation
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🖼️ Example Output
> Original Image → Denoised Image → Thresholded Image
> Original	Denoised	Thresholded

<img width="1146" height="657" alt="Screenshot 2025-08-09 143931" src="https://github.com/user-attachments/assets/af6ea07f-705b-4a7f-9c30-5f7e8d8e45da" />   
<img width="1146" height="660" alt="Screenshot 2025-08-09 144013" src="https://github.com/user-attachments/assets/f2d227d8-065b-415f-a05d-e190552803aa" />
<img width="1144" height="650" alt="Screenshot 2025-08-09 144031" src="https://github.com/user-attachments/assets/80a8c35a-ccb5-4e1a-a9e5-bf70516f9c85" />
<img width="282" height="103" alt="Screenshot 2025-08-09 144059" src="https://github.com/user-attachments/assets/fc5db2ab-c0de-43c8-97d4-5a629ff01be4" />
<img width="1136" height="659" alt="Screenshot 2025-08-09 144125" src="https://github.com/user-attachments/assets/1a86e427-9678-43a3-a05e-00671bcdcc42" />



____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📚 How It Works
> Grayscale Conversion – Converts the image into grayscale for easier processing.
> Bilateral Filter – Removes noise but keeps important edges intact.
> Adaptive Thresholding – Enhances the visibility of characters for OCR.
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📌 Future Improvements
> Automatic number plate detection using Haar Cascades or YOLO
> Direct OCR extraction using Tesseract
> Batch processing for multiple images
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📜 License
This project is open-source and available under the MIT License.

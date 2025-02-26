## SECURE DATA HIDING  IN IMAGE USING STEGANOGRAPHY

## 📌 Project Overview

This project implements an encryption and decryption technique using OpenCV to hide textual data within an image. The text is securely embedded into the pixel values using XOR-based encryption and can only be retrieved using the correct decryption key.

## 🚀 Features

- Secure text encryption using image pixel values.
- XOR-based encryption technique.
- Key-based decryption for secure retrieval.
- Works with RGB image planes.
- Lightweight and efficient.

## 🛠 Technologies Used

- *Programming Language*: Python
- *Libraries*: OpenCV, NumPy, OS

---

## 📖 How to Use

### 🔹 Prerequisites

Ensure you have the following installed on your system:

- Python (>=3.6)
- OpenCV (pip install opencv-python)
- NumPy (pip install numpy)

### 🔹 Steps to Run the Project

#### 1️⃣ Clone the Repository

bash
git clone https://github.com/rahul82667/-Steganography
cd -Steganography


#### 2️⃣ Run the Encryption Script

bash
python encrypt.py


- Enter the security key.
- Input the text you want to hide.
- The encrypted image (encrypted_img.jpg) will be saved in the same directory.

#### 3️⃣ Run the Decryption Script

bash
python decrypt.py


- Enter the same security key used for encryption.
- The hidden text will be extracted and displayed.

---

## 📷 Example

### *Encryption Process:*

1. Load an image (1.jpg).
2. Enter a secret key.
3. Embed text into pixel values using XOR operation.
4. Save the encrypted image.

### *Decryption Process:*

1. Load the encrypted image.
2. Input the correct decryption key.
3. Extract and reveal the hidden text.

---

## 🔗 GitHub Repository

[https://github.com/rahul82667/-Steganography](https://github.com/rahul82667/-Steganography)

## 📌 Future Enhancements

- Implement multi-layer encryption for enhanced security.
- Create a GUI for easier usability.
- Explore deep learning-based steganography methods.

*🔐 Secure Your Messages with Image Encryption! 🚀*

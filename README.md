# 🖼️ Image Encryption & Decryption (Pixel Manipulation)

A simple Python project that demonstrates **image encryption and decryption** by directly manipulating pixel values.  
This is a great way to understand how data can be transformed at the pixel level to secure images.

---

## 📖 About  
This program works by modifying the pixel values of an image using a user-defined key.  
The same key must be used to decrypt the image back to its original form.  

---

## 🚀 Features  
- Encrypts an image by shifting pixel values  
- Decrypts the encrypted image back to its original state  
- Works on standard image formats (PNG, JPG, etc.)  
- Easy to use — just provide an input image and key  

---

## ⚙️ How to Run  

1. **Clone this repository**  
```bash
git clone https://github.com/your-username/PRODIGY_CS_O1.git
cd PRODIGY_CS_O1
```

2. **Install dependencies**  
This project uses Pillow for image processing:  
```bash
pip install pillow
```

3. **Run the program**  
```bash
python image_encryption.py
```

4. **Example Output**  
```
Enter image path: input.png
Enter key: 50
Image encrypted successfully → saved as encrypted.png
Decrypting with same key...
Image decrypted successfully → saved as decrypted.png
```

---

## 🛠️ Future Ideas  
- Add a GUI for selecting images and entering key  
- Support batch encryption for multiple images  
- Use more advanced encryption methods (AES + pixel manipulation)  

---

## 📄 License  
MIT License – free to use and modify.

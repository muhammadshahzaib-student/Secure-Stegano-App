✨ Features
🔐 Steganography: 
Hide Text: Embed secret text data inside images.
Hide Files: Compress and hide multiple files within an image.
Hide Videos: Conceal video files (e.g., MP4, AVI, MOV) in images.
Extract Hidden Content: Seamlessly retrieve hidden text, files, folders, or videos using a password.

🔏 Encryption Tools: 
AES-256 GCM Encryption: Secure password-based encryption.
File Encryption: Encrypt files while preserving the original filename.
Text Encryption: Convert plaintext into AES-encrypted Base64 strings.

🖼️ Image Handling: 
Load, preview, and update images.
Create new blank images as data carriers.
Revert images to original state and clear hidden data.

📋 Clipboard Support: 
Copy/paste text and images between the app and system clipboard.

📁 File Management: 
Built-in file explorer panel.
Drag-and-drop friendly text editor.
Automatic temporary file handling and cleanup.

🧪 Background Workers: 
Encoding/decoding processes run in background threads for a smooth experience.
Real-time progress updates.

🔧 Technologies Used: 
Python 3.10
PyQt5 – GUI framework
Pillow (PIL) – Image processing
PyCryptodome – AES-GCM encryption
Zipfile – File compression for hiding

📦 Output: 
The output is a .png image file containing encrypted hidden content.
It remains a valid image while secretly storing data retrievable only with a password.

🔒 Security Design: 
Uses PBKDF2 for key derivation and AES-256-GCM for encryption and authentication.
Data is appended in the image using LSB steganography.
Special binary marker (1111111111111110) signifies the end of hidden data.

Install Dependencies:
pip install pyqt5 pillow pycryptodome

## 🧑‍💻 Author: 
Muhammad Shahzaib (https://github.com/muhammadshahzaib-student)

📸 Screenshot: 
![image](https://github.com/user-attachments/assets/152a07a6-5a04-4bc3-a128-5b206b5687e3)

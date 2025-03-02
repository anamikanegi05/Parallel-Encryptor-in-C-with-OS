🔐 File Encryption & Decryption System
📌 Overview
This project is a File Encryption & Decryption System built using C++. It allows users to securely encrypt and decrypt files using a user-defined key stored in an .env file. The system processes files efficiently, making it useful for securing sensitive documents like PDFs, text files, and more.

🚀 Features
✅ Encrypt & Decrypt files with a secret key 🔑
✅ Uses Caesar Cipher Algorithm for encryption 🔄
✅ Supports batch processing of multiple files 📂
✅ Utilizes file handling & process management for efficiency ⚡
✅ Written in C++ with OS-level process execution 🖥️

📂 Project Structure
scss
Copy
Edit
📦 File-Encryption-Decryption  
│-- 📂 src  
│   ├── 📂 app  
│   │   ├── 📂 fileHandling  (Handles file I/O operations)  
│   │   ├── 📂 encryptDecrypt (Encryption & decryption logic)  
│   │   ├── 📂 processes (Task & process management)  
│   ├── main.cpp (Entry point)  
│-- .env (Stores encryption key)  
│-- Makefile (Compilation instructions)  
│-- README.md (This file)  
🛠️ Installation & Usage
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/File-Encryption-Decryption.git
cd File-Encryption-Decryption
2️⃣ Set Up the Environment
Create a .env file and add your encryption key:

yaml
Copy
Edit
8717  # Example encryption key (change it!)
3️⃣ Compile the Code
sh
Copy
Edit
make
4️⃣ Run the Program
To encrypt/decrypt files inside a folder:

sh
Copy
Edit
./encrypt_decrypt
Enter the directory path and action (encrypt/decrypt) when prompted.

📝 How It Works
1️⃣ Reads the encryption key from .env 📄
2️⃣ Encrypts/Decrypts files byte by byte 🔢
3️⃣ Uses process management to handle multiple tasks efficiently 🚀
4️⃣ Stores modified content back into the file 📂

🎯 Future Enhancements
🔐 Implement stronger encryption algorithms (AES, RSA)
🌍 Create a GUI/Web interface for easy usage
📡 Add remote encryption support
🤝 Contributing
Pull requests are welcome! Feel free to fork this repository and contribute improvements.

📜 License
This project is open-source under the MIT License.

This README provides a clear introduction, setup instructio

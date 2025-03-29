## 📌 Overview



This **File Sorter** is a Python script that automatically organizes files in a specified directory based on their file extensions. It creates folders for different file types and moves the corresponding files into these folders.



## 🚀 Features



- Automatically scans the directory for files.

- Creates folders if they don't exist.

- Moves files into categorized folders based on their extensions (.csv, .png, .docx).

- Prevents moving directories by mistake.

- Prints a list of files that were not moved.



## 📂 Folder Structure (Before & After)



### **Before Running the Script:**



```

file_sorter/

│── data.csv

│── image1.png

│── document.docx

│── notes.txt

│── random_file.exe

```



### **After Running the Script:**



```

file_sorter/

│── csv files/

│   └── data.csv

│── image files/

│   └── image1.png

│── doc files/

│   └── document.docx

│── notes.txt  (Not moved)

│── random_file.exe  (Not moved)

```



## 🛠️ Installation & Usage



### **1. Clone the Repository**



```bash

git clone https://github.com/your-username/file-sorter.git

cd file-sorter

```



### **2. Install Python (If not installed)**



Ensure you have Python installed (version 3.x recommended). You can download it from [python.org](https://www.python.org/downloads/).



### **3. Run the Script**



```bash

python sorter.py

```



## 📜 Code Explanation



The script follows these steps:



1. Defines the target directory (`file_sorter/`).

2. Lists all files in the directory.

3. Creates folders for `.csv`, `.png`, and `.docx` files if they don’t exist.

4. Moves the respective files into their categorized folders.

5. Prints a list of files that were **not** moved.



## 🤝 Contributing



Feel free to fork this repo, create a new branch, and submit a pull request with improvements!



## 📄 License



This project is open-source and available under the **MIT License**.



---



💡 **Developed by Sahil Sanwal**



folders for different file types and moves the corresponding files into these folders.

🚀 Features

Automatically scans the directory for files.

Creates folders if they don't exist.

Moves files into categorized folders based on their extensions (.csv, .png, .docx).

Prevents moving directories by mistake.

Prints a list of files that were not moved.

📂 Folder Structure (Before & After)

Before Running the Script:

file_sorter/
│── data.csv
│── image1.png
│── document.docx
│── notes.txt
│── random_file.exe

After Running the Script:

file_sorter/
│── csv files/
│   └── data.csv
│── image files/
│   └── image1.png
│── doc files/
│   └── document.docx
│── notes.txt  (Not moved)
│── random_file.exe  (Not moved)

🛠️ Installation & Usage

1. Clone the Repository

git clone https://github.com/your-username/file-sorter.git
cd file-sorter

2. Install Python (If not installed)

Ensure you have Python installed (version 3.x recommended). You can download it from python.org.

3. Run the Script

python sorter.py

📜 Code Explanation

The script follows these steps:

Defines the target directory (file_sorter/).

Lists all files in the directory.

Creates folders for .csv, .png, and .docx files if they don’t exist.

Moves the respective files into their categorized folders.

Prints a list of files that were not moved.

🤝 Contributing

Feel free to fork this repo, create a new branch, and submit a pull request with improvements!

📄 License

This project is open-source and available under the MIT License.

💡 Developed by Sahil Sanwal

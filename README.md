# 📖 Phonebook Management System

A robust and user-friendly Phonebook Management System with a sleek UI, seamless navigation, and efficient data handling. Effortlessly add, search, modify, and delete contacts with real-time updates. 📇✨

## 🚀 Features
- 🔒 **Secure Login** – Password-protected access for authorized users.
- 📌 **Effortless Contact Management** – Add, search, modify, and delete contacts with ease.
- 📂 **Persistent Storage** – Stores data in `ebraj.txt` for future retrieval.
- 🎨 **Intuitive Interface** – Smooth navigation with a clean UI.

## 🛠️ Installation
### 📌 Prerequisites
- 🖥️ Windows OS (Utilizes `conio.h` and `windows.h`)
- 🏗️ C++ Compiler (MinGW recommended for Windows)

### 🔧 Compilation & Execution
Use the following commands in Bash (for Windows with MinGW installed):

```bash
# 🏗️ Compile the program
g++ phonebook.cpp -o phonebook.exe -static -mwindows

# ▶️ Run the program
./phonebook.exe
```

## 🎯 Usage
1. 🔑 **Run the program** and enter the password (**default:** `00000000`).
2. 📜 **Select an option from the menu:**
   - `1️⃣` - Add a new contact ➕
   - `2️⃣` - Search for a contact 🔍
   - `3️⃣` - List all contacts 📜
   - `4️⃣` - Modify a contact 📝
   - `5️⃣` - Delete a contact ❌
   - `6️⃣` - Exit the program 🚪

## 🖥️ Automate Execution with a Bash Script
For a streamlined experience, create a `run.sh` script with the following:

```bash
#!/bin/bash
g++ phonebook.cpp -o phonebook.exe -static -mwindows
if [ $? -eq 0 ]; then
    echo "✅ Compilation successful. Running the program..."
    ./phonebook.exe
else
    echo "❌ Compilation failed. Please check for errors."
fi
```

Run it using:
```bash
bash run.sh
```

## 📝 Notes
- 📂 The program stores contact details in `phonebook.txt`.
- 🔄 Modifications and deletions automatically update the data.
- 🔑 **Password-protected** access ensures data security.

📬 Contact

📧 Email: lokeshagarwal2304@gmail.com

🐦 Twitter: Lokeshagarwal2304(https://twitter.com/lokeshagarwal2304)

💼 LinkedIn: lokeshagarwal2304(https://linkedin.com/in/lokeshagarwal2304)

See you Soon :)

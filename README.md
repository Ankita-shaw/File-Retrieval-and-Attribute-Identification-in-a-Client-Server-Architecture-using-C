# File-Retrieval-and-Attribute-Identification-in-a-Client-Server-Architecture-using-C

File Retrieval & Analysis in a Client-Server Model By Ankita Shaw

Overview :This project implements a simple yet efficient client-server model in C, enabling remote file retrieval and attribute identification.

The client sends a filename to the server, which checks for its existence and responds accordingly. 
If the file is found, the server transmits its contents to the client and determines its properties:  ✔️ Executable File 🏃‍♂️ ✔️ Directory 📁 ✔️ Read-Only File 🔒 ✔️ Non-Existent File ❌ (Server notifies the client.) 

Key Features 🔹 File Existence Check: Ensures the requested file is available on the server. 🔹 Remote File Transfer: Sends the file’s contents from server to client. 🔹 File Type Identification: Detects if the file is an executable, directory, or read-only. 🔹 Networking with Sockets: Uses socket programming in C for communication. 🔹 System Calls & File Handling: Utilizes functions like  fclose and fopen for efficient processing.  How It Works 1️⃣ The client sends a filename request. 2️⃣ The server receives the filename and checks its existence. 3️⃣ If the file does not exist, the server notifies the client. 4️⃣ If the file exists, the server:  Reads & transfers its contents to the client. Determines its type (executable, directory, or read-only). Sends file details along with the data.

Technologies Used 🖥️ Language: C 🔗 Networking: Socket Programming

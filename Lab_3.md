Writing an Assembly program named hello.asm using Mousepad and saving it to the Downloads folder in Kali Linux. The program prints “Hello, World!” and then exits.

<img width="857" height="645" alt="Screenshot 2025-11-04 010701" src="https://github.com/user-attachments/assets/35f52109-2efe-4cdc-8434-45baa5176501" />



Assembling hello.asm using NASM to generate hello.o, then linking it using ld to create an executable named hello. Running the executable successfully displays “Hello, World!” in the terminal.

<img width="859" height="650" alt="Screenshot 2025-11-04 005418" src="https://github.com/user-attachments/assets/cf136f17-2531-4f80-941b-a8dfa17c43f6" />



Creating an ASM folder and attempting to assemble HelloWorld.asm using ml and NASM. Neither command was recognized in the terminal. A separate batch file named test.bat was then run successfully, displaying “Hello World from Windows!”

<img width="677" height="637" alt="Screenshot 2026-10-16 043803" src="https://github.com/user-attachments/assets/8f412469-dee2-4c2c-9686-7147c44ac121" />



Attempting to inspect the headers of test.bat using dumpbin /headers. The tool returned an “Invalid format” warning because a batch script is not a supported compiled binary, such as an .exe or .obj file.

<img width="690" height="495" alt="Screenshot 2026-10-16 043830" src="https://github.com/user-attachments/assets/6282d035-41f2-4a9f-bd29-8daf561a7a5b" />



The goal of this lab is to learn basic Assembly instructions and understand how Assembly code is assembled, linked, and executed, providing a foundation for reverse engineering.

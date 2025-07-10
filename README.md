# MEMORY-DUMP-USING-FTK-IMAGER-AND-PHOTOREC
This repository documents a forensic exercise involving memory acquisition from a Windows system using FTK Imager, and subsequent data recovery (carving) using PhotoRec in a Kali Linux environment.


Project Overview

Title: Memory Dump Acquisition and Carving  

Author: Adenike Oluwabusola Oni  

Tools Used: FTK Imager, PhotoRec, Kali Linux  

This project demonstrates:

- Capturing a live memory dump from a Windows system

- Sharing and accessing the dump from Kali Linux

- Carving memory for recoverable artifacts using PhotoRec


Step-by-Step Procedure
1. Capture Memory with FTK Imager

- Launch FTK Imager

- Navigate: `File` → `Capture Memory`

- Set destination path and filename

- Include page file

- Click **Capture Memory**

- Wait for acquisition to complete


2. Transfer Dump File to Kali Linux

- Share the memory dump folder with Kali Linux

- Access and copy the dump to the **Kali Desktop**

- Use terminal to verify successful copy


3. Carve Memory with PhotoRec

- Open PhotoRec

- Select the memory dump file as source

- Choose destination folder for recovered data

- Begin recovery process

- Review the extracted files


Output
- Memory Dump File: Raw memory data from Windows

- Recovered Files: Carved files including fragments of documents, images, and system artifacts from volatile memory


Skills & Tools Demonstrated
- Memory forensics

- Live RAM acquisition using FTK Imager

- File carving and recovery using PhotoRec

- Kali Linux terminal operations

- Basic digital evidence handling


Disclaimer: 
No actual confidential data is included. This was conducted as an academic or learning-based forensic simulation. All operations were simulated on controlled systems with no involvement of real criminal investigations.


For questions, suggestions, or collaborations:  
📧 [adenikeoluwabusolaoni@gmail.com]

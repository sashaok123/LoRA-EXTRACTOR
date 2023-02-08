# LoRA-EXTRACTOR
A small script to facilitate the extraction of LoRA models from custom checkpoints.

**THIS SCRIPT IS BASED ON LIBRARIES: https://github.com/kohya-ss/sd-scripts**


The extractor consists of 3 small scripts and libraries. 

List of scripts:
1) !Updating and extracting LoRA - to check, update or install the required libraries and extract the LoRA model (data) from the checkpoint.
2) LoRA extraction only - only for extracting the LoRA model (data) from the checkpoint.
3) Only updating libraries - only for updating or installing the required libraries.

According to tests, the GPU is practically not involved. For the most part, the entire load is on RAM and CPU.

**FileToOpen** and **FileToSave** are included in the **[Wfile 1.5](https://www.horstmuc.de/w32dial.htm#wfile/)** package. Was used to open a window, select a file and save LoRA model.
Links to check files on virustotal: **[FileToOpen.exe](https://www.virustotal.com/gui/file/18e68248f98aba1c5d755c95152453458600daaa03046015da5c592edb642a44)** and **[FileToSave.exe](https://www.virustotal.com/gui/file/bb8ce8ddb36c580a7bb153a4883f6d6e8cc3a11b2cded9f4891d228711e0db91)**

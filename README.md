# A Novel Hierarchical Embedded System for Detection and Diagnosis of COPD and Other Respiratory Disorders

This repo is the PyTorch code of our paper: [links]

**Ultra96v2 Board**
1. Connect the 12V power supply.
2. Connect to the AES-ACC-USB-JTAG board.
3. Connect the Camera daughter card to the Ultra96 v2 (optional)
4. Connect the microUSB cable to the AES-ACC-USB-JTAG and the PC.
5. Connect the second microUSB cable from the Ultra96 v2 USB3.0 connector to the PC for network connection
6. Use the miniDiSplay cable to connect the Ultra96 v2 and the DisplayPort Monitor (optional)
7. Connect the USB webcam to one of the host's USB ports (optional)
8. Prepare the MicroSD card and partition it to FAT32

   ![u96v2_settings](https://github.com/user-attachments/assets/46c3a41a-7929-442f-9ab6-89f303a9d4a4)

**Highlight**
   1. A proposed hierarchical embedded system using Random Forest and Lightweight CNN models with four resilient layers that achieve 98,81\% accuracy reach state-of-the-art results compared to other basic Machine Learning methods. Moreover, unlike previous methods that used static models, fixed parameters, and set-up conditions, this dynamic embedded system with high flexibility could complete the classification without completing four stages. It could be modified to adapt to various conditions of the dataset.
![image](https://github.com/user-attachments/assets/42bd333c-2045-4e26-aa75-68ed1b1806ae)

   2. Implement the proposed model on soft-hard system FPGA Ultra96V2 using PYNQ and Vitis-AI framework that works in real-time conditions and achieves impressive 52.5\% power saving and outperformance with excellent GOPs compared to traditional CPU-GPU methods.

![image](https://github.com/user-attachments/assets/f878df14-d830-461c-8b2b-dc74825cfdba)

   4. We propose a novel Domain-Specific Quantization Strategy (DSQS) tailored specifically for respiratory sound analysis on FPGA platforms.

**Overall model architecture**

![image](https://github.com/user-attachments/assets/4b1c30da-8533-40db-953d-ead10facfe67)


**Requirements**


**Usage - To run the code**

**Citation**

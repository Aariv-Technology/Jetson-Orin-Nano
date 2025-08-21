# Jetson Orin Nano CSI Camera Testing

This guide explains how to test CSI cameras (IMX219, IMX477, etc.) on the **NVIDIA Jetson Orin Nano** after completing the initial camera configuration. Refere Setup_README.md for CSI-Camera Initial configs setup.

---

## 📌 Prerequisites
- Camera configured using **jetson-io** tool (see setup instructions)  
- Python 3 installed  
---

## 📥 Clone the Repository
After setting up the initial camera configuration, clone this repository:

```bash
git clone https://github.com/Aariv-Technology/Jetson-Orin-Nano.git
cd Jetson-Orin-Nano/CSI-Camera-configs
```
## 📂 Directory Structure
Once inside the CSI-Camera-configs folder, you should see the following files:
```
ls -l
Example output:
drwxrwxr-x 3 aariv aariv 4096 Aug 21 11:15 ./
drwxrwxr-x 4 aariv aariv 4096 Aug 21 10:54 ../
-rwxrwxr-x 1 aariv aariv 6074 Aug 21 10:43 dual_camera.py*
-rwxrwxr-x 1 aariv aariv 3356 Aug 21 10:43 face_detect.py*
drwxrwxr-x 2 aariv aariv 4096 Aug 21 11:25 images/
-rwxrwxr-x 1 aariv aariv 6782 Aug 21 10:43 README.md*
-rwxrwxr-x 1 aariv aariv 1963 Aug 21 10:43 simple_camera.cpp*
-rwxrwxr-x 1 aariv aariv 2607 Aug 21 10:43 simple_camera.py*
```
## ▶️ Run Example Scripts
You can test the camera using the provided Python scripts:

1. Run Simple Camera Preview
```
python3 simple_camera.py
```
2. Run Face Detection Example
```
python3 face_detect.py
```
   



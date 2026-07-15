# IRUAV-Net

Official PyTorch implementation of IRUAV-Net.

---

## ⚙️ Requirements

- Python 3.10  
- PyTorch 2.12.0 (CUDA 12.8)   
- opencv-python  
- numpy  
- scikit-image  
---

## 📂 Dataset

We use the following dataset:

### HIT-UAV
- Download: https://github.com/suojiashun/HIT-UAV-Infrared-Thermal-Dataset  
---
## 🚀 Training & Testing

### Training
python train.py

You can modify training configurations in train.py, including:

- dataset path
- batch size
- number of epochs

### Testing
python test_xxx.py


We have provided the testing code, dataset, and weights to facilitate the review of our work.

(1) Baidu Drive link: [Baidu Driver Download here](https://pan.baidu.com/s/1suEddcIqWobJtBXvgeyd_g?pwd=gf85). Access Code: gf85 

(2) Google Drive link: [Google Driver Download here](https://drive.google.com/drive/folders/12zwIB2bTb50LWs4WnpvVjCOLg4W5Z0B9?usp=drive_link).

To verify our experimental results, please download the code, dataset, weights, install the necessary dependencies via requirements.txt, and run the val.py script.




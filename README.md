# Intel-Image-Dataset
--- 

[Part 2: homebrewed CNN](https://github.com/Yalnyra/Intel-Image-Dataset/blob/main/Vinokur_Model_2.ipynb)
### Requirements

### TODO: add conda requirements.yml 

Clone dataset https://drive.google.com/file/d/1xEwPYoiY8wsyF33LCTrRhDywbfC82f-g/view?usp=sharing

locally or on your drive

If using Google Drive:
upload the following into your drive and unzip: 
Set up URL variable:
<
URL = "drive/MyDrive/Intel-Image-Classification"
# Alternative path, if using kaggle
# URL = "/kaggle/input/intel-image-classification"
# Dataset folders
folder = {"kaggle": 'seg_pred/seg_pred',
          'train': 'seg_train/seg_train',
          'test': 'seg_test/seg_test'
          }
BATCH_SIZE = 64
_NUM_WORKERS = os.cpu_count() // 2
# For reproducibility
SEED = 1234


`` pip install torchvision ``
`` pip install wandb==0.17.6 ``

(Optional) if desired to log, use ``wandb login`` in cmdline or inside notebook first
>
>
DLCV Coursework, Semi-supervised challenge 

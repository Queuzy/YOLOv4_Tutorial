# YOLO v4 Tutorial

YOLO v4 tiny Tutorial with Kaggle Oral Cancer (Lips and Tongue) images Dataset

## 1. Buildup instruction

1. Open [setup.ipynb](setup.ipynb)
2. Click `Open in Colab` button on the top
3. Run code and link your own Google drive
4. Check "`YOLOv4_Tutorial`" folder at drive home page

## 2. Dataset annotation

* LabelImg installation: 
1. Open terminal and activate python environment
2. type `> pip install labelImg` to install labelImg
3. type `> labelImg` to open labelImg

* Source dataset link on Kaggle:
 https://www.kaggle.com/code/shivam17299/oral-cancer-lips-and-tongue-images-dataset

## 3. YOLO v4 training

1. Modify model configuration in [yolov4_custom.cfg](yolov4_custom.cfg)
2. Open [yolov4.ipynb](yolov4.ipynb)
3. Click menu bar `Runtime > Run all` to execute entire program
4. Link Google drive and check execution message
5. Wait for finishing the training progress

# OGSOD-1.0-Dataset
Multimodal object detection dataset for SAR and optical images
数据集 (Dataset)

# 数据集简介
* **数据量**：训练集包含 14665 张可见光和SAR图像对，测试集包含3666张图像对。
* **类别**：bridge harbor storage tank。
* **格式**： Ultralytics YOLO Oriented Bounding Boxes 1.0 。

# 下载地址
数据集托管在 Google Drive 上，请点击下方链接下载：
standard : [https://drive.google.com/drive/folders/1V5BRbZYjHfmIp8qpKmqT_CcTyIJwiKOV?usp=sharing]
Oriented Bounding Boxes: [https://drive.google.com/drive/folders/1VIOpBJkZ4eG4hoZCzSOt3Bl1PCUL6LXZ?usp=sharing]

# 数据目录结构
下载解压后，请将数据集按照以下结构放置在项目根目录：
data/
OGSOD-1.0
  ├──rgb
  │  └── images/
  │  │      ├──test
  │  │      └──train
  │  └── labels/
  │        ├──test/
  │        └──train/
  └──sar  
     └── images/
     │      ├──test/
     │      └──train/
     └── labels/
           ├──test/
           └──train/
        

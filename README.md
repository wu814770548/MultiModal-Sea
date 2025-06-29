# 多模态海洋数据集（MultiModal-Sea Dataset）
鉴于当前海面多源遥感图像数据存在显著缺失，直接开展多源去噪研究面临数据稀缺、模态差异、配准困难等挑战。因此，拟采用“由单模态到多模态、由浅入深逐步融合”的技术路线。
![image name](https://github.com/user-attachments/assets/56f21fd7-1fdf-4e87-8d3f-6a1076fa3eac#pic_center=100x100)
## 数据集介绍
1.**高光谱图像（Hyperspectral)**：由五个不同图像的HyRANK数据集和224个波段的KSC数据集构成:<br>
**HyRANK数据集**:是由Hyperion传感器获取的。包含了两幅用于训练的高光谱图像和三幅用于测试的高光谱图像。五幅图像均有176个光谱波段，图像大小各不相同。所提供的训练样本包括水体、树木、农田、建筑物等14种场景。以下为样本展示。<br>
![image](https://github.com/user-attachments/assets/5e98e3d7-7e71-41f8-b038-4fa5894480f7) <br>
**KSC数据集**:由AVIRIS传感器在佛罗里达州肯尼迪太空中心于1996年3月23日拍摄。这个数据包含了224个波段，经过水汽噪声去除后还剩下176个波段，共包括沼泽、泥滩、水域等13种场景。以下为样本展示。<br>
![image](https://github.com/user-attachments/assets/6ded1a66-3ac5-4bde-9a43-d47020398f11)<br>

2.**光学遥感图像（Optical）**:由AID,RSI-CB等不同数据集的汇总，共一万六千多个样本。<br>
**AID数据集**:是一个大规模航空图像数据集，通过从谷歌地球图像中收集样本图像。该数据集包含海滩、河流、桥梁等30种航空场景，以下是样本展示。
![image](https://github.com/user-attachments/assets/5e8dd7ca-e5e8-474a-9556-fbe0d0362b22)<br>
**RSI-CB数据集**是一个大规模遥感图像数据集。该数据集包含RSI-CB128和RSI-CB256两个子数据集，涵盖交通运输及设施、水域及水利设施等多种场景。以下是样本展示。
![image](https://github.com/user-attachments/assets/d564fd01-b4cc-4f68-b3f2-a246c34a5302)<br>
**MAI数据集**是由来自Google地球图像的 3,923 张大型图像组成，覆盖美国、德国和法国。总共包含海滩、港口、河流、海洋等24 个场景，以下是样本展示。
![image](https://github.com/user-attachments/assets/fe55b8b0-4cc1-4971-a2d5-e865aa6cd077)<br>
**UCMercedLandUse数据集**是从USGS National Map Urban Area Imagery集合的影像中手动提取的高光谱数据的真彩色显示，包括海滩、港口、河流、海洋、湖等多个类别，以下是样本展示。
![image](https://github.com/user-attachments/assets/a75c517b-04a9-4fa8-997b-fd2c9f23e0d6)<br>
**NWPU-RESISC45数据集**是一个遥感图像的大规模公开数据集。该数据具有空间分辨率、视角等多样性且包含海滩、桥梁、云、港口、河流、海冰等多种场景，以下是样本展示。
![image](https://github.com/user-attachments/assets/5fb8e2b1-6727-41b6-9e9a-1b0d02be6d6d)<br>
**WHU-RS19数据集**是来源于谷歌卫星影像上获取的遥感影像构成的数据集，覆盖中国的城市地区，包含水池、桥梁、港港口、河流等多种遥感场景，以下是样本展示。
![image](https://github.com/user-attachments/assets/f6c00e26-fafe-4be1-a29d-4844c714100f)<br>
3.**SAR图像（SAR）**:由包含100张SAR图像的WHU-OPT-SAR数据集和31张SAR图像的AIR-SARShip-1.0数据集构成。<br>
**WHU-OPT-SAR数据集**包含100张5556*3704 像素的SAR图像，覆盖面积为51448.56km2分辨率为5米。WHU-OPT-SAR数据集覆盖了广泛的遥感影像，包括山脉、林地、丘陵、平原，河流等不同地形和针叶林、阔叶林、灌木和水生植被等不同植被。下面是样本展示。
![image](https://github.com/user-attachments/assets/45d3b994-33b2-4912-a614-c6f1d296f764)<br>
**AIR-SARShip-1.0数据集**首批发布31幅图像，图像分辨率包括1m和3m，成像模式包括聚束式和条带式，极化方式为单极化，场景包含港口、岛礁、不同等级海况的海面，目标覆盖运输船、油船、渔船等十余类近千艘舰船。图像尺寸约为3000×3000像素，图像格式为Tiff、单通道、8/16位图像深度，标注文件提供相应图像的长宽尺寸、标注目标的类别以及标注矩形框的位置。下面是样本展示。
![image](https://github.com/user-attachments/assets/df8e982b-4fed-4a03-b88a-829ceca58979)<br>
## 数据集下载
原始样本已上传本github站点，可直接下载压缩包，并解压使用。也可以从下方的地址下载：<br>
1.高光谱图像数据集（Hyperspectral):[https://pan.baidu.com/s/1NfNLWsKRNS3diDGZyQUU4Q?pwd=2asa](https://pan.baidu.com/s/1NfNLWsKRNS3diDGZyQUU4Q?pwd=2asa) 密码：2asa<br>
2.光学遥感图像数据集（Optical）:[https://pan.baidu.com/s/1W7VJG05oSg5GVAjk6ojbWA?pwd=2asa](https://pan.baidu.com/s/1W7VJG05oSg5GVAjk6ojbWA?pwd=2asa) 密码：2asa<br>
3.SAR图像数据集-WHU-OPT-SAR(SAR):[https://pan.baidu.com/s/137mtTtFDvVLOIt1gpppbQQ?pwd=2asa](https://pan.baidu.com/s/137mtTtFDvVLOIt1gpppbQQ?pwd=2asa) 密码：2asa<br>
4.SAR图像数据集-AIR-SARShip-1.0(SAR):[https://pan.baidu.com/s/1vsVTSHYLfJt7-xCa84wsuQ?pwd=2asa](https://pan.baidu.com/s/1vsVTSHYLfJt7-xCa84wsuQ?pwd=2asa) 密码：2asa<br>

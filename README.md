# 口罩遮挡人脸数据集（Real-World Masked Face Dataset，RMFD）

近期全球新型冠状病毒肆虐，疫情严重地区（如武汉）几乎人人戴口罩，具有海量样本基数。收集样本建立全球最大口罩人脸数据集，并向社会开放，为当前及今后可能的类似公共安全事件智能管控积累数据资源。基于口罩人脸数据，设计相应口罩遮挡人脸检测和识别算法，帮助社区封闭时的人员进出管控，车站、机场的人脸识别闸机以及人脸门禁考勤设备的升级，适应行人口罩蒙面遮挡的应用环境。

发起单位：武汉大学国家多媒体软件工程技术研究中心

联系人：熊张洋，联系邮箱：x_zhangyang@whu.edu.cn

为了进一步扩充数据集，欢迎大家将个人收集到的戴口罩图片，通过邮件的方式发送到 x_zhangyang@whu.edu.cn，我们会对收到的图片统一处理。

## 数据集下载

部分原始样本已上传本github站点，RMFD_part_1可直接下载使用，RMFD_part_2 (4个压缩文件) 和RMFD_part_3 (3个压缩文件) 需要下载全部压缩文件后，再进行解压。也可以从下方的地址下载：

链接: https://pan.baidu.com/s/1Vly3K-0qjlB6M2lenTZ8PA 提取码: xhze 

或者 https://drive.google.com/open?id=1kZAIiv34Iav9Vt8BB101FXo4KoEClpx9

已标注数据集说明如下：（区别于github中raw samples） 不同于人脸口罩识别（或检测）数据集，口罩人脸识别样本集须得包含同一人的多张戴口罩与未戴口罩的人脸图像，为此，我们建立了两种口罩人脸识别样本集。

(1) 真实口罩人脸识别数据集：从网络爬取样本，经过整理、清洗和标注后，含525人的5千张口罩人脸、9万正常人脸。 

下载地址： https://pan.baidu.com/s/1XvGepj84SCA9rlVb9rGhEQ 密码：j3aq

或者 https://drive.google.com/open?id=1UlOk6EtiaXTHylRUx2mySgvJX9ycoeBp


(2) 模拟口罩人脸识别数据集： 给公开数据集中的人脸戴上口罩，得到1万人、50万张人脸的模拟口罩人脸数据集。 

WebFace模拟口罩人脸数据集： 

下载地址： https://pan.baidu.com/s/1Qi_8D_kH2QCm761elZs5YA 密码: 77m8 

或者 https://drive.google.com/open?id=1q0ibaoFVEmXrjlk3-Oyx2oYR8HpVy6jc

LFW模拟口罩人脸数据集: 

下载地址：https://pan.baidu.com/s/1Ge0KcYgu6oVAbLlDHCKwRg 密码: o126

或者 https://drive.google.com/open?id=1soLIUkGruSKMzg5z5_OYYqUVoca4E_lI

## 口罩人脸识别

基于建立的数据集，设计和训练了面部-眉眼多粒度口罩人脸识别模型，数据集上的识别精度达到95%，部分动态视频演示见：

链接: https://pan.baidu.com/s/1P0PiWFNT1z_TcCj8vo43ow 提取码: acwe 

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wnx.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wuhao.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/hzb.gif)



## 相关工作

https://arxiv.org/abs/2003.09093

## 原始样本示例：

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0003.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0001.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0002.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/0.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/1.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/2.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/3.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/4.jpg)

#
# Real-World Masked Face Dataset（RMFD）

Because of the recent epidemic of COVID-19 virus around the world, people across the country wear masks and there appear a large number of masked face samples. We thus created the world's largest masked face dataset to accumulate data resources for possible intelligent management and control of similar public safety events in the future. Based on masked face dataset, corresponding masked face detection and recognition algorithms are designed to help people in and out of the community when the community is closed. In addition, the upgrade of face recognition gates, facial attendance machines, and facial security checks at train stations is adapted to the application environment of pedestrian wearing masks.

Sponsor: National Engineering Research Center for Multimedia Software (NERCMS), School of Computer Science, Wuhan University

Contact: Zhangyang Xiong, Email: x_zhangyang@whu.edu.cn

In order to further expand this dataset, everyone is welcome to send personally collected pictures of masks to x_zhangyang@whu.edu.cn by email, and we will process the received pictures uniformly.

## Download Datasets

Part of the original samples has been uploaded to this github website. RFMD_part_1 can be downloaded directly. RFMD_part_2 (4 compressed files) and RFMD_part_3 (3 compressed files) need to download all compressed files before decompressing them.You can also download these datasets from the link below.

Download link: https://pan.baidu.com/s/1Vly3K-0qjlB6M2lenTZ8PA Password: xhze 

or https://drive.google.com/open?id=1kZAIiv34Iav9Vt8BB101FXo4KoEClpx9

More labeled face samples are illustrated as follows: (different from raw samples in github) Different from the facial mask recognition (or detection) dataset, the masked face recognition dataset must include multiple masked and unmasked face images of the same subject. To this end, we have established two kinds of masked face recognition datasets. 

(1)	Real-world masked face recognition dataset: We crawled the samples from the website. After cleaning and labeling, it contains 5,000 masked faces of 525 people and 90,000 normal faces. 

Download link: https://pan.baidu.com/s/1XvGepj84SCA9rlVb9rGhEQ  Password: j3aq

or https://drive.google.com/open?id=1UlOk6EtiaXTHylRUx2mySgvJX9ycoeBp

(2)	Simulated masked face recognition datasets: We put on the masks on the faces in the public face datasets, and obtained the simulated masked face dataset of 500,000 faces of 10,000 subjects.

WebFace simulated masked face dataset:
https://pan.baidu.com/s/1Qi_8D_kH2QCm761elZs5YA Password: 77m8

or https://drive.google.com/open?id=1q0ibaoFVEmXrjlk3-Oyx2oYR8HpVy6jc

LFW simulated masked face dataset:
https://pan.baidu.com/s/1Ge0KcYgu6oVAbLlDHCKwRg Password: o126

or https://drive.google.com/open?id=1soLIUkGruSKMzg5z5_OYYqUVoca4E_lI

## Masked Face Recognition

Based on the constructed datasets, we designed and trained a face-eye-based multi-granularity masked face recognition model. The face identification accuracy on the dataset is over 95%, and some real-time video demos are as follows:

Download link: https://pan.baidu.com/s/1P0PiWFNT1z_TcCj8vo43ow Password: acwe 

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wnx.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/wuhao.gif)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/demo/hzb.gif)


## Related Work

https://arxiv.org/abs/2003.09093
 
## Examples of Raw Samples

![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0003.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0001.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/RWMFD_part_1/0000/0002.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/0.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/1.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/2.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/3.jpg)
![image](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset/blob/master/example/4.jpg)

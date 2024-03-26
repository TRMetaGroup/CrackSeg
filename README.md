# 1. Dataset Introduction

We have open-sourced a large-scale, meticulously annotated crack segmentation dataset, which is aimed at the most common on-board  camera scenarios.

This  dataset consists of **3,540 high-resolution images**  (**3840$\times$2160** pixels)  shot from several roads in Shandong Province, China, using a camera-equipped vehicle. The collected images are then meticulously annotated with pixel-level semantic masks by a team of professionals who meticulously annotated the locations and shapes of cracks on the images using the CVAT annotation tool.

 To note, the annotation process for each image underwent thorough inspection and verification to ensure the accuracy and consistency of the labels. Furthermore, we ensured that the dataset includes images captured under **different road types** (e.g., freeways, national and provincial highways, etc.) to enhance the model's generalization capability.
![crack distribution heatmaps](images\image1.png)

The dataset encompasses a total of 3,540 images, with **70% (2,478 images) designated for training**, **10% (354 images) for validation**, and the remaining **20% (708 images) for testing**. The crack distribution heatmaps in the training, validation, and testing sets are depicted in Figure above. It can be observed that these cracks are mostly confined to the road surface under the on-board camera perspective.

![image-20240326182448286](images\table1.png) 

The comparison of our dataset with existing datasets can be seen in Table above and Figure below. It can be observed that our dataset (i.e., CrackSeg)  has significant advantages in both data scale and scene challenges. 


![image-20240326181652592](images\image2.png)

# 2. Dataset Download
* trainset (5.05 GB): [BaiduYun](https://pan.baidu.com/s/1jxdur0_ebq4omdHq4Jtx3w) (Extraction code: 7w9p)
  
* valset (658MB):  [BaiduYun](https://pan.baidu.com/s/1ZRx2cOzu2dft1HTHK6A4qw ) (Extraction code: 5suz )
  
* testset-dev (1.31 GB): [BaiduYun](https://pan.baidu.com/s/12l277_KAP6ul_moaFM6mrA) (Extraction code: x9qn  )


# 3. Citation

Our paper has been submitted to the *IEEE Transactions on Intelligent Transportation Systems* and is currently under the second round of review. The title of the paper is **'Teaching Segment-Anything-Model Domain-specific Knowledge for Road Crack Segmentation from On-board Cameras'**.

Once published, we welcome everyone to actively cite it if this dataset has been helpful to your research!

# 4. Issue Feedback
If you find any inaccuracies or unreasonable aspects in our dataset annotations, please provide us with timely feedback, and we will address the issues as soon as possible. Our contact email is: vvgod@seu.edu.cn.
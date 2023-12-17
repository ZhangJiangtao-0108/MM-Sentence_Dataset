# MM-Sentence Dataset

## Introduction
---


## Download
---
The MM-Sentence database is released to universities and research institutes for research purpose only. To request the access right to the data resources, please follow the instructions below:
- Download the [MM-Sentence Dataset Release Agreement](https://github.com/ZhangJiangtao-0108/MM-Sentence_Dataset/blob/main/MM-Sentence%20_Dataset%20_Release%20_Agreement.pdf);
- Read all items and conditions carefully;
- Complete it appropriately. Note that the agreement should be signed by a full-time staff member (that is, the student is not acceptable).
- Please scan the signed agreement, send it to (zhangjiangtao@mail.hfut.edu.cn) and CC to Prof. Wang (qswang@hfut.edu.cn). If you are a student, please also CC to the full-time staff member who sign the agreement.

## Introduction
We utilize logitech C922xPro Stream Web camera and the armband with built-in sEMG and IMU sensors to collect sign language data.
Where the frame rate of the camera is 60fps and the resolution is 1920*1080 pixels.
The sampling frequencies of sEMG and IMU sensors are 200Hz and 50Hz, respectively
This dataset contains 182 sign language sentences with a total of 34 sign words.
11 volunteers are asked to perform the sign language sentences five times.
As shown in feature, 14 upper body joints and 42 hand joint points of the volunteers are extracted by OpenPose as the skeletal modalities of the MM-Sentence dataset.
Each instance in this datasets contains RGB videos, Skeletal, sEMG and IMU information of the signer.
![Skeletal points]()

## Reference
---
Please cite the following papers if you use MM-Sentence dataset for your research:

  
Besides, you can refer to the following papers for continuous SLR published by our group:
- J. Zhang, Q. Wang, Q. Wang, and Z. Zheng, “Multimodal fusion framework based on statistical attention and contrastive attention for sign language recognition,” IEEE Transactions on Mobile Computing, pp. 1–13, 2023, doi:10.1109/TMC.2023.3235935
- J. Zhang, Q. Wang, and Q. Wang, “HDTSLR: A framework based on hierarchical dynamic positional encoding for sign language recognition,” IEEE Transactions on Mobile Computing, pp. 1–13, 2023, doi:10.1109/TMC.2023.3310712

OpenPose Reference：
- Z. Cao, G. Hidalgo, T. Simon, S.-E. Wei, and Y. Sheikh, “Openpose: Realtime multi-person 2d pose estimation using part affinity fields,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 43, no. 1, pp. 172–186, 2021.
- T. Simon, H. Joo, I. Matthews, and Y. Sheikh, “Hand keypoint detection in single images using multiview bootstrapping,” in CVPR, 2017, pp. 4645–4653.
- Z. Cao, T. Simon, S.-E. Wei, and Y. Sheikh, “Realtime multi-person 2d pose estimation using part affinity fields,” in CVPR, 2017, pp. 1302–1310.
- S.-E. Wei, V. Ramakrishna, T. Kanade, and Y. Sheikh, “Convolutional pose machines,” in CVPR, 2016, pp. 4724–4732.

## Contact
If you have any questions about the dataset and our papers, please feel free to contact us:
- Qingshan wang, Professor, HFUT, qswang@hfut.edu.cn
- Jiangtao Zhang, Ph.D Student, HFUT, zhangjiangtao@mail.hfut.edu.cn

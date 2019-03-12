# awesome_video_person_reid
only focus on video person re-identification

# 2014
## 1.Person Re-identification by Video Ranking --ECCV2014  [[paper](http://www.eecs.qmul.ac.uk/~sgg/papers/WangEtAl_ECCV14.pdf)]
    特征（feature）： HOG3D
    本文的主要贡献&创新点：开源了新的视频序列数据集iLIDS-VID；能从有噪声的帧序列中选出关键帧；学习一个视频排序函数.
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1          28.9            23.3
# 2015
## 2.Sparse Re-ID: Block Sparsity for Person Re-identification --CVPR2015 [[paper](http://openaccess.thecvf.com/content_cvpr_workshops_2015/W14/papers/Karanam_Sparse_Re-Id_Block_2015_CVPR_paper.pdf)]
    特征（feature）： Color Histograms Schmid & Gabor Filters
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1          24.9            35.1

## 3.A Spatio-temporal Appearance Representation for Video-based Pedestrian Re-identification --ICCV2015 [[paper](https://ieeexplore.ieee.org/document/7410791)]
    特征（feature）： Fiser vector
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1          44.3            64.1

# 2016
## 4.Deep Recurrent Convolutional Networks for Video-based Person Re-identification: An End-to-End Approach --arxiv2016 [[paper](https://arxiv.org/abs/1606.01609.pdf)]
    特征（feature）： four CNN（四层卷积神经网络）
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1          42.6            49.8  

## 5.Top-push Video-based Person Re-identification --CVPR 2016 [[paper](https://arxiv.org/abs/1604.08683.pdf)]
    特征（feature）： HOG3D+color histograms+LBP
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1           56.33          56.74      
 
## 6.Person Re-identification by Exploiting Spatio-temporal Cues and Multi-view Metric Learning --IEEE SRL 2016 [[paper](https://arxiv.org/abs/1604.08683.pdf)]
    特征（feature）： LBP
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1          69.13           66.78     
 
## 7.Person Re-identification via Recurrent Feature Aggregation  --ECCV2016 [[paper](https://arxiv.org/abs/1701.06351.pdf)][[code](https://github.com/daodaofr/caffe-re-id)]
    特征（feature）： LBP+HSV+lab color channels
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1           49.3           64.1

## 8.Recurrent Convolutional Network for Video-based Person Re-identification  --CVPR2016 [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/McLaughlin_Recurrent_Convolutional_Network_CVPR_2016_paper.pdf)] [[code](https://github.com/niallmcl/Recurrent-Convolutional-Video-ReID)]
    特征（feature）： CNN + RNN  (非常经典的结构)
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1           58              70      

# 2017
## 9.Video-based Person Re-identification with Accumulative Motion Contex  --TCSVT2017 [[paper](https://arxiv.org/abs/1701.00193.pdf)]
    特征（feature）： CNN + RNN + opticflow 
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1           65.3            78            

## 10.Learning Compact Appearance Representation for Video-based Person Re-identification  --arxiv2017 [[paper](https://arxiv.org/abs/1702.06294.pdf)] 
    特征（feature）： Five CNN (5层卷积神经网络)
    实验结果(results)：
                         iLIDS-VID         PRID
            Rank1           60.4           83.3

## 11.See the Forest for the Trees: Joint Spatial and Temporal Recurrent Neural Networks for Video-based Person Re-identification   --CVPR2017 [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_See_the_Forest_CVPR_2017_paper.pdf)]
    特征（feature）： Temporal Attention Model (TAM) + Spatial Recurrent Model (SRM)
    实验结果(results)：
                         iLIDS-VID         PRID          Mars
            Rank1           55.2           79.4          70.6
            mAP              --             --           50.7
 
 ## 12.Quality Aware Network for Set to Set Recognition   --CVPR2017 [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_See_the_Forest_CVPR_2017_paper.pdf)] [[code](https://github.com/sciencefans/Quality-Aware-Network)]
    特征（feature）： CNN（GoogleNet）
    实验结果(results)：
                         iLIDS-VID         PRID          
            Rank1           68.0           90.3       
 
 ## 13.Jointly Attentive Spatial-Temporal Pooling Networks for Video-based Person Re-identification    --ICCV2017 [[paper](https://arxiv.org/abs/1708.02286.pdf)] [[code](https://github.com/shuangjiexu/Spatial-Temporal-Pooling-Networks-ReID)]
 # 博客解读：[[CSDN](https://blog.csdn.net/qq_34132310/article/details/88429853)]
    特征（feature）： (3层)CNN + RNN + attention
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           62              77            44   
 
 ## 14.A Two Stream Siamese Convolutional Neural Network For Person Re-identification    --ICCV2017 [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chung_A_Two_Stream_ICCV_2017_paper.pdf)] 
    特征（feature）： CNN + RNN + attention  => siamese network
    实验结果(results)：
                         iLIDS-VID         PRID          
            Rank1           60              78       
 
 ## 15.Deep Cross-Modality Alignmeant for Multi-Shot Person Re-Identification   --MM2017 [[paper](https://dl.acm.org/citation.cfm?id=3123266.3123324)] 
    特征（feature）： (3层)CNN + RNN + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           60              80           63     
 
## 16.Data Generation for Improving Person Re-identification    --MM2017 [[paper](https://dl.acm.org/citation.cfm?id=3123302)] 
    特征（feature）： (3层)CNN + RNN + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID                
            Rank1           66              79            
 
## 17.Three-Stream Convolutional Networks for Video-based Person Re-Identification    --arxiv2017 [[paper](https://arxiv.org/abs/1712.01652.pdf)] 
    特征（feature）： (4层)CNN + RNN + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           67.5           79.7          45.6            

# 2018
## 18.TRegion-based Quality Estimation Network for Large-scale Person Re-identification    --AAAI2018 [[paper](https://arxiv.org/abs/1711.08766.pdf)] 
    特征（feature）： (4层)CNN + RNN + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           76.1           92.4          77.83            
            mAP              --             --           71.14

## 19.Video Person Re-identification by Temporal Residual Learning    --arxiv2018 [[paper](https://arxiv.org/abs/1802.07918.pdf)] 
    特征（feature）：  GoogleNet + BiLSTM
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           57.7           87.8          79.3            

## 20.Diversity Regularized Spatiotemporal Attention for Video-based Person Re-identification    --CVPR2018 [[paper](https://arxiv.org/pdf/1803.09882.pdf)] [[code](https://github.com/ShuangLI59/Diversity-Regularized-Spatiotemporal-Attention)]
    特征（feature）： Resnet50 + attention
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           80.2           93.2          82.3            
            mAP              --             --           65.8

## 21.Multi-shot Pedestrian Re-identification via Sequential Decision Making    --CVPR2018 [[paper](https://arxiv.org/pdf/1712.07257.pdf)] [[code](https://github.com/TuSimple/rl-multishot-reid)]
    特征（feature）： Inception-BN or AlexNet
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           60.2           85.2          71.2            

## 22.Exploit the Unknown Gradually: One-Shot Video-Based Person Re-Identification by Stepwise Learning    --CVPR2018 [[paper](https://yu-wu.net/pdf/CVPR2018_Exploit-Unknown-Gradually.pdf)] [[code](https://github.com/Yu-Wu/Exploit-Unknown-Gradually)]
    特征（feature）： ResNet50 + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars          DukeMTMC-VideoReID      
            Rank1           --              --          62.67               72.79 
            mAP              --             --          42.45               63.23

## 23.Video Person Re-identification with Competitive Snippet-similarity Aggregation and Co-attentive Snippet Embedding    --CVPR2018 [[paper](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1036.pdf)] [[code](https://github.com/dapengchen123/video_reid)]
    特征（feature）： ResNet50 + attention
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           85.4           93.0          86.3           
            mAP             87.8           94.5          76.1 

## 24.SCAN: Self-and-Collaborative Attention Network for Video Person Re-identification    --CVPR2018 [[paper](https://arxiv.org/pdf/1807.05688.pdf)] 
    特征（feature）： ResNet50 + attention
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           88.0           95.3          87.2           
            mAP             89.9           95.8          77.2 

## 25.Video-based Person Re-identification via 3D Convolutional Networks and Non-local Attention    --arxiv2018 [[paper](https://arxiv.org/abs/1807.05073.pdf)] 
    特征（feature）： ResNet50-3D + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1           81.3           91.2          84.3           
            mAP              --             --            77 

## 26.Spatial-Temporal Synergic Residual Learning for Video Person Re-Identification    --arxiv2018 [[paper](https://arxiv.org/pdf/1807.05799.pdf)] 
    特征（feature）： CNN + RNN + avgpooling
    实验结果(results)：
                         iLIDS-VID         PRID          Mars        
            Rank1            70             88           76.7           

# Bio of Quan Dou (权豆)                               
<p align="center">
 <img src="quandou.jpg" width="50%" height="50%" align='center'/>
</p>

  从2023年1月到现在，我就职于西安电子科技大学人工智能学院，任副教授。主要从事图像配准与变化检测相关研究工作。当前我的合作导师是[**焦李成**](http://www.liuyebin.com/)教授。我与清华大学**呼延宁**（博士后）保持良好合作关系，并共同开展相关研究工作。2019年11月到2020年11月曾在法国格勒诺布尔法国国家信息与自动化研究所访问交流，与[**jocelyn chanussot**](https://jocelyn-chanussot.net/)愉快合作。2011年到2022年在西安电子科技大学分别取得学士和博士学位。攻读博士期间主要跟随西安电子科技大学人工智能学院[**王爽**](https://web.xidian.edu.cn/shwang/)教授, 从事SAR图像配准相关研究工作。


## 研究兴趣:

SAR图像配准，变化检测，主要技术涉及深度学习，机器学习算法。

## 工作经历:

* 01/2023 - 至今:    副教授， 西安电子科技大学人工智能学院，北京，中国。

* 06/2022 - 09/2011: 学士—博士， 西安电子科技大学，陕西西安，中国。

## 最新消息:

**Mar 2025:** 我们的文章 **123** 被 ***CVPR 2025***接收.



## 热点论文:
* Shuang Wang, **Dou Quan**, Xuefeng Liang, Mengdan Ning, Yanhe Guo, Licheng Jiao. **A deep learning framework for remote sensing image registration**. ISPRS Journal of Photogrammetry and Remote Sensing 145, 148-164.2018/11/1.
  
<p align="center">
 <img src="MCOD.png" width="50%" height="50%"/>
</p>

+ **Abstract:** We propose an effective deep neural network aiming at remote sensing image registration problem. Unlike conventional methods doing feature extraction and feature matching separately, we pair patches from sensed and reference images, and then learn the mapping directly between these patch-pairs and their matching labels for later registration. This end-to-end architecture allows us to optimize the whole processing (learning mapping function) through information feedback when training the network, which is lacking in conventional methods. In addition, to alleviate the small data issue of remote sensing images for training, our proposal introduces a self-learning by learning the mapping function using images and their transformed copies. Moreover, we apply a transfer learning to reduce the huge computation cost in the training stage. It does not only speed up our framework, but also get extra performance gains. The comprehensive experiments conducted on seven sets of remote sensing images, acquired by Radarsat, SPOT and Landsat, show that our proposal improves the registration accuracy up to 2.4–53.7%.
  [**PDF**](https://www.sciencedirect.com/science/article/pii/S0924271617303891) [**CODE**]()
  
* **Dou Quan**, Xuefeng Liang, Shuang Wang, Shaowei Wei, Yanfeng Li, Ning Huyan, Licheng Jiao. **AFD-Net: Aggregated feature difference learning for cross-spectral image patch matching**. Proceedings of the IEEE/CVF International Conference on Computer Vision(2019) 3017-3026.
  
<p align="center">
 <img src="AUD.png" width="50%" height="50%" align='center'/>
 </p>
 
+ **Abstract:** Image patch matching across different spectral domains is more challenging than in a single spectral domain. We consider the reason is twofold: 1. the weaker discriminative feature learned by conventional methods; 2. the significant appearance difference between two images domains. To tackle these problems, we propose an aggregated feature difference learning network (AFD-Net). Unlike other methods that merely rely on the high-level features, we find the feature differences in other levels also provide useful learning information. Thus, the multi-level feature differences are aggregated to enhance the discrimination. To make features invariant across different domains, we introduce a domain invariant feature extraction network based on instance normalization (IN). In order to optimize the AFD-Net, we borrow the large margin cosine loss which can minimize intra-class distance and maximize inter-class distance between matching and non-matching samples. Extensive experiments show that AFD-Net largely outperforms the state-of-the-arts on the cross-spectral dataset, meanwhile, demonstrates a considerable generalizability on a single spectral dataset.  [**PDF**](https://openaccess.thecvf.com/content_ICCV_2019/html/Quan_AFD-Net_Aggregated_Feature_Difference_Learning_for_Cross-Spectral_Image_Patch_Matching_ICCV_2019_paper.html) [**CODE**]()
  
* **Ning Huyan**, Xiangrong Zhang, Huiyu Zhou, Licheng Jiao. **Hyperspectral anomaly detection via background and potential anomaly dictionaries construction**. IEEE Transactions on Geoscience and Remote Sensing 57 (4), 2263-2276. 2018/11/1.
  
<p align="center">
 <img src="ABD.png" width="50%" height="50%" align='center'/>
  </p>
  
+ **Abstract:** In this paper, we propose a new anomaly detection method for hyperspectral images based on two well-designed dictionaries: background dictionary and potential anomaly dictionary. In order to effectively detect an anomaly and eliminate the influence of noise, the original image is decomposed into three components: background, anomalies, and noise. In this way, the anomaly detection task is regarded as a problem of matrix decomposition. Considering the homogeneity of background and the sparsity of anomalies, the low-rank and sparse constraints are imposed in our model. Then, the background and potential anomaly dictionaries are constructed using the background and anomaly priors. For the background dictionary, a joint sparse representation (JSR)-based dictionary selection strategy is proposed, assuming that the frequently used atoms in the overcomplete dictionary tend to be the background. In order to make full use of the prior information of anomalies hidden in the scene, the potential anomaly dictionary is constructed. We define a criterion, i.e., the anomalous level of a pixel, by using the residual calculated in the JSR model within its local region. Then, it is combined with a weighted term to alleviate the influence of noise and background. Experiments show that our proposed anomaly detection method based on potential anomaly and background dictionaries construction can achieve superior results compared with other state-of-the-art methods.  [**PDF**](https://ieeexplore.ieee.org/abstract/document/8519775)
  
* **Ning Huyan**, Xiangrong Zhang, Dou Quan, Jocelyn Chanussot, Licheng Jiao. **Cluster-memory augmented deep autoencoder via optimal transportation for hyperspectral anomaly detection**. IEEE Transactions on Geoscience and Remote Sensing 60, 1-16. 2022/6/6.
  
<p align="center">
 <img src="OTCMA.png" width="50%" height="50%" align='center'/>
  </p>
  
+ **Abstract:** Hyperspectral anomaly detection (AD) aims to detect objects significantly different from their surrounding background. Recently, many detectors based on autoencoder (AE) exhibited promising performances in hyperspectral AD tasks. However, the fundamental hypothesis of the AE-based detector that anomaly is more challenging to be reconstructed than background may not always be true in practice. We demonstrate that an AE could well reconstruct anomalies even without anomalies for training, because AE models mainly focus on the quality of sample reconstruction and do not care if the encoded features solely represent the background rather than anomalies. If more information is preserved than needed to reconstruct the background, the anomalies will be well reconstructed. This article proposes a cluster-memory augmented deep autoencoder via optimal transportation for hyperspectral anomaly detection (OTCMA) clustering for hyperspectral AD to solve this problem. The deep clustering method based on optimal transportation (OT) is proposed to enhance the features consistency of samples within the same categories and features discrimination of samples in different categories. The memory module stores the background’s consistent features, which are the cluster centers for each category background. We retrieve more consistent features from the memory module instead of reconstructing a sample utilizing its own encoded features. The network focuses more on consistent feature reconstruction by training AE with a memory module. This effectively restricts the reconstruction ability of AE and prevents reconstructing anomalies. Extensive experiments on the benchmark datasets demonstrate that our proposed OTCMA achieves state-of-the-art results. Besides, this article presents further discussions about the effectiveness of our proposed memory module and different criteria for better AD.  [**PDF**](https://ieeexplore.ieee.org/abstract/document/9789180) [**CODE**](https://github.com/huyanning/OTCMA-Net)




## 奖项:


## 联系方式: 

**Email:** quandou@xidian.edu.cn， douquan.xidian@gmail.com

**Address:** Xi'an, Shannxi, China.







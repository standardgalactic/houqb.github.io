---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Qibin Hou received his Ph.D. degree from Nankai University in 06/2019 under the supervision of Prof. Ming-Ming Cheng. From 08/2019 to 08/2021, I spent two wonderful years working with Dr. Jiashi Feng and Dr. Shuicheng Yan as a research fellow at National University of Singapore. Now, he is an associate professor at School of Computer Science, Nankai University, Tianjin, China. I am also with Nankai International Advanced Research Institute (Shenzhen Futian).
 <a href='https://scholar.google.com/citations?user=fF8OFV8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Citation"></a>。

## Research Interests：

My research covers a range of `Computer Vision` and `Deep Learning`. To be specific, my research concentrates on building AI models to help agents better see and understand the complex world. 

Specific directions: `Semantic Segmentation` `Object Detection` `Foundation Models`

See my recent publications for more details.

<span class='anchor' id='-student'></span>

## For perspective students

If you are interested in the research topics in my group, welcome to drop an email. Note that before contacting me, you are supposed to have read <a href="https://mmcheng.net/recruit/" class="redlink">[this]</a> already.

We have several projects each year from the industry to ensure the applications of our research.

<span class='anchor' id='-news'></span>

+ Five papers accepted by CVPR'24
+ Three papers accepted by ICLR'24 and AAAI'24
+ Three papers accepted by ICCV'23 and CVPR'23
+ Top 2% of Scientists on Stanford List
+ Five papers published in T-PAMI'2023
 
<span class='anchor' id='-lwzl'></span>

## Selected Journal Publications ([Google Scholar](https://scholar.google.com/citations?user=fF8OFV8AAAAJ&hl=en))

#### "*" means authors contributed equally and "#" means corresponding author.

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Vision permutator: A permutable mlp-like architecture for visual recognition</h4>   
  <sub><p style="line-height:15px"> <b>Qibin Hou</b>, Zihang Jiang, Li Yuan, Ming-Ming Cheng, Shuicheng Yan, Jiashi Feng</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2106.12368.pdf">[Arxiv]</a> <a href="https://github.com/Andrew-Qibin/VisionPermutator" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Volo: Vision outlooker for visual recognition</h4>   
  <sub><p style="line-height:15px"> Li Yuan*, <b>Qibin Hou</b>*, Zihang Jiang*, Jiashi Feng, Shuicheng Yan</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023</p>   
  <p style="line-height:15px"> <a href="https://ieeexplore.ieee.org/abstract/document/9888055">[Arxiv]</a> <a href="https://github.com/sail-sg/volo" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization distillation for object detection</h4>   
  <sub><p style="line-height:15px"> Zhaohui Zheng, Rongguang Ye, <b>Qibin Hou</b>#, Dongwei Ren, Ping Wang, Wangmeng Zuo, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2204.05957.pdf">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Deeply Supervised Salient Object Detection with Short Connections</h4>   
  <sub><p style="line-height:15px"> <b>Qibin Hou</b>, Ming-Ming Cheng, Xiaowei Hu, Ali Borji, Zhuowen Tu, Philip Torr</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2019</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2306.04300.pdf">[Arxiv]</a> <a href="https://github.com/Andrew-Qibin/DSS" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

## Selected Conference Publications ([Google Scholar](https://scholar.google.com/citations?user=fF8OFV8AAAAJ&hl=en))

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>CorrMatch: Label Propagation via Correlation Matching for Semi-Supervised Semantic Segmentation</h4>   
  <sub><p style="line-height:15px"> Boyuan Sun, Yuqi Yang, Le Zhang, Ming-Ming Cheng, <b>Qibin Hou#</b></p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Localization_Distillation_for_Dense_Object_Detection_CVPR_2022_paper.pdf">[Arxiv]</a> <a href="https://github.com/BBBBchan/CorrMatch">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>CrossKD: Cross-Head Knowledge Distillation for Dense Object Detection</h4>   
  <sub><p style="line-height:15px"> Jiabao Wang*, Yuming Chen*, Zhaohui Zheng, Xiang Li, Ming-Ming Cheng, <b>Qibin Hou#</b></p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2306.11369.pdf">[Arxiv]</a> <a href="https://github.com/jbwang1997/CrossKD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Dformer: Rethinking rgbd representation learning for semantic segmentation</h4>   
  <sub><p style="line-height:15px"> Bowen Yin, Xuying Zhang, Zhongyu Li, Li Liu, Ming-Ming Cheng, <b>Qibin Hou#</b> </p> 
  <p style="line-height:15px">International Conference on Learning Representations (ICLR), 2024</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2309.09668.pdf">[Arxiv]</a> <a href="https://github.com/VCIP-RGBD/DFormer">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>SRFormer: Permuted Self-Attention for Single Image Super-Resolution</h4>   
  <sub><p style="line-height:15px"> Yupeng Zhou, Zhen Li, Chun-Le Guo, Song Bai, Ming-Ming Cheng, <b>Qibin Hou#</b> </p> 
  <p style="line-height:15px">IEEE International Conference on Computer Vision (ICCV), 2023</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Zhou_SRFormer_Permuted_Self-Attention_for_Single_Image_Super-Resolution_ICCV_2023_paper.pdf">[Arxiv]</a> <a href="https://github.com/HVision-NKU/SRFormer">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization Distillation for Dense Object Detection</h4>   
  <sub><p style="line-height:15px"> Zhaohui Zheng*, Rongguang Ye*, Ping Wang, Dongwei Ren, Wangmeng Zuo, <b>Qibin Hou#</b>, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2022</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Localization_Distillation_for_Dense_Object_Detection_CVPR_2022_paper.pdf">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Coordinate attention for efficient mobile network design</h4>   
  <sub><p style="line-height:15px"> <b>Qibin Hou</b>, Daquan Zhou, Jiashi Feng</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Hou_Coordinate_Attention_for_Efficient_Mobile_Network_Design_CVPR_2021_paper.pdf">[Arxiv]</a> <a href="https://github.com/Andrew-Qibin/
CoordAttention">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Strip Pooling: Rethinking Spatial Pooling for Scene Parsing</h4>   
  <sub><p style="line-height:15px"> <b>Qibin Hou</b>, Li Zhang, Ming-Ming Cheng, Jiashi Feng</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2020</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2003.13328.pdf">[Arxiv]</a> <a href="https://github.com/Andrew-Qibin/SPNet">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>A Simple Pooling-Based Design for Real-Time Salient Object Detection</h4>   
  <sub><p style="line-height:15px"> Jiang-Jiang Liu*, <b>Qibin Hou*</b>, Ming-Ming Cheng, Jiashi Feng, Jianmin Jiang</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019</p>   
  <p style="line-height:15px"> <a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_A_Simple_Pooling-Based_Design_for_Real-Time_Salient_Object_Detection_CVPR_2019_paper.pdf">[Arxiv]</a> <a href="https://github.com/backseason/PoolNet">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Self-Earsing Networks for Integral Object Attention</h4>   
  <sub><p style="line-height:15px"> <b>Qibin Hou</b>, Peng-Tao Jiang, Yunchao Wei, Ming-Ming Cheng </p> 
  <p style="line-height:15px">Advances in Neural Information Processing Systems (NeurIPS), 2018</p>   
  <p style="line-height:15px"> <a href="https://papers.nips.cc/paper/7336-self-erasing-network-for-integral-object-attention.pdf">[Arxiv]</a> <a href="https://github.com/Andrew-Qibin/SeeNet">[Code]</a></p>   
  </sub>
</blockquote>



<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2015.11* 获得 第十四届“挑战杯”全国大学生课外学术科技作品竞赛 `一等奖`  
- *2015.06* 获得 第十三届“挑战杯”四川大学生课外学术科技作品竞赛 `一等奖` [[新闻]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  

<span class='anchor' id='-xshy'></span>

# 🏛️ 学术会议
- *2021.10*, 全国电磁无损检测技术研讨会 暨 中国机械工程学会无损检测分会电磁专业技术大会第十一届第四次全体会议, 陕西西安, 受邀报告
- *2019.09*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 江苏南京, 海报
- *2017.10*, 第六届中国国际管道会议 (CIPC 2017), 河北廊坊

<span class='anchor' id='-gzsx'></span>

# 💻 工作实习
- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉

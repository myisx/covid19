## 前言
以下代码仅供参考，CT影像目前还无法完全取代核酸检测，详情可查看文章:

> https://spectrum.ieee.org/the-human-os/biomedical/imaging/hospitals-deploy-ai-tools-detect-covid19-chest-scans

## 基于CT影像图实现的新型冠状病毒检测
| train| validate | test |
|--|--|--|
| 0.99 | 0.84 | 0.83 |

> 数据集 https://github.com/UCSD-AI4H/COVID-CT​
![实际结果](https://img-blog.csdnimg.cn/20200706175052124.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI3ODAyMTg=,size_16,color_FFFFFF,t_70#pic_center)
![训练过程](https://img-blog.csdnimg.cn/20200706175139319.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI3ODAyMTg=,size_16,color_FFFFFF,t_70)
![可视化](https://img-blog.csdnimg.cn/20200706175139355.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI3ODAyMTg=,size_16,color_FFFFFF,t_70)

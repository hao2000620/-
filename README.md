talking-head数据集

# 1 MEAD

MEAD: A Large-scale Audio-visual Dataset for Emotional Talking-face Generation

开放了48个演员的数据，每个演员有8个情绪，每个情绪三个强度，7个视角拍摄

<[uniBruce/Mead：MEAD：用于情感说话面孔生成的大规模视听数据集 [ECCV2020\] (github.com)](https://github.com/uniBruce/Mead)>

百度网盘下载

# 2 CREMA-D

48个男性，43个女性，20-74岁，多人种

演员发出12个句子，每个句子用6种情绪，4种情绪水平

git-lfs下载

<[CheyneyComputerScience/CREMA-D: Crowd Sourced Emotional Multimodal Actors Dataset (CREMA-D) (github.com)](https://github.com/CheyneyComputerScience/CREMA-D)>

# 3 VoxCeleb 

大型数据集，从油管截取，150000个句子，1251个人

<[VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)>



| 数据集名   | 时长       | 词汇量 | 图片尺寸  | 拍摄环境 | 数据类型                      | 拍摄时间 | 重点                             | 下载链接                                                     |
| ---------- | ---------- | ------ | --------- | -------- | ----------------------------- | -------- | -------------------------------- | ------------------------------------------------------------ |
| MEAD4      | 40h*48人   | /      | 1920*1080 | 室内     | 7个视角，以人脸为中心         | 2020     | 多视角，多情感                   | [MEAD](https://wywu.github.io/projects/MEAD/MEAD.html)       |
| HDTF       | 15.8h      | /      | 512*512   | 野外     | 以人脸为中心                  | 2021     | 野外高分辨率视频                 | [HDTF](https://github.com/MRzzm/HDTF)                        |
| CREMA-D    | /          | /      | /         | /        | 人脸为中心                    | 2017     | 多情感                           | [CREMA]([CheyneyComputerScience/CREMA-D：众包情感多模态参与者数据集（CREMA-D） (github.com)](https://github.com/CheyneyComputerScience/CREMA-D)) |
| VoxCeleb 2 | 2000h+     | /      | /         | 野外     | 公开的youtube视频             | 2018     | 超大规模，多人，多职业，多年龄段 | [VoxCeleb2]([沃克斯名人 (ox.ac.uk)](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)) |
| LSR2       | 2min*1000+ | <100   | /         | 野外     | 公开youtube视频，标出人脸区域 |          | 按预训练，训练，验证和测试分类   | [LSR2]([唇读句子 2 （LRS2） 数据集 (ox.ac.uk)](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html)) |
| LRW        | 111h       | 500    | 256*256   | 野外     | 1-2s的说话人脸视频            | 2016     | 每个视频对应一个英文单词         | [LRW]([Lip Reading in the Wild (LRW) dataset (ox.ac.uk)](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)) |
| GRID       | 28h        | 51     | 720*576   | 室内     | 3s的人脸中心视频              | 2006     | 每个视频对应6个英文单词          | [GRID]([视听伦巴第语音语料库 (shef.ac.uk)](https://spandh.dcs.shef.ac.uk//avlombard/)) |
| BIWI       | 19h*14人   | /      | /         | 室内     | 三维的人脸数据集              | 2010     | 三维人脸数据，按表情分类         | [BIWI]([ETHZ - Computer Vision Lab: Biwi 3D Audiovisual Corpus of Affective Communication - B3D(AC)^2](https://data.vision.ee.ethz.ch/cvl/datasets/b3dac2.en.html)) |
| VOCASET    | /          | /      | 5023个点  | 室内     | 3d人脸点云                    | 2019     | 高质量人脸扫描                   | [VOCASET](https://voca.is.tue.mpg.de/)                       |
| LSVSR      | 3900h      | 127k   | /         | 野外     | 人脸中心视频                  | 2018     | 最大的现存的数据库，youtube截取  | 没公开                                                       |


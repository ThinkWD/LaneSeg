PaddleSeg 2.5.0 以后的版本不再支持车道线检测模型的训练, 此仓库用于自定义数据集训练车道线检测模型。

### 使用方法：

1. 参考 [PaddleSeg/LaneSeg](https://github.com/PaddlePaddle/PaddleSeg/blob/release/2.5/contrib/LaneSeg/README_CN.md) 安装 paddle 环境

2. 安装本仓库：

   ```bash
   git clone https://github.com/ThinkWD/LaneSeg.git
   cd LaneSeg
   python3 -m pip install -e .
   ```
   
3.  参考 [PaddleSeg/LaneSeg](https://github.com/PaddlePaddle/PaddleSeg/blob/release/2.5/contrib/LaneSeg/README_CN.md) 准备训练数据

4.  参考本仓库 LaneSeg/data/bisenetV2.yml 中开头的注释部分开始训练

3.  本仓库改动了训练类别和分辨率，详见 git 提交记录


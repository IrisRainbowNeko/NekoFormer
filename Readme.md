# AuroraVision

AuroraVision是一个通用的二次元感知模型。可以对二次元图片进行标注，特征提取，相似度计算(图文，图图)等操作。
后续还会提供目标检测相关功能。

## 安装

```shell
pip install -r requirements.txt
```

## 使用

### 图像打标签
```shell
python infer.py --ckpt_path 模型权重路径 --tags_path tag汇总文件路径 --img 图片路径
```


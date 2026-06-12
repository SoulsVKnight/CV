# CV
交大视觉印象课程实验 - 图像检索与文字检测系统

项目简介
本项目为计算机视觉基础课程实验，实现两个核心功能：
1. 图像检索：基于ResNet101多尺度特征提取的校园地标以图搜图系统
2. 文字检测：基于PaddleOCR的校园图片文字检测与识别系统

实验环境
- Python 3.9+
- PyTorch 1.10+
- PaddlePaddle / PaddleOCR
- Gradio (演示界面)

## 快速开始

安装依赖
```bash
pip install -r requirements.txt

运行图像检索
python image_retrieval.py
启动演示界面
python gradio_retrieval_demo.py
运行文字检测
python text_detection.py

# FireDrone · CDS701 Group Project

本项目用 YOLO 定位图片中的火焰和烟雾，用 SVM 判断整张图片是否有火烟线索。[Releases 下载区](../../releases)提供数据、模型、源码和 Windows 程序。

| 下载文件 | 内容 |
|---|---|
| `01_Training_Data.zip` | 本项目实际使用的 FLAME 和 D-Fire 图片、标签、训练／验证／测试清单及来源说明 |
| `02_Models_and_Source.zip` | 原始与微调 YOLO、两代 SVM、MobileNetV3 特征提取器、训练和评估源码 |
| `03_FireDroneImage_Windows_x64.zip` | 含运行库、模型和示例图片的 FireDrone 图片识别程序 |

## 在 Windows 上打开程序

1. 下载并解压 `03_FireDroneImage_Windows_x64.zip`。
2. 打开解压后的 `FireDroneImage` 文件夹，双击 `FireDroneImage.exe`。请一起保留文件夹内的运行库和模型。
3. 点击“加载样例”或导入自己的图片，选择“优化检测”“原始检测”或“SVM 图像分类”，开始识别。

程序可在 Windows 64 位电脑上独立运行，无需安装 Python 或 VS Code。查看训练数据或复现实验时，再下载前两个压缩包并解压到同一个目录，按包内说明操作。

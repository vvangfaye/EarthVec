# EarthVec
[English](README.md) | 中文

EarthVec 是一个用于矢量化地球遥感影像的仓库，包含数据集、方法和部署工具。
目前项目处于积极开发阶段，EarthVec 初步支持部分选定的方法和数据集，并计划在未来逐步扩展其功能。

## 路线图
多边形矢量化方法和数据集是 EarthVec 的初步重点。以下功能计划在未来版本中实现：
- [x] 添加 [HoliTracer](https://www.github.com/vvangfaye/HoliTracer) 方法。
- [x] 支持大尺寸图像的训练和推理。
- [x] 支持带有坐标信息的栅格格式。
- [ ] 改进文档和使用流程（即将推出）。
- [ ] 添加 [Hisup](https://github.com/SarahwXU/HiSup)、[FFL](https://github.com/Lydorn/Polygonization-by-Frame-Field-Learning) 方法（即将推出）。
- [ ] 支持基于分块的数据集以及更多方法。
- [ ] 添加部署工具和脚本。

后续规划：线矢量化方法和数据集支持。

## 安装说明
```bash
git clone https://github.com/vvangfaye/EarthVec.git
cd EarthVec
pip install -e . # 以可编辑模式安装
```

## 贡献
该项目处于早期阶段，非常欢迎贡献！您可以提交问题、功能请求，或直接联系（📧 邮箱：wangfaye@whu.edu.cn）。

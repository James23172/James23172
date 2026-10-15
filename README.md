# 赵骁枭

华北电力大学（211） · 软件工程

正在整理课程项目和机器学习实践，关注软件研发与计算机视觉。

## 项目

### [钢材表面缺陷检测 · YOLOv8n / ONNX](https://github.com/James23172/steel-defect-detection)

基于NEU-DET六类缺陷数据，完成标注转换、固定数据划分、10/30轮训练预算对比、独立测试及ONNX本地CPU推理核验。

- 独立测试：**mAP50 72.8%，mAP50-95 42.7%**（270张、633个目标）。
- 六张验证图的PyTorch/ONNX输出一致性检查通过；保留裂纹漏检样例及实验局限。
- 技术：Python、PyTorch、Ultralytics YOLOv8、ONNX Runtime。

### [BlackBox · 多车协作地图探索仿真](https://github.com/James23172/blackbox)

基于Java、Redis黑板与RabbitMQ消息协作的课程项目，含路径规划、实时展示和回放。

- 技术：Java、Redis、RabbitMQ、Maven。
- 项目架构、运行指南和文档见仓库README。

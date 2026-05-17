# undergraduate-thesis
research on deep learning-based detection methods for ripe tomatoes for robotic harvesting

基于YOLOv8深度学习对成熟番茄的目标检测进行了三种算法改进：
1. 在backbone中加入MHSA模块
2. 在backbone中加入SPConv模块
3. 在backbone中同时加入MHSA模块和SPConv模块

训练后得到的结果：
三种算法相较于YOLOv8深度学习算法均有提升。其中MHSA-YOLOv8效果最好，SPConv—YOLOv8次之，而MS-YOLOv8的效果最差。
因此可以得出结论，MHSA模块和SPConv模块不能同时加入到主干网络中，两者相互矛盾。MHSA-YOLOv8可进行进一步的研究，应用到实际机器人识别采摘番茄中。

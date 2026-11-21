# 硬件工程

[下载 Robot-Audio.epro2](eda/Robot-Audio.epro2?raw=true)，在嘉立创 EDA 专业版中导入。文件中包含八通道音频板的原理图和六层 PCB。

看原理图时可以沿着两条路径读。采集端从 PDM 麦克风经 PCMD3180 转成 TDM 送入 STM32H743。播放端从 STM32H743 经 I²S 接到 TAS5828M，LM5125A-Q1 提供随音频包络变化的功放电源。

[板卡实拍和 PCB 布局](../README.md)

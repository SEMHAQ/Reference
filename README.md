# Reference - 学术论文文献仓库

按研究方向分类整理的论文集合。

## 目录结构

```
Reference/
├── 01_Object_Detection/          # 目标检测（YOLO系列、EfficientDet等）
├── 02_Traffic_Flow_Prediction/   # 交通流预测（时空图网络、Transformer等）
├── 03_Time_Series_Forecasting/   # 时间序列预测（TimeMixer、TimeXer等）
├── 04_Graph_Neural_Networks/     # 图神经网络（GCN、GAT等）
├── 05_Medical_Imaging/           # 医学图像与文物检测
├── 06_RLHF_RL_Finetuning/       # RLHF与强化学习微调（InstructGPT、DPO、GRPO等）
├── 07_NLP_and_Others/            # NLP、语音、姿态估计等其他方向
└── README.md
```

## 01_Object_Detection — 目标检测（39篇）

### YOLO 系列
| 论文 | 关键词 |
| --- | --- |
| Tan_EfficientDet_Scalable_and_Efficient_Object_Detection | EfficientDet, CVPR 2020 |
| TOE_YOLO_Tiny_Object_Detection_UAV_Imagery | 小目标检测, 无人机 |
| YOLO11_SRA_Safety_Helmet_Detection_Underground | 矿井安全帽检测 |
| YOLOv8_Chaotian_Pepper_Detection_Complex_Field | 朝天椒检测 |
| LightweightYOLOv5_ShuffleNetV2_Rice_Disease_Detection | 轻量化, 水稻病害 |
| Lightweight_Small_Object_Detection_BiFPN_Attention | BiFPN, 小目标 |
| YOSCA_Confidence_Adjustment_Object_Detection_Aerial | 置信度调整, 航拍 |
| CrackNex_Few_shot_Low_light_Crack_Segmentation_UAV | 小样本, 裂缝检测 |
| ST_CFI_Swin_Transformer_Plant_Disease_Identification | Swin Transformer, 植物病害 |
| DGBL_YOLOv8s_Enhanced_Object_Detection_UAV_Imagery | 无人机目标检测 |
| LSOD_YOLOv8_Lightweight_Cigarette_Detection | 轻量化, 香烟检测 |
| CPB_YOLOv8_Multi_Scale_Traffic_Sign_Detection | 交通标志检测 |
| DFA_YOLO_Electric_Power_Operation_Violation | 电力违规识别 |
| Enhanced_Lightweight_YOLOv8n_Complex_Scenes | 复杂场景轻量化 |
| YOLOv8_Attention_Student_Classroom_Behavior | 课堂行为识别 |
| Improved_YOLO11_Insulator_Defect_Detection_Power_Lines | 绝缘子缺陷检测 |
| YOLO11_FGA_Express_Package_Quality_Detection | 快递包裹质量检测 |
| YOLO_SSFA_Lightweight_Infrared_Small_Target | 红外小目标检测 |
| Multiscale_Grouped_Convolution_Protective_Equipment | 电力防护装备检测 |
| Lightweight_Floating_Object_Detection_Algorithm | 水面漂浮物检测 |
| Rain_Streak_Removal_Conditional_GAN | 去雨, GAN |

### 中文目标检测论文
| 论文 | 关键词 |
| --- | --- |
| 农田玉米叶片病害DBG-YOLO | 玉米病害检测 |
| BoT-YOLOX毫米波图像目标检测 | 毫米波成像 |
| CA-YOLOv8输送带大块煤检测 | 煤矿输送带 |
| Dark-YOLO低照度目标检测 | 低照度环境 |
| EfficientNetV2的PCB缺陷检测 | PCB缺陷 |
| MBE-YOLO轻量化井下行人检测 | 矿井行人检测 |
| SSD自然场景盲文识别 | 盲文识别 |
| Transformer+MobileNetv3铁路钢轨伤损检测 | 钢轨检测 |
| YOLOv8-WBG矿山钻头检测 | 矿山钻头 |
| YOLOv8边缘端轻量化多尺度目标检测 | 边缘计算 |
| 线性可变形卷积煤矿输送带异物检测 | 输送带异物 |
| 递归门控卷积煤块检测 | 煤块检测 |
| 改进YOLOv8n矿井火灾检测 | 矿井火灾 |
| 无人机视角YOLOv8s小目标检测 | 无人机小目标 |
| ICL-YOLOv11防眩板缺失检测 | 防眩板检测 |
| YOLOv11n桥梁水下结构病害检测 | 桥梁病害 |
| 改进YOLOv11n固定栓目标检测 | 固定栓检测 |
| 改进YOLOv11n路面裂缝坑洞检测 | 路面病害 |

## 02_Traffic_Flow_Prediction — 交通流预测（11篇）

| 论文 | 关键词 |
| --- | --- |
| Deep_Spatio_Temporal_Residual_Networks_Crowd_Flows | 城市人流预测 |
| MSTGCN_Multi_View_Spatial_Temporal_GCN | 多视角时空GCN |
| MultiSPANS_Spatial_Temporal_Transformer_Traffic | 结构熵优化Transformer |
| PDFormer_Propagation_Delay_Aware_Transformer | 传播延迟感知 |
| Spatio_Temporal_Transformer_GCN_Traffic_Flow | 时空Transformer+GCN |
| Traffic_Light_Control_with_Reinforcement_Learning | RL交通灯控制 |
| 基于双图卷积机制的数字孪生交通流预测 | 数字孪生 |
| 基于时空多头图注意力网络的交通流预测 | 图注意力网络 |
| 基于自适应时空多头图注意力网络的交通流量预测 | 自适应图注意力 |
| 面向路网交通流态势预测的图神经网络模型 | 路网态势预测 |
| 基于注意力卷积LSTM的城市出租车流量预测 | 出租车流量 |

## 03_Time_Series_Forecasting — 时间序列预测（3篇）

| 论文 | 关键词 |
| --- | --- |
| TimeMixer_Decomposable_Multiscale_Mixing | ICLR 2024, 多尺度混合 |
| TimeMixer++_General_Time_Series_Pattern_Machine | ICLR 2025, 通用时序模式机 |
| TimeXer_Transformers_Exogenous_Variables | 外生变量Transformer |

## 04_Graph_Neural_Networks — 图神经网络（5篇）

| 论文 | 关键词 |
| --- | --- |
| CGNet_Context_Guided_Network_Semantic_Segmentation | 语义分割 |
| DGCN_Dynamic_Graph_Convolutional_Networks | 动态图卷积 |
| An_improved_dynamic_Chebyshev_graph_convolution_network | 切比雪夫图卷积 |
| NIPS2016_Convolutional_Neural_Networks_on_Graphs | 谱滤波, NIPS 2016 |
| Wavelet_Convolution_Mining_Conveyor_Belt_Damage | 小波卷积, 传送带损伤 |

## 05_Medical_Imaging — 医学图像与文物检测（7篇）

| 论文 | 关键词 |
| --- | --- |
| DuAT_Dual_Aggregation_Transformer_Medical_Segmentation | 医学图像分割 |
| Paint_Loss_Detection_YOLO_Ancient_Murals | 古代壁画脱落检测 |
| DKR_YOLO_AI_Driven_Ancient_Mural_Recognition | 古代壁画AI识别 |
| DKR_YOLO_AI_Driven_Ancient_Mural_Recognition_CN | 中文版 |
| 基于多尺度卷积调制的医学图像分割 | 医学图像分割 |
| 基于残差双通道注意力U-Net古代壁画病害检测 | 壁画病害U-Net |
| 基于深度学习的岩石薄片矿物智能识别 | 岩石薄片矿物 |

## 06_RLHF_RL_Finetuning — RLHF与强化学习微调（10篇）

| # | 论文 | 关键词 |
| --- | --- | --- |
| 01 | InstructGPT (OpenAI, 2022) | RLHF 基石 |
| 02 | Constitutional AI (Anthropic, 2022) | AI 自我批评反馈 |
| 03 | DPO (2023) | 直接偏好优化 |
| 04 | SPO (2024) | 多维偏好序列对齐 |
| 05 | MO-GRPO (2025) | 多目标 GRPO |
| 06 | Multi-Objective RL for LLM (2025) | MORL 愿景 |
| 07 | DeepSeek-R1 (2025) | RLVR 可验证奖励 |
| 08 | Scaf-GRPO (ICLR 2026) | GRPO 改进 |
| 09 | RLVR-World (NeurIPS 2025) | RLVR 多模态 |
| 10 | RL Meets LLMs Survey (2025) | 综述 |

## 07_NLP_and_Others — NLP、语音、姿态估计等（15篇）

| 论文 | 关键词 |
| --- | --- |
| EMOLIPS_Reliable_Emotional_Speech_Lip_Reading | 情感语音唇读 |
| EMOLIPS_Reliable_Emotional_Speech_Lip_Reading_CN | 中文版 |
| JURIS基于理解增强型指令微调的司法命名实体识别 | 法律NLP |
| RASP-Net基于残差块和高相似传递注意力的图像去雪 | 图像去雪 |
| T3FRNet融合三重感知细粒度重构的换衣行人重识别 | 行人重识别 |
| 基于位姿图的激光SLAM点云优化 | SLAM |
| 具备可解释性的软件缺陷预测数据集构建 | 软件工程 |
| 基于低成本三维扫描仪的人脸深度图识别 | 人脸识别 |
| 基于动态时空子图卷积网络的电机轴承故障声纹识别 | 故障诊断 |
| 基于多码深度特征融合GAN的文本生成图像 | 文本到图像 |
| 基于改进低阶适应的开放词汇语音情感识别 | 语音情感识别 |
| 增强人体关键点特征的姿态估计算法 | 姿态估计 |
| 多尺度门控时空增强的唇语识别 | 唇语识别 |
| 川剧文化大数据可视分析 | 数据可视化 |
| 面向小样本学习的轻量化知识蒸馏 | 知识蒸馏 |

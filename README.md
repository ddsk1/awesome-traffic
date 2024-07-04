# awesome-traffic
- [LLM](#LLM)
    - [交通信号控制](#交通信号控制)
    - [交通模拟](#交通模拟)
    - [交通情况分类](#交通情况分类)
    - [场景理解](#场景理解)
    - [其他](#LLM其他)
- [其他](#其他)
    - [基础模型](#基础模型)
    - [模型评价](#模型评价)

## LLM

### 交通信号控制

- [LLMLight](https://github.com/usail-hkust/LLMTSCS) - 交通信号灯控制。 
- [LLM-Assisted-Light](https://github.com/Traffic-Alpha/LLM-Assisted-Light) - Leveraging Large Language Model Capabilities for Human-Mimetic Traffic Signal Control in Complex Urban Environments 交通信号灯控制
- [HARLA](https://github.com/Traffic-Alpha/TSC-HARLA) - 基于混合增广的强化学习和LLM的信号灯控制

### 交通模拟

- [LimSim](https://github.com/PJLab-ADG/LimSim) - Integrated traffic and autonomous driving simulators with (M)LLM support 交通模拟
- [交通模拟合集](https://github.com/zachytong/Awesome-Traffic-Simulation) -
- [ChatScene](https://github.com/javyduck/ChatScene) - ChatScene首先使用LLM生成文本描述的交通场景。这些场景描述随后被分解成多个子描述，具体说明车辆的行为和位置。代理然后将这些文本描述的子场景显著地转换为特定领域的语言，从而生成实际的代码，用于预测和控制模拟器中的行为，促进在CARLA模拟环境中创建多样且复杂的场景。
- [InstructDriver](https://github.com/bonbon-rj/instructdriver) - 通过明确的指令调优将LLM转化为运动规划器，使其行为与人类一致。基于人类逻辑和交通规则推导驾驶指令数据。然后采用一个可解释的InstructChain模块，进一步推理反映这些指令的最终规划。

### 交通情况分类

- [ET-BERT](https://github.com/linwhitehat/ET-BERT) - 交通情况分类 （2022）
- [NetGPT](https://arxiv.org/abs/2304.09513) - 没有代码，交通情况分类

### LLM其他

- [TransGPT · 致远](https://github.com/DUOMO/TransGPT) - 通用常识交通大模型,交通情况预测、智能咨询助手、公共交通服务、交通规划设计、交通安全教育、协助管理、交通事故报告和分析、自动驾驶辅助系统等功能
- [ST-LLM](https://github.com/ChenxiLiu-HNU/ST-LLM) - Spatial-Temporal Large Language Model for Traffic Prediction 交通流量预测
- [GPT-ST](https://github.com/hkuds/gpt-st) - 交通管理和出行规划的时空预测

### 场景理解

- [OmniDrive](https://github.com/nvlabs/omnidrive) - 3D感知，场景理解（数据集）
- [EM-VLM4AD](https://github.com/akshaygopalkr/em-vlm4ad) - 高效、轻量的多帧视觉语言模型，用于自动驾驶的视觉问答任务，适用于需要紧凑内存和快速推理时间的实时自动驾驶系统
- [DriveSim](https://github.com/sreeramsa/drivesim) - 评估了多种MLLMs作为驾驶世界模型的能力，重点关注它们在固定车载摄像头视角下对图像/帧序列的理解和解释（测试/Code to be released in this repository soon）
- [Drive Like A Human](https://github.com/PJLab-ADG/driveLikeAHuman) - 使用大型语言模型（LLM）以类人方式理解驾驶环境的潜力，并分析其在面对复杂场景时推理、解释和记忆的能力
- [PaddleSeg](https://github.com/PaddlePaddle/PaddleSeg) - 端到端完成从训练到部署的全流程图像分割应用
- [Reason3D](https://github.com/kuanchihhuang/reason3d) - VQA图像理解



## 其他

- [Datasets are not enough: Challenges in labeling network traffic](https://www.sciencedirect.com/science/article/abs/pii/S0167404822002048) - 交通网络数据准备（2022）
- [交通轨迹预测合集](https://github.com/Psychic-DL/Awesome-Traffic-Agent-Trajectory-Prediction) -

### 基础模型

- [视觉基础模型 CLIP](https://github.com/openai/CLIP) - 2019 通过让模型学会将图像与相
对应的文本描述配对，使模型具备理解开放图像与自由形式文本的能力。
- [视觉基础模型 Stable Diffusion](https://github.com/AUTOMATIC1111/stable-diffusion-webui) - 得到一张带噪声的图像，训练模型，能够预测出图像上所带有的噪声，从而实现去噪，以完全随机的高斯噪声作为起点，逐步去噪生成最终图像，在预测噪声时，额外接受文本输入，作为控制图像生成的条件
- [视觉基础模型 SAM](https://github.com/facebookresearch/segment-anything) - 通用的多任务基础分割模型，可以输入多种提示形式的交互分割任务，支持灵活的提示形式，并且可以实时输出分割掩码，以便进行交互使用
- [多任务语音大模型 Whisper](https://github.com/openai/whisper) - 能够执行多种 语音->文本 任务的多任务语音大模型
- [llama3](https://github.com/meta-llama/llama3) - 最常见开源LLM
- [Qwen (通义千问)](https://github.com/QwenLM/Qwen) - 最常见小型开源LLM

### 模型评价

- [Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness) - 提供了一个统一的框架，用于在大量不同的评估任务中测试生成语言模型。
- [opencompass](https://github.com/open-compass/opencompass) - 支持任意模型、100多种数据集和多种结果输出方案。特点是开源可复现、能力维度全面、模型支持丰富、高效的分布式评测、多样化的评测范式以及灵活化的拓展
- [Video-MME](https://github.com/BradyFU/Video-MME) - 多模态视频综合性能评测，多样性
- [Video-Bench](https://github.com/PKU-YuanGroup/Video-Bench) - 将视频语言模型的能力定义为视频理解、基于先验知识的问题解答和理解与决策，构建了十个任务，包括人群计数、总结、驾驶决策等。问题形式使用单项选择题形式
- [interPlan](https://github.com/mh0797/interplan) - 判断规划器在罕见情况下的泛化能力，包含了若干极端案例和具有挑战性的驾驶场景

- [opencompass](https://github.com/open-compass/opencompass) - 支持任意模型、100多种数据集和多种结果输出方案。特点是开源可复现、能力维度全面、模型支持丰富、高效的分布式评测、多样化的评测范式以及灵活化的拓展
- [Video-MME](https://github.com/BradyFU/Video-MME) - 多模态视频综合性能评测，多样性
- [Video-Bench](https://github.com/PKU-YuanGroup/Video-Bench) - 将视频语言模型的能力定义为视频理解、基于先验知识的问题解答和理解与决策，构建了十个任务，包括人群计数、总结、驾驶决策等。问题形式使用单项选择题形式



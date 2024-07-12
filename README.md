# awesome-traffic
- [LLM](#LLM)
    - [交通信号控制](#交通信号控制)
    - [交通模拟](#交通模拟)
    - [交通情况分类](#交通情况分类)
    - [场景理解](#场景理解)
    - [驾驶员行为分析](#驾驶员行为分析)
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
- [SMART](https://smart-motion.github.io/smart/) - 矢量化地图和agent轨迹的连续时间空间预测

### 交通情况分类

- [ET-BERT](https://github.com/linwhitehat/ET-BERT) - 交通情况分类 （2022）
- [NetGPT](https://arxiv.org/abs/2304.09513) - 没有代码，交通情况分类


### 场景理解

- [OmniDrive](https://github.com/nvlabs/omnidrive) - 3D感知，场景理解（数据集）
- [EM-VLM4AD](https://github.com/akshaygopalkr/em-vlm4ad) - 高效、轻量的多帧视觉语言模型，用于自动驾驶的视觉问答任务，适用于需要紧凑内存和快速推理时间的实时自动驾驶系统
- [DriveSim](https://github.com/sreeramsa/drivesim) - 评估了多种MLLMs作为驾驶世界模型的能力，重点关注它们在固定车载摄像头视角下对图像/帧序列的理解和解释（测试/Code to be released in this repository soon）
- [Drive Like A Human](https://github.com/PJLab-ADG/driveLikeAHuman) - 使用大型语言模型（LLM）以类人方式理解驾驶环境的潜力，并分析其在面对复杂场景时推理、解释和记忆的能力
- [PaddleSeg](https://github.com/PaddlePaddle/PaddleSeg) - 端到端完成从训练到部署的全流程图像分割应用
- [Reason3D](https://github.com/kuanchihhuang/reason3d) - VQA图像理解
- [Detect_VLM](https://github.com/kth-rpl/detect_vlm) - 极端场景下的VLMs检测交通参与者运动预测，涵盖了代理和场景两个层面（预计7月放出代码）
- [GPT4V-AD-Exploration](https://github.com/pjlab-adg/gpt4v-ad-exploration) - 对最新的最先进的VLM——GPT-4V(ision)在自动驾驶场景中的应用进行了详尽的评估。探讨了该模型在理解和推理驾驶场景、做出决策以及最终作为驾驶员角色的能力。
- [OccWorld](https://github.com/wzzheng/occworld) - 具备更强的表达能力、更高的获取效率和更广泛的适用性。通过学习基于重建的场景分词器和采用时空生成变换器，OccWorld能够生成后续的场景和自车标记，解码未来的占用和自车轨迹。
- [Language Conditioned Traffic Generation](https://github.com/Ariostgx/lctgen) - 接收自然语言输入，输出车辆的图像预测


### 驾驶员行为分析

- [GPT-Driver](https://github.com/pointscoder/gpt-driver) - 将OpenAI GPT-3.5模型转变为可靠运动规划器，将运动规划重新表述为一个语言建模问题
- [Driving-with-LLMs](https://github.com/wayveai/driving-with-llms) - 使用矢量标题语言数据将数值矢量模态与静态LLM表示对齐,引入了一种驾驶问答的评估指标
- [LeapAD](https://github.com/pjlab-adg/leapad) - Carla中的驾驶员决策模拟
- [DriveLM](https://github.com/OpenDriveLab/DriveLM) - 是第一个与现有端到端规划模型兼容的驾驶世界模型。通过视图分解的联合时空建模，可以在驾驶场景中生成高保真的多视图视频，并根据基于图像的奖励确定最佳轨迹。
- [DriveMLM](https://github.com/OpenGVLab/DriveMLM) - 多模态输入carla及现实情形决策（未放代码）
- [LMDrive](https://github.com/opendilab/LMDrive) - 闭环端到端carla驾驶模拟，通过token化的指令和多个视角的视角和雷达分别输入，得到速度方向控制
- [Agent-Driver](https://github.com/USC-GVL/Agent-Driver) - 加入认知和tools能力信息的判断，理解并运用（导航、识别、位置、预测）
- [Drive Anywhere](https://drive-anywhere.github.io/) - 寻找与驾驶相关的特征，将特征放置至合适位置，移动对应特征以预测驾驶行为（未放出代码）
- [Talk2BEV](https://github.com/llmbev/talk2bev) - 无需bev特定训练、视觉空间推理、意图预测、自然语言处理对齐
- [GPT-Driver](https://github.com/PointsCoder/GPT-Driver) - 使用gpt3.5描述坐标位置的语言生成行驶轨迹，经过提示生成位置，之后引导推理，微调后得出结果
- [DriveGPT4](https://tonyxuqaq.github.io/projects/DriveGPT4/) - 端到端预测车辆低级控制信号，可解释（未放代码）


### LLM其他

- [TransGPT · 致远](https://github.com/DUOMO/TransGPT) - 通用常识交通大模型,交通情况预测、智能咨询助手、公共交通服务、交通规划设计、交通安全教育、协助管理、交通事故报告和分析、自动驾驶辅助系统等功能
- [TrafficGPT](https://github.com/lijlansg/TrafficGPT) - 处理交通数据，辅助人类决策，交互式反馈和结果修正
- [ST-LLM](https://github.com/ChenxiLiu-HNU/ST-LLM) - Spatial-Temporal Large Language Model for Traffic Prediction 交通流量预测
- [GPT-ST](https://github.com/hkuds/gpt-st) - 交通管理和出行规划的时空预测


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
- [LaMPilot](https://github.com/PurdueDigitalTwin/LaMPilot) -  An Open Benchmark Dataset for Autonomous Driving with Language Model Programs（未放出）
- [Reason2Drive](https://github.com/fudan-zvg/Reason2Drive) - 视觉-文本测试集及方式，关注在复杂环境中的原因理解，原理是可解释性和步骤逻辑推理
- [Rank2Tell](https://arxiv.org/pdf/2309.06597) - 评判识别元素重要性分类数据集（未放出）



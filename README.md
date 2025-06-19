# 具身智能与多模态研究论文集

---

## 目录

* [Benchmark](#benchmark)
* [VLA & VLM](#vla--vlm)
* [触觉模态](#触觉模态)
* [世界模型](#世界模型)

---

## Benchmark

1. **EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents** (EmbodiedBench v2)  
   * **机构**：New York University (NYU)  
   * **总结**：面向视觉驱动嵌入式智能体的综合评测套件，统一测多模态 LLM 的执行与推理。

2. **VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks**  
   * **机构**：Fudan University — NLP Lab  
   * **总结**：专测语言条件下机器人长时程动作推理，可量化策略连续性与抗干扰。

3. **ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**  
   * **会议/出版**：CVPR 2020  
   * **机构**：University of Washington  
   * **总结**：首个将自然语言长指令映射到多步家务动作的基准；强调状态不可逆与组合操作。

4. **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning**  
   * **机构**：University of Washington  
   * **总结**：文字-视觉双视图环境，对齐动作空间以验证跨模态迁移。

5. **Alexa Arena: A User-Centric Interactive Platform for Embodied AI**  
   * **机构**：Amazon Lab126  
   * **总结**：面向用户的多房间交互平台，用语音+任务采集真实人机数据。

6. **Constrained Human-AI Cooperation: An Inclusive Embodied Social Intelligence Challenge (CHAIC)**  
   * **会议/出版**：NeurIPS 2024 (Datasets & Benchmarks)  
   * **机构**：MIT CSAIL  
   * **总结**：让 AI 与身体受限伙伴合作完成长程任务，考查社会感知与协同。

7. **Habitat 3.0: A Co-Habitat for Humans, Avatars and Robots**  
   * **机构**：Meta AI · Georgia Tech  
   * **总结**：引入虚拟人 avatar，与机器人和真人共处，高保真社交导航试验田。

8. **EgoPlan-Bench: Benchmarking Multimodal Large Language Models for Human-Level Planning**  
   * **机构**：Huazhong University of Science and Technology  
   * **总结**：第一视角规划基准，专剖多模态 LLM 的状态跟踪与长程依赖弱点。

9. **ET-Plan-Bench: Embodied Task-level Planning Benchmark Towards Spatial-Temporal Cognition with Foundation Models**  
   * **机构**：Huazhong University of Science and Technology  
   * **总结**：聚焦空间遮挡与时间因果推理，难度可调的任务级规划集合。

10. **EmbodiedEval: Evaluate Multimodal LLMs as Embodied Agents**  
    * **机构**：Tsinghua University  
    * **总结**：125 场景 / 328 任务，统一打分多模态大模型在导航到社交等五类任务。

11. **Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making**  
    * **会议/出版**：NeurIPS 2024  
    * **机构**：Chinese University of Hong Kong (CUHK)  
    * **总结**：给 LLM 设计决策界面并量化其具身决策质量，补齐“思考-行动”评测缺口。

---

## VLA & VLM

1. **3D-VLA: A 3D Vision-Language-Action Generative World Model**  
   * **会议/出版**：ICLR 2024  
   * **机构**：UMass Amherst  
   * **总结**：三维视觉-语言-动作世界模型，用 VLA 生成多步 3D 行为。

2. **DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping**  
   * **机构**：Tsinghua University  
   * **总结**：统一模仿+语言提示，实现灵巧手机械手任意抓取。

3. **Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding (FuSe)**  
   * **会议/出版**：ICML 2024  
   * **机构**：UC Berkeley  
   * **总结**：语言对齐微调跨机器人策略，一次训练通吃多任务。

4. **Gemini Robotics: Bringing AI into the Physical World**  
   * **机构**：Google DeepMind  
   * **总结**：把 Gemini 模型迁入现实机器人，展示端到端低时延控制。

5. **π 0.5: An Open-World Vision-Language-Action Model for Few-Shot Adaptation**  
   * **机构**：Physical Intelligence  
   * **总结**：开放世界 VLA，少样本适配任意新物体与场景。

6. **Robot-R1: Replacing Supervised Fine-Tuning with Reinforcement Learning for Enhanced Spatial Action Prediction**  
   * **机构**：KAIST · Yonsei University · UC Berkeley  
   * **总结**：用强化学习代替 SFT，显著提升 VLM 在具身推理的空间动作预测。

7. **3DLLM-Mem: Long-Term Spatial-Temporal Memory for Embodied 3D Large Language Model**  
   * **会议/出版**：CVPR 2025 (3D LLM/VLA Workshop Best Paper)  
   * **机构**：Tsinghua University  
   * **总结**：加入长期空间-时间记忆，解决 3D LLM 的“短时健忘”。

8. **OneTwoVLA: A Unified Vision-Language-Action Model with Adaptive Task-Model Switching**  
   * **机构**：Peking University  
   * **总结**：自适应推理的统一 VLA，任务-模型双层切换提高推理效率。

9. **From Strangers to Assistants: Fast Desire Alignment for Embodied Agent-User Adaptation**  
   * **机构**：Renmin University of China  
   * **总结**：分钟级意图对齐框架，让机器人迅速变成贴心助理。

---

## 触觉模态

1. **Touch-Vision-Language Dataset: A Large-Scale Benchmark for Visuo-Tactile-Language Alignment**  
   * **会议/出版**：ICML 2024  
   * **机构**：UC Berkeley  
   * **总结**：首个大规模视触语对齐数据集，打通 TVL 三域表征。

2. **UniTouch: A Unified Multi-Sensor Tactile Representation Learning Framework**  
   * **会议/出版**：CVPR 2024  
   * **机构**：Yale University  
   * **总结**：统一多源触觉表示，可迁移至动态交互。

3. **AnyTouch: Learning Unified Static-Dynamic Representation across Multiple Visuo-Tactile Sensors**  
   * **会议/出版**：ICLR 2025  
   * **机构**：Renmin University of China  
   * **总结**：跨视-触传感器的统一静/动态编码，支持下游分类与控制。

---

## 世界模型

1. **Navigation World Models: A Controllable Video Generation Model for Planning Navigation Trajectories**  
   * **会议/出版**：CVPR 2025 Oral  
   * **机构**：Meta AI  
   * **总结**：预训练可控导航世界模型，一次生成整条轨迹。

2. **Text2World: Benchmarking Large Language Models for Symbolic World Model Generation**  
   * **会议/出版**：ACL 2024  
   * **机构**：MIT  
   * **总结**：基于 LLM 的符号世界生成基准，评测文本-场景一致性。

3. **Cosmos-Transfer1: Conditional World Generation with Adaptive Multimodal Control**  
   * **机构**：NVIDIA  
   * **总结**：条件化多模态世界生成框架，可控信号生成丰富场景。

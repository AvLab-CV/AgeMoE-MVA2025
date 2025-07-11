# AgeMoE-MVA2025
![Linux](https://img.shields.io/badge/System-Linux-green.svg?style=plastic)
![Python 3.8](https://img.shields.io/badge/python-3.8-green.svg?style=plastic)
![CUDA 11.3](https://img.shields.io/badge/cuda-11.3-green.svg?style=plastic)
![PyTorch 1.12](https://img.shields.io/badge/pytorch-1.12-green.svg?style=plastic)
![Janus Pro (VLM)](https://img.shields.io/badge/Janus_Pro-pretrained-blue.svg?style=plastic)
![MiVOLO](https://img.shields.io/badge/MiVOLO-pretrained-blue.svg?style=plastic)

![image](https://github.com/AvLab-CV/AgeMoE-MVA2025/blob/d6204caf9540dec4f10629d4d1c38d49c915c3e9/Figure3.jpg)


**Abstract:** Age estimation models are widely used in applications such as cross-age recognition, facial age transformation, and content screening. However, the evaluation of existing models still relies on outdated baselines such as DEX and Face++, which are often inaccurate and unstable—particularly for younger age groups—thus limiting their practical applicability. In addition, current benchmarks mainly emphasize overall mean absolute error (MAE), while overlooking prediction stability and fairness across age groups. To address these limitations, we propose a lightweight Mixture of Experts (MoE) framework that dynamically combines vision-language models (VLMs), such as Janus Pro, with structure-oriented visual experts, including CNN-based (e.g., VGG16, ResNet50) and Transformer-based models (e.g., MiVOLO). Our framework improves age prediction stability through expert-specific bias correction and supports plug-and-play integration without retraining, enabling efficient fusion at minimal cost. Experiments on the AgeDB and Cross-Age Face (CAF) datasets demonstrate superior performance compared to state-of-the-art models, validating the effectiveness of our framework in age estimation and its potential for broader multi-modal applications.

# Checkpoints & Inference Code
Pretrained checkpoints and inference scripts will be released soon. <br>
We are currently finalizing model packaging and reproducibility checks to ensure a smooth user experience. <br>
⏳Coming soon

# Credits
**Janus Pro** (Vision-Language Model) <br>
Code Repository: [https://github.com/Alpha-VLLM/Janus](https://github.com/deepseek-ai/Janus?tab=readme-ov-file) <br>
Code License: MIT License <br>
Model Weights License: DeepSeek Model License <br>
Copyright © 2023 Alpha-VLLM <br>
Note: Janus Pro weights are subject to usage restrictions under the DeepSeek Model License. Please review the license terms before use in commercial or derivative works. <br>

**MiVOLO** (Transformer-based Age Estimator) <br>
Repository: [https://github.com/youngwanLEE/MiVOLO](https://github.com/WildChlamydia/MiVOLO) <br>
License: MIT License <br>
Copyright © 2022 Youngwan Lee <br>

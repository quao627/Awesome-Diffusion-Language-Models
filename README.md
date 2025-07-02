[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![](https://img.shields.io/github/stars/quao627/Awesome-Diffusion-Language-Models)](https://github.com/quao627/Awesome-Diffusion-Language-Models)
[![](https://img.shields.io/github/license/quao627/Awesome-Diffusion-Language-Models)](https://github.com/quao627/Awesome-Diffusion-Language-Models/blob/main/LICENSE)
[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fquao627%2FAwesome-Diffusion-Language-Models&label=visitors&countColor=%2337d67a&style=flat&labelStyle=none)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fquao627%2FAwesome-Diffusion-Language-Models)

A curated list of resources, papers, code, and tutorials for Diffusion Language Models (DLMs), covering research progress, implementations, benchmarks, and applications.

## Contents
- [Resources](#resources)
  - [Blog Posts](#blog-posts)
  - [Tutorials](#tutorials)
- [Models](#models)
  - [Closed Source](#closed-source)
  - [Open Source](#open-source)
- [Papers](#papers)
  - [Survey](#survey)
  - [Foundational Works](#foundational-works)
  - [Discrete-Time Diffusion Language Models](#discrete-time-diffusion-language-models)
  - [Continuous-Time Diffusion Language Models](#continuous-time-diffusion-language-models)
  - [Reasoning](#reasoning)
  - [Multimodal](#multimodal)
  - [Hybrid Approaches](#hybrid-approaches)
  - [Efficiency](#efficiency)
  - [Applications](#applications)
    - [Code Generation](#code-generation)

 
# Resources
## Blog Posts
**What are Diffusion Language Models?** \
*Xiaochen Zhu* \
[[Website](https://spacehunterinf.github.io/blog/2025/diffusion-language-models/)] \
14 April 2025

**Strengths and limitations of diffusion language models** \
*sean goedecke* \
[[Website](https://www.seangoedecke.com/limitations-of-text-diffusion-models/)] \
22 May 2025

## Tutorials

# Models
## Closed Source
**Mercury**
[[Website](https://www.inceptionlabs.ai/introducing-mercury)] [[Technical Report](https://www.inceptionlabs.ai/introducing-mercury)]

**Gemini Diffusion**
[[Website](https://deepmind.google/models/gemini-diffusion/)] [[Blog](https://blog.google/technology/google-deepmind/gemini-diffusion/)]

## Open Source
**LLaDA-8B**
[[Website](https://ml-gsai.github.io/LLaDA-demo/)] [[Model](https://huggingface.co/GSAI-ML)] [[Code](https://github.com/ML-GSAI/LLaDA)]

**Dream-7B**
[[Website](https://hkunlp.github.io/blog/2025/dream/)] [[Model](https://huggingface.co/Dream-org)] [[Code](https://github.com/HKUNLP/Dream)]

# Papers
## Survey
**Discrete Diffusion in Large Language and Multimodal Models: A Survey** \
*Runpeng Yu, Qi Li, Xinchao Wang* \
Arxiv 2025 (Jun 16, 2025). [[Paper](https://arxiv.org/abs/2506.13759)]

## Foundational Works
**Deep Unsupervised Learning using Nonequilibrium Thermodynamics** \
*Jascha Sohl-Dickstein, Eric Weiss, Niru Maheswaranathan, Surya Ganguli* \
ICML 2015. [[Paper](https://proceedings.mlr.press/v37/sohl-dickstein15.html)] [[Code](https://github.com/Sohl-Dickstein/Diffusion-Probabilistic-Models)]

**Denoising Diffusion Probabilistic Models** \
*Jonathan Ho, Ajay N. Jain, Pieter Abbeel* \
NeurIPS 2020. [[Paper](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)] [[Code(official)](https://github.com/hojonathanho/diffusion)] [[Code(Pytorch)](https://github.com/lucidrains/denoising-diffusion-pytorch)]

**Structured Denoising Diffusion Models in Discrete State-Spaces** \
*Jacob Austin, Daniel D. Johnson, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* \
NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/958c530554f78bcd8e97125b70e6973d-Abstract.html)] [[Code](https://github.com/google-research/google-research/tree/master/d3pm)]


## Discrete-Time Diffusion Language Models

**Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions** \
*Emiel Hoogeboom, Didrik Nielsen, Priyank Jaini, Patrick Forré, Max Welling* \
NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/67d96d458abdef21792e6d8e590244e7-Abstract.html)] [[Code](https://github.com/didriknielsen/argmax_flows)]

**Scaling Diffusion Language Models via Adaptation from Autoregressive Models** \
*Shansan Gong, Shivam Agarwal, Yizhe Zhang, Jiacheng Ye, Lin Zheng, Mukai Li, Chenxin An, Peilin Zhao, Wei Bi, Jiawei Han, Hao Peng, Lingpeng Kong* \
ICLR 2025. [[Paper](https://arxiv.org/abs/2410.17891)] [[Code](https://github.com/HKUNLP/DiffuLLaMA)]

**Large Language Diffusion Models** \
*Shen Nie, Fengqi Zhu, Zebin You, Xiaolu Zhang, Jingyang Ou, Jun Hu, Jun Zhou, Yankai Lin, Ji-Rong Wen, Chongxuan Li* \
Arxiv 2025. [[Paper](https://arxiv.org/abs/2502.09992)] [[Code](https://github.com/ML-GSAI/LLaDA)] [[Model](https://huggingface.co/GSAI-ML)]

**LLaDA 1.5: Variance-Reduced Preference Optimization for Large Language Diffusion Models** \
*Fengqi Zhu, Rongzhen Wang, Shen Nie, Xiaolu Zhang, Chunwei Wu, Jun Hu, Jun Zhou, Jianfei Chen, Yankai Lin, Ji-Rong Wen, Chongxuan Li* \
Arxiv 2025 (May 25, 2025). [[Paper](https://arxiv.org/abs/2505.19223)] [[Code](https://github.com/ML-GSAI/LLaDA-1.5)]

**LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning** \
*Zebin You, Shen Nie, Xiaolu Zhang, Jun Hu, Jun Zhou, Zhiwu Lu, Ji-Rong Wen, Chongxuan Li* \
Arxiv 2025 (May 22, 2025). [[Paper](https://arxiv.org/abs/2505.16933)] [[Code](https://github.com/ML-GSAI/LLaDA-V)]

## Continuous-Time Diffusion Language Models

**A Continuous Time Framework for Discrete Denoising Models** \
*Andrew Campbell, Joe Benton, Valentin De Bortoli, Thomas Rainforth, George Deligiannidis, Arnaud Doucet* \
NeurIPS 2022. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b5b528767aa35f5b1a60fe0aaeca0563-Abstract-Conference.html)] [[Code](https://github.com/andrew-cr/tauLDR)]

**Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution** \
*Aaron Lou, Chenlin Meng, Stefano Ermon* \
ICML 2024. [[Paper](https://arxiv.org/abs/2310.16834)] [[Code](https://github.com/louaaron/Score-Entropy-Discrete-Diffusion)] [[Model](https://huggingface.co/louaaron)]

## Reasoning

**d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning** \
*Siyan Zhao, Devaansh Gupta, Qinqing Zheng, Aditya Grover* \
Arxiv 2025. [[Paper](https://arxiv.org/abs/2504.12216)] [[Code](https://github.com/dllm-reasoning/d1)]

**Diffusion of Thoughts: Chain-of-Thought Reasoning in Diffusion Language Models** \
*Jiacheng Ye, Shansan Gong, Liheng Chen, Lin Zheng, Jiahui Gao, Han Shi, Chuan Wu, Xin Jiang, Zhenguo Li, Wei Bi, Lingpeng Kong* \
NeurIPS 2024. [[Paper](https://arxiv.org/abs/2402.07754)] [[Code](https://github.com/HKUNLP/diffusion-of-thoughts)]

**Reinforcing the Diffusion Chain of Lateral Thought with Diffusion Language Models** \
*Zemin Huang*, *Zhiyang Chen*, *Zijun Wang*, *Tiancheng Li*, *Guo-Jun Qi* \
Arxiv 2025 (May 21, 2025). [[Paper](https://arxiv.org/abs/2505.10446)]

## Multimodal

**MMaDA: Multimodal Large Diffusion Language Models** \
*Ling Yang, Ye Tian, Bowen Li, Xinchen Zhang, Ke Shen, Yunhai Tong, Mengdi Wang* \
Arxiv 2025 (May 21, 2025). [[Paper](https://arxiv.org/abs/2505.15809)] [[Code](https://github.com/Gen-Verse/MMaDA)]

**LaViDa: A Large Diffusion Language Model for Multimodal Understanding** \
*Shufan Li, Konstantinos Kallidromitis, Hritik Bansal, Akash Gokul, Yusuke Kato, Kazuki Kozuka, Jason Kuen, Zhe Lin, Kai-Wei Chang, Aditya Grover* \
Arxiv 2025 (May 23, 2025). [[Paper](https://arxiv.org/abs/2505.16839)] [[Code](https://github.com/jacklishufan/LaViDa)]

## Hybrid Approaches

**Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models** \
*Marianne Arriola, Aaron Gokaslan, Justin T. Chiu, Zhihan Yang, Zhixuan Qi, Jiaqi Han, Subham Sekhar Sahoo, Volodymyr Kuleshov* \
ICLR 2025. [[Paper](https://arxiv.org/abs/2503.09573)] [[Code](https://github.com/kuleshov-group/bd3lms)] [[Model](https://huggingface.co/collections/kuleshov-group/bd3-lms-67be95f81b96b15fec50d53f)]

## Efficiency
**Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding** \
*Chengyue Wu, Hao Zhang, Shuchen Xue, Zhijian Liu, Shizhe Diao, Ligeng Zhu, Ping Luo, Song Han, Enze Xie* \
Arxiv 2025. [[Paper](https://arxiv.org/abs/2505.22618)] [[Code](https://github.com/NVlabs/Fast-dLLM)]

## Applications
### Code Generation
**DiffuCoder: Understanding and Improving Masked Diffusion Models for Code Generation** \
*Shansan Gong, Ruixiang Zhang, Huangjie Zheng, Jiatao Gu, Navdeep Jaitly, Lingpeng Kong, Yizhe Zhang* \
Arxiv 2025. [[Paper](https://arxiv.org/abs/2506.20639)] [[Code](https://github.com/apple/ml-diffucoder)]

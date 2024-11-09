# awesome-video-understanding [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources (paper, code, data) on video understanding research. **(sorted by release date)**

🚀 This repo will be continuously updated. <br> ⭐️ Please Star it if you find it helpful! <br> 🤝 Feel free to submit a PR or open an issue with suggestions or improvements.

---
**Table of Contents**
- [Models](#models)
  - [Large Multimodal Models](#large-multimodal-models)
  - [Agents](#agents)
- [Benchmarks](#benchmarks)
  - [General QA](#general-qa)
  - [Caption](#caption)
  - [Temporal-Grounding](#temporal-grounding)
  - [Hallucination](#hallucination)
- [Datasets](#datasets)
  - [Pre-Training](#pre-training)
  - [Instruction-Tuning](#instruction-tuning)
  - [RLHF](#rlhf)
---

## Models
### Large Multimodal Models
| Name | Paper | Task | Note |
|:---|:---|:---|:---|
| **Aria** <br> @Rhymes AI | [Aria: An Open Multimodal Native Mixture-of-Experts Model](https://arxiv.org/abs/2410.05993) <br>  24.10.08 / ArXiv / [Project Page](https://github.com/rhymes-ai/Aria) | General QA / Caption | / |
| **LLaVA-Video** <br> @ByteDance | [Video Instruction Tuning with Synthetic Data](https://arxiv.org/abs/2410.02713) <br> 24.10.03 / ArXiv / [Project Page](https://llava-vl.github.io/blog/2024-09-30-llava-video/) | General QA / Caption | / |
| **Oryx** <br> @THU | [Oryx MLLM: On-Demand Spatial-Temporal Understanding at Arbitrary Resolution](https://arxiv.org/abs/2409.12961v2) <br> 24.09.19 / ArXiv / [Project Page](https://oryx-mllm.github.io/) | General QA / Caption | / |
| **Qwen2-VL** <br> @Qwen | [Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution](https://arxiv.org/abs/2409.12191) <br> 24..09.18 / ArXiv / [Project Page](https://github.com/QwenLM/Qwen2-VL) | General QA / Caption | / |
| **LLaVA-OneVision** <br> @ByteDance | [LLaVA-OneVision: Easy Visual Task Transfer](https://arxiv.org/abs/2408.03326) <br> 24.08.06 / ArXiv / [Project Page](https://llava-vl.github.io/blog/2024-08-05-llava-onevision/) | General QA / Caption | / |
| **InternVL-2** <br> @OpenGVLab | [InternVL2: Better than the Best—Expanding Performance Boundaries of Open-Source Multimodal Models with the Progressive Scaling Strategy](https://internvl.github.io/blog/2024-07-02-InternVL-2.0/) <br> 24.07.04 / Blog / [Project Page](https://github.com/OpenGVLab/InternVL) | General QA / Caption | / |
| **VideoLLaMA** <br> @Alibaba | [VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs](https://arxiv.org/abs/2406.07476) <br> 24.06.11 / ArXiv / [Project Page](https://github.com/DAMO-NLP-SG/VideoLLaMA2?tab=readme-ov-file) | General QA / Caption | / |
| **VILA** <br> @Nvidia | [VILA: On Pre-training for Visual Language Models](https://arxiv.org/abs/2312.07533) <br> 23.12.12 / CVPR'24 / [Project Page](https://github.com/NVlabs/VILA?tab=readme-ov-file) | General QA / Caption | / |
### Agents
| Name | Paper | Task | Note |
|:---|:---|:---|:---|
| **TraveLER**<br>@Berkeley | [TraveLER: A Modular Multi-LMM Agent Framework for Video Question-Answering](https://arxiv.org/abs/2404.01476) <br> 24.04.01 / EMNLP'24 / [Project Page](https://github.com/traveler-framework/TraveLER) | QA | / |
| **VideoAgent**<br>@BIGAI | [VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding](https://arxiv.org/abs/2403.11481) <br> 24.03.18 / ECCV'24 / [Project Page](https://videoagent.github.io/) | QA <br> Temporal-Grounding | / |
| **VideoAgent**<br>@Stanford | [VideoAgent: Long-form Video Understanding with Large Language Model as Agent](https://arxiv.org/abs/2403.10517) <br> 24.03.15 / ECCV'24 / [Project Page](https://wxh1996.github.io/VideoAgent-Website/) | QA | / |

## Benchmarks
### General QA
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **HourVideo** <br> @Stanford | [HourVideo: 1-Hour Video-Language Understanding](https://arxiv.org/abs/2411.04998) <br> 24.11.07 / NIPS'24 D&B / [Project Page](https://hourvideo.stanford.edu/) | LLM+Human Annotated / 500 videos / 20~120m / 13K QAs | Long / Egocentric |
| **TemporalBench** <br> @WUM | [TemporalBench: Benchmarking Fine-grained Temporal Understanding for Multimodal Video Models](https://arxiv.org/abs/2410.10818) <br> 24.10.14 / ArXiv / [Project Page](https://temporalbench.github.io/#leaderboard) | Human+LLM Annotated / 2K videos / 0~20m / 10K QAs | / |
| **LongVideoBench** <br> @NTU | [LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding](https://arxiv.org/abs/2407.15754) <br> 24.07.22 / NIPS'24 D&B / [Project Page](https://longvideobench.github.io/) | **Humman Annotated** / 3.8K videos / 0~1h / 6.7K QAs | / |
| **LVBench** <br> @Zhipu | [LVBench: An Extreme Long Video Understanding Benchmark](https://arxiv.org/abs/2406.08035) <br> 24.06.12 / ArXiv / [Project Page](https://lvbench.github.io/) | **Humman Annotated** / 500 videos / avg. 1h / 1.5k QAs | / |
| **VideoMME** <br> @VideoMME-Team| [Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis](https://arxiv.org/abs/2405.21075) <br> 24.05.31 / ArXiv / [Project Page](https://video-mme.github.io/) | **Humman Annotated** / 900 videos / 0~60m / 2.7K QAs| / |
| **TempCompass** <br> @PKU | [TempCompass: Do Video LLMs Really Understand Videos?](https://arxiv.org/abs/2403.00476) <br> 24.03.01 / ACL'24 Findings / [Project Page](https://llyx97.github.io/tempcompass/) | ChatGPT+Human Annotated / 410 videos / 0~35s / 7.5K QAs | / |
### Caption
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **VDC** <br> @UW | [AuroraCap: Efficient, Performant Video Detailed Captioning and a New Benchmark](https://arxiv.org/abs/2410.03051) <br> 24.10.04 / ArXiv / [Project Page](https://rese1f.github.io/aurora-web/) | GPT-4o Annotated / 1027 videos / 0~60s / 1027 captions | Evaluate Captioning using QAs |
### Temporal-Grounding
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **Charades-STA** <br> @USC| [TALL: Temporal Activity Localization via Language Query](https://arxiv.org/abs/1705.02101) <br> 17.05.05 / ICCV'17 / [Project Page](https://github.com/jiyanggao/TALL) | Rule+Human Annotated / 4233 clip-sentence pairs | / |
| **ActivityNet Captions** <br> @Stanford| [Dense-Captioning Events in Videos](https://arxiv.org/abs/1705.00754) <br> 17.05.05 / ICCV'17 / [Project Page](https://cs.stanford.edu/people/ranjaykrishna/densevid/) | Human Annotated / 20K videos / 0~270s | / |
| **YouCook2** <br> @Google Brain | [Towards Automatic Learning of Procedures from Web Instructional Videos]() <br> 17.03.28 / AAAI'18 / [Project Page](http://youcook2.eecs.umich.edu/) | **Human Annotated** / 2K videos / 0~800s / avg. 7.7 segments per video | / |
### Hallucination
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **VideoHallucer** <br> @BIGAI | [VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models](https://arxiv.org/abs/2406.16338) / 24.06.24 / ArXiv / [Project Page](https://videohallucer.github.io/) | Rule+Human Annotated / 948 videos / 7~187s / 1.8K QAs | / |

## Datasets
### Pre-Training
| Name | Paper | Data | Metadata |
|:---|:---|:---|:---|
|**ShareGPTVideo** <br> @CMU| [Direct Preference Optimization of Video Large Multimodal Models from Language Model Reward](https://arxiv.org/abs/2404.01258) <br>  24.04.01 / ArXiv / [Project Page](https://github.com/RifleZhang/LLaVA-Hound-DPO?tab=readme-ov-file) | [Dataset](https://huggingface.co/datasets/ShareGPTVideo/train_video_and_instruction) | GPT-4V Annotated (10 frames) / 900K Videos / 900K Captions |
### Instruction-Tuning
| Name | Paper | Data | Metadata |
|:---|:---|:---|:---|
| **LLaVA-Video-178k** <br> @ByteDance |  [Video Instruction Tuning with Synthetic Data](https://arxiv.org/abs/2410.02713)<br>24.10.03 / ArXiv / [Project Page](https://llava-vl.github.io/blog/2024-09-30-llava-video/)| [Dataset](https://huggingface.co/datasets/lmms-lab/LLaVA-Video-178K) | GPT-4o Annotated **(1 FPS)** / 178K videos / 0~3m / 178K Captions / 1.1M QAs |
|**ShareGPTVideo** <br> @CMU| [Direct Preference Optimization of Video Large Multimodal Models from Language Model Reward](https://arxiv.org/abs/2404.01258) <br>  24.04.01 / ArXiv / [Project Page](https://github.com/RifleZhang/LLaVA-Hound-DPO?tab=readme-ov-file) | [Dataset](https://huggingface.co/datasets/ShareGPTVideo/train_video_and_instruction) | GPT-4V Annotated (10 frames) / 900K Videos / 900K Captions / 900K QAs |
### RLHF
| Name | Paper | Data | Metadata |
|:---|:---|:---|:---|
| **ShareGPTVideo** <br> @CMU | [Direct Preference Optimization of Video Large Multimodal Models from Language Model Reward](https://arxiv.org/abs/2404.01258) <br>  24.04.01 / ArXiv / [Project Page](https://github.com/RifleZhang/LLaVA-Hound-DPO?tab=readme-ov-file) | [Dataset](https://huggingface.co/datasets/ShareGPTVideo/train_video_and_instruction/tree/main/video_instruction/train/dpo) | ChatGPT Annotated / 17K videos / 17K preference data |

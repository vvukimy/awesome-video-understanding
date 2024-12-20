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
  - [Action Recognition](#action-recognition)
  - [Hallucination](#hallucination)
- [Datasets](#datasets)
  - [Pre-Training](#pre-training)
  - [Instruction-Tuning](#instruction-tuning)
  - [RLHF](#rlhf)
- [Research Topics](#research-topics)
  - [Visual Encoding](#visual-encoding)
  - [Visual Token Reduction](#visual-token-reduction)
  - [Streaming](#streaming)
---

## Models
### Large Multimodal Models
| Name | Paper | Task | Note |
|:---|:---|:---|:---|
| **Apollo** <br> @Meta | [Apollo: An Exploration of Video Understanding in Large Multimodal Models](https://arxiv.org/abs/2412.10360) <br> 24.12.13 / ArXiv / [Project Page](https://apollo-lmms.github.io/) | General QA | / |
| **InternVL2.5** <br> @Nvidia | [Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling](https://arxiv.org/abs/2412.05271) <br> 24.12.06 / ArXiv / [Project Page](https://internvl.github.io/blog/2024-12-05-InternVL-2.5/) | General QA | / |
| **NVILA** <br> @Nvidia | [NVILA: Efficient Frontier Visual Language Models](https://arxiv.org/abs/2412.04468) <br> 24.12.05 / ArXiv / [Project Page](https://github.com/NVlabs/VILA) | General QA | / |
| **LongVU** <br> @Meta | [LongVU: Spatiotemporal Adaptive Compression for Long Video-Language Understanding](https://arxiv.org/abs/2410.17434) <br> 24.10.22 / ArXiv / [Project Page](https://vision-cair.github.io/LongVU/) | General QA | / |
| **Aria** <br> @Rhymes AI | [Aria: An Open Multimodal Native Mixture-of-Experts Model](https://arxiv.org/abs/2410.05993) <br>  24.10.08 / ArXiv / [Project Page](https://github.com/rhymes-ai/Aria) | General QA / Caption | / |
| **LLaVA-Video** <br> @ByteDance | [Video Instruction Tuning with Synthetic Data](https://arxiv.org/abs/2410.02713) <br> 24.10.03 / ArXiv / [Project Page](https://llava-vl.github.io/blog/2024-09-30-llava-video/) | General QA / Caption | / |
| **Oryx** <br> @THU | [Oryx MLLM: On-Demand Spatial-Temporal Understanding at Arbitrary Resolution](https://arxiv.org/abs/2409.12961v2) <br> 24.09.19 / ArXiv / [Project Page](https://oryx-mllm.github.io/) | General QA / Caption | / |
| **Qwen2-VL** <br> @Qwen | [Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution](https://arxiv.org/abs/2409.12191) <br> 24..09.18 / ArXiv / [Project Page](https://github.com/QwenLM/Qwen2-VL) | General QA / Caption | / |
| **LLaVA-OneVision** <br> @ByteDance | [LLaVA-OneVision: Easy Visual Task Transfer](https://arxiv.org/abs/2408.03326) <br> 24.08.06 / ArXiv / [Project Page](https://llava-vl.github.io/blog/2024-08-05-llava-onevision/) | General QA / Caption | / |
| **InternVL-2** <br> @OpenGVLab | [InternVL2: Better than the Best—Expanding Performance Boundaries of Open-Source Multimodal Models with the Progressive Scaling Strategy](https://internvl.github.io/blog/2024-07-02-InternVL-2.0/) <br> 24.07.04 / Blog / [Project Page](https://github.com/OpenGVLab/InternVL) | General QA / Caption | / |
| **VideoLLaMA** <br> @Alibaba | [VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs](https://arxiv.org/abs/2406.07476) <br> 24.06.11 / ArXiv / [Project Page](https://github.com/DAMO-NLP-SG/VideoLLaMA2?tab=readme-ov-file) | General QA / Caption | / |
| **LWM** <br> @Berkeley | [World Model on Million-Length Video And Language With Blockwise RingAttention]() <br> 24.02.13 / ArXiv / [Project Page](https://largeworldmodel.github.io/lwm/) | General QA | / |
| **VILA** <br> @Nvidia | [VILA: On Pre-training for Visual Language Models](https://arxiv.org/abs/2312.07533) <br> 23.12.12 / CVPR'24 / [Project Page](https://github.com/NVlabs/VILA?tab=readme-ov-file) | General QA / Caption | / |
### Agents
| Name | Paper | Task | Note |
|:---|:---|:---|:---|
| **TraveLER**<br>@Berkeley | [TraveLER: A Modular Multi-LMM Agent Framework for Video Question-Answering](https://arxiv.org/abs/2404.01476) <br> 24.04.01 / EMNLP'24 / [Project Page](https://github.com/traveler-framework/TraveLER) | QA | / |
| **VideoAgent**<br>@BIGAI | [VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding](https://arxiv.org/abs/2403.11481) <br> 24.03.18 / ECCV'24 / [Project Page](https://videoagent.github.io/) | QA / Temporal Grounding | / |
| **VideoAgent**<br>@Stanford | [VideoAgent: Long-form Video Understanding with Large Language Model as Agent](https://arxiv.org/abs/2403.10517) <br> 24.03.15 / ECCV'24 / [Project Page](https://wxh1996.github.io/VideoAgent-Website/) | QA | / |

## Benchmarks
### General QA
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **HourVideo** <br> @Stanford | [HourVideo: 1-Hour Video-Language Understanding](https://arxiv.org/abs/2411.04998) <br> 24.11.07 / NIPS'24 D&B / [Project Page](https://hourvideo.stanford.edu/) | LLM+Human Annotated / 500 videos / 20~120m / 13K QAs | Long / Egocentric |
| **TOMATO** <br> @Yale | [TOMATO: Assessing Visual Temporal Reasoning Capabilities in Multimodal Foundation Models](https://arxiv.org/abs/2410.23266) <br> 24.10.31 / ArXiv / [Project Page](https://github.com/yale-nlp/TOMATO) | **Human Annotated** / 1.4K videos / 0~72s / 1.5K QAs | / |
| **TemporalBench** <br> @UWM | [TemporalBench: Benchmarking Fine-grained Temporal Understanding for Multimodal Video Models](https://arxiv.org/abs/2410.10818) <br> 24.10.14 / ArXiv / [Project Page](https://temporalbench.github.io/#leaderboard) | Human+LLM Annotated / 2K videos / 0~20m / 10K QAs | / |
| **LongVideoBench** <br> @NTU | [LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding](https://arxiv.org/abs/2407.15754) <br> 24.07.22 / NIPS'24 D&B / [Project Page](https://longvideobench.github.io/) | **Humman Annotated** / 3.8K videos / 0~1h / 6.7K QAs | / |
| **LVBench** <br> @Zhipu | [LVBench: An Extreme Long Video Understanding Benchmark](https://arxiv.org/abs/2406.08035) <br> 24.06.12 / ArXiv / [Project Page](https://lvbench.github.io/) | **Humman Annotated** / 500 videos / avg. 1h / 1.5k QAs | / |
| **VideoMME** <br> @VideoMME-Team| [Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis](https://arxiv.org/abs/2405.21075) <br> 24.05.31 / ArXiv / [Project Page](https://video-mme.github.io/) | **Humman Annotated** / 900 videos / 0~60m / 2.7K QAs| / |
| **TempCompass** <br> @PKU | [TempCompass: Do Video LLMs Really Understand Videos?](https://arxiv.org/abs/2403.00476) <br> 24.03.01 / ACL'24 Findings / [Project Page](https://llyx97.github.io/tempcompass/) | ChatGPT+Human Annotated / 410 videos / 0~35s / 7.5K QAs | / |
### Caption
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **VDC** <br> @UW | [AuroraCap: Efficient, Performant Video Detailed Captioning and a New Benchmark](https://arxiv.org/abs/2410.03051) <br> 24.10.04 / ArXiv / [Project Page](https://rese1f.github.io/aurora-web/) | GPT-4o Annotated / 1027 videos / 0~60s / 1027 captions | Evaluate Captioning using QAs |
### Temporal Grounding
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **QVHightlight** <br> @UNC | [QVHighlights: Detecting Moments and Highlights in Videos via Natural Language Queries](https://arxiv.org/abs/2107.09609) <br> 21.07.20 / NIPS'21 / [Project Page](https://github.com/jayleicn/moment_detr) | **Human Annotated** / 10K videos / avg. 150s / 10K queries | / |
| **Charades-STA** <br> @USC| [TALL: Temporal Activity Localization via Language Query](https://arxiv.org/abs/1705.02101) <br> 17.05.05 / ICCV'17 / [Project Page](https://github.com/jiyanggao/TALL) | Rule+Human Annotated / 4233 clip-sentence pairs | / |
| **ActivityNet Captions** <br> @Stanford| [Dense-Captioning Events in Videos](https://arxiv.org/abs/1705.00754) <br> 17.05.05 / ICCV'17 / [Project Page](https://cs.stanford.edu/people/ranjaykrishna/densevid/) | **Human Annotated** / 20K videos / 0~270s | / |
| **YouCook2** <br> @Google Brain | [Towards Automatic Learning of Procedures from Web Instructional Videos]() <br> 17.03.28 / AAAI'18 / [Project Page](http://youcook2.eecs.umich.edu/) | **Human Annotated** / 2K videos / 0~800s / avg. 7.7 segments per video | / |
### Action Recognition
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **FineGym** <br> @CUHK | [FineGym: A Hierarchical Video Dataset for Fine-grained Action Understanding](https://arxiv.org/abs/2004.06704) <br> 20.04.14 / CVPR'20 / [Project Page](https://sdolivia.github.io/FineGym/) | **Human Annotated** | / |
### Hallucination
| Name | Paper | Metadata | Note |
|:---|:---|:---|:---|
| **VideoHallucer** <br> @BIGAI | [VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models](https://arxiv.org/abs/2406.16338) <br> 24.06.24 / ArXiv / [Project Page](https://videohallucer.github.io/) | Rule+Human Annotated / 948 videos / 7~187s / 1.8K QAs | / |

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

## Research Topics
### Visual Encoding
| Name | Paper | Note |
|:---|:---|:---|
| **ElasticTok** <br> @Berkeley | [ElasticTok: Adaptive Tokenization for Image and Video](https://arxiv.org/abs/2410.08368) <br> 24.10.10 / ArXiv / [Project Page](https://largeworldmodel.github.io/elastictok/) | Visual Tokenizer |
| **VideoPrism** <br> @Google | [VideoPrism: A Foundational Visual Encoder for Video Understanding](https://arxiv.org/abs/2402.13217) <br> 24.02.20 / ICML'24 / [Project Page](https://research.google/blog/videoprism-a-foundational-visual-encoder-for-video-understanding/) | Video Encoder |
| **MMVP** <br> @NYU | [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209) <br> 24.01.11 / ArXiv / [Project Page](https://tsb0601.github.io/mmvp_blog/) | Hybrid Encoder |
### Visual Token Reduction
| Name | Paper | Note |
|:---|:---|:---|
| **RLT**  <br> @CMU | [Don't Look Twice: Faster Video Transformers with Run-Length Tokenization](https://arxiv.org/abs/2411.05222) <br> 24.11.07 / NIPS'24 / [Project Page](https://rccchoudhury.github.io/rlt/) | Run-Length Tokenization |
| **InTI** <br> @NJU | [Dynamic and Compressive Adaptation of Transformers From Images to Videos](https://arxiv.org/abs/2408.06840) <br> 24.08.13 / ECCV'24 / [Project Page]() | Dynamic Inter-frame token interpolation |
| **Cambrian-1** <br> @NYU | [Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs](https://arxiv.org/abs/2406.16860) <br> 24.06.24 / ArXiv / [Project Page](https://cambrian-mllm.github.io/) | Spatial Vision Aggregator |
| **FastV** <br> @PKU | [An Image is Worth 1/2 Tokens After Layer 2: Plug-and-Play Inference Acceleration for Large Vision-Language Models](https://arxiv.org/abs/2403.06764) <br> 24.03.11 / ECCV'24 / [Project Page](https://github.com/pkunlp-icler/FastV) | Prune tokens after layer 2 |
### Streaming
| Name | Paper | Note |
|:---|:---|:---|
| **StreamChat** <br> @CUHK | [StreamChat: Chatting with Streaming Video](https://arxiv.org/abs/2412.08646) <br> 24.12.11 / ArXiv'24 / [Project Page](https://jihaonew.github.io/projects/streamchat.html) | / |
| **Streaming_VDC** <br> @Google | [Streaming Dense Video Captioning](https://arxiv.org/abs/2404.01297) <br> 24.04.01 / CVPR'24 / [Project Page](https://github.com/google-research/scenic/tree/main/scenic/projects/streaming_dvc) | Framework |

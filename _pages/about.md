---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am currently a second-year Master's student in the [School of Computer Science and Engineering](https://cse.seu.edu.cn/) at [Southeast University](https://www.seu.edu.cn/), specializing in Human-AI Interaction and Multi-Agent Systems. I am supervised by [Associate Prof. Zhuying Li](https://zhuyingli.info/) at the [PALM Lab](https://palm.seu.edu.cn/).

## Education
- **MSc in Computer Science and Engineering**, [Southeast University](https://www.seu.edu.cn/), China<br>
  2024 - 2027 (expected)

- **BSc in Software Engineering**, [Southeast University](https://www.seu.edu.cn/), China<br>
  2020 - 2024

- **Exchange Program in Computer Science**, [KTH Royal Institute of Technology](https://www.kth.se/en), Sweden<br>
  Jan. 2023 - Jun. 2023

## Research Interests
- Human-AI Collaboration and AI Scaffolding
- Human-Computer Interaction (HCI)
- Multi-Agent Systems
- Generative AI Systems and Efficient Inference

## Working Experience

- **TikTok Engineer Intern**, [ByteDance](https://www.bytedance.com/en/), Beijing, China<br>
  Apr. 2026 - Present
  - Working on finetuning SEED-1.8 model for creative asset selection for user growth.
  - Developed and shipped the ad budget allocation system, enabling automated budget distribution across ad campaigns and countries.
  - Building a creative asset manager agent for user growth scenarios, integrating LLM reasoning with tool-based workflows for asset retrieval, analysis, planning, and management.

- **AI Frameworks Engineer Intern**, [Intel Corporation](https://www.intel.com/content/www/us/en/homepage.html), Shanghai, China<br>
  Nov. 2025 - Apr. 2026
  - Adapted and optimized 15+ multimodal AIGC models and end-to-end generation pipelines, covering text-to-image, image editing, text/image-to-video, speech synthesis and cloning, 3D generation, and video super-resolution.
  - Contributed to SGLang Diffusion support for Intel XPU, including XCCL distributed communication adaptation and Triton kernel fallback paths for diffusion model inference.
  - Built DiT inference acceleration for ComfyUI with block-level output caching and reuse, achieving 1.3x-2.0x speedup while preserving generation quality, and up to 2.2x when combined with `torch.compile`.
  - Supported GGUF quantized inference on Intel XPU through SYCL custom operators, reducing memory pressure for large generative models.
  - Implemented Raylight-based multi-GPU video generation for Wan2.2 14B and HunyuanVideo 1.5.

- **Co-Founder & AI Platform Engineer**, INFERA, Shenzhen, China<br>
  Mar. 2025 - Aug. 2025
  - Participated in the design and development of InfNest, a proactive AI and multi-agent platform for next-generation edge hardware and AI glasses.
  - Developed the InfNest multi-agent framework with Master/Member/Group hierarchy, a three-layer memory system, MCP-based tool extension, and a dynamic workflow engine for complex task orchestration.
  - Contributed to backend development for the Melons AI headphone project, implementing AI music services.

- **AI Frameworks Engineer Intern**, [Intel Corporation](https://www.intel.com/content/www/us/en/homepage.html), Shanghai, China<br>
  Sep. 2023 - May. 2024
  - Contributed to the development and optimization of [ipex-llm](https://github.com/intel/ipex-llm), an open-source project for improving large language model fine-tuning and inference on Intel GPU, NPU, and CPU.
  - Implemented and integrated efficient parameter fine-tuning methods, including QLoRA, LISA, and GaLoRA, for mainstream models such as LLaMA and Mistral.
  - Supported inference adaptation for mainstream LLMs, including low-bit quantization, Mixtral-8x7B sparse MoE inference optimization, and speculative decoding to improve inference throughput.
  - Supported enterprise deployment and performance tuning, including Docker- and Kubernetes-based distributed inference and fine-tuning environments.

- **C++ Developer Intern**, [China Telecom Corporation Limited](https://www.chinatelecomglobal.com/), Nanjing, China<br>
  Jul. 2023 - Aug. 2023
  - Worked on streaming media applications and system concurrency optimization.


## Selected Projects

- **[ComfyUI-CacheDiT](https://github.com/Jasonzzt/ComfyUI-CacheDiT)**, 280+ GitHub stars<br>
  Jan. 2026 - Feb. 2026
  - Designed a warmup-skip caching strategy for Diffusion Transformer denoising, reusing block-level outputs across adjacent steps to accelerate image and video generation while preserving visual quality.
  - Implemented model-specific caching strategies for LTX-2 dual-latent video/audio generation and Wan2.2 MoE high/low-noise expert pipelines.
  - Built automatic model detection and zero-configuration ComfyUI nodes for mainstream DiT models.

- **Optical Flow and YOLO-based Underwater Fish Detection**, National College Student Innovation and Entrepreneurship Project<br>
  Dec. 2021 - May. 2023
  - Proposed an optical-flow-YOLO spatiotemporal fusion detection algorithm using Gaussian Mixture Models and optical flow to extract motion features in complex underwater scenes.
  - Built an end-to-end real-time fish detection and tracking framework, achieving 25+ FPS and improving robustness under low-light and turbid-water conditions.

## Awards and Honors
- First-class Postgraduate Scholarship, Southeast University (2024)
- President’s Scholarship, Southeast University (2021)
- Huawei Scholarship (2023)
- Zhishan Scholarship, Southeast University (2022)
- Excellent Student Leader, Southeast University (2022)
- Merit Student, Southeast University (2021)

## Publications
-	Mingtao Wu, **Ziteng Zhang**, Mengjie Tang, Zhuying Li, and Yan Wang. GreenCompass: Weaving Playful Nature Engagement into Urban Micro-Moments through Context-Aware Gamification. Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI '26). [Paper](https://dl.acm.org/doi/pdf/10.1145/3772318.3790485)
- Zhuying Li, **Ziteng Zhang**, Xin Sun, and Yan Wang. 2026. Digital Spirituality in Mainland China: Understanding Online Practices for Designing Culturally Relevant Spiritual Experiences. Proc. ACM Hum.-Comput. Interact. 10, 2, Article CSCW013 (CSCW '26). [Paper](https://doi.org/10.1145/3788049)
- Mingtao Wu, Zhuying Li, **Ziteng Zhang**, and Yan Wang. 2025. GreenCompass: Experiencing Urban Pocket Time as Playful Nature Connection through Context-Aware Gamification. In Proceedings of the Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA '25). [Paper](https://doi.org/10.1145/3706599.3719811)

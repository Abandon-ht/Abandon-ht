<p align="center">
  <img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/hero.svg?v=3" width="100%" alt="小佬鼠 / LittleMouse — 才疏学浅的小佬鼠。Curious about models, machines, music and minds." />
</p>

<p align="center">
  <a href="#projects">项目 / Projects</a> · <a href="#models">模型 / Models</a> · <a href="#focus">方向 / Focus</a> · <a href="#about">关于 / About</a>
</p>

<p align="center">
  <a href="https://huggingface.co/Abandon-ht">🤗 Hugging Face / Abandon-ht</a> · <a href="https://x.com/Abandon_ht">X / @Abandon_ht</a> · <a href="https://space.bilibili.com/425988695">Bilibili ↗</a>
</p>

你好，我是 **小佬鼠 · LittleMouse**，也叫 **Abandon-ht**，关注**端侧模型部署、语音交互与嵌入式系统**。我的实践围绕 ASR、TTS、LLM 与计算机视觉展开，从模型导出与图适配、量化编译，到 C++ / Rust 运行时集成和真实设备上的交互应用。

Hi, I'm **LittleMouse (小佬鼠)**, also known as **Abandon-ht**. I focus on **on-device model deployment, speech interaction and embedded systems**, working across ASR, TTS, LLMs and computer vision—from model export, graph adaptation and quantization to C++ / Rust runtime integration and interactive applications on real devices.

<p>
  <img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/stack.svg?v=3" width="100%" alt="C / C++ · Python · Rust · PyTorch · ONNX · Tauri · Linux" />
</p>

<a id="projects"></a>

## 精选项目 · Featured Projects

<table>
<tr>
<td width="50%"><a href="https://github.com/Abandon-ht/DesktopPet"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/desktop-pet.svg?v=3" width="100%" alt="DesktopPet：本地语音交互与 Live2D 桌面伙伴；A Live2D companion with local voice" /></a></td>
<td width="50%"><a href="https://github.com/Abandon-ht/YOLO26.axera"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/yolo26.svg?v=3" width="100%" alt="YOLO26 / NPU：模型导出、NPU 编译与推理；Model export, NPU compilation and inference" /></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/Abandon-ht/sherpa-onnx"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/sherpa.svg?v=3" width="100%" alt="sherpa-onnx：AX650 ZipVoice TTS 后端贡献；AX650 ZipVoice TTS backend contribution" /></a></td>
<td width="50%"><a href="https://github.com/Abandon-ht/m3axpi_model"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/m3axpi.svg?v=3" width="100%" alt="m3axpi_model：YOLOv5 / YOLOv8 端侧部署示例；On-device YOLOv5 / YOLOv8 examples" /></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/Abandon-ht/ax-AI_develop_guide"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/ax-guide.svg?v=3" width="100%" alt="Edge AI Guide：检测、分割与姿态模型部署；Detection, segmentation and pose deployment" /></a></td>
<td width="50%"><a href="https://github.com/Abandon-ht/ModuleLLM_Development_Guide"><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/module-llm.svg?v=3" width="100%" alt="ModuleLLM Guide：ESP32 与 PC 端开发资料；ESP32 and PC development notes" /></a></td>
</tr>
</table>

**工具与更多探索 · Tools & More**

- [llama-tokenizer-rs](https://github.com/Abandon-ht/llama-tokenizer-rs) — Rust BPE / SentencePiece 分词器 · A Rust BPE / SentencePiece tokenizer.
- [ncnn-android-yolo11](https://github.com/Abandon-ht/ncnn-android-yolo11) — Android 视觉推理探索 · Android vision inference experiments (fork).
- [ModuleLLM-OpenAI-Plugin](https://github.com/Abandon-ht/ModuleLLM-OpenAI-Plugin) — 模块接入示例 · Module integration examples.

<a id="models"></a>

## 模型与导出资产 · Models & Export Artifacts

在 Hugging Face 分享语音、语言和视觉模型的转换产物与部署资料。<br />
I share converted models, export artifacts and deployment notes for speech, language and vision on Hugging Face.

| 方向 · Area | 公开仓库 · Public Repositories |
| :--- | :--- |
| **语音识别 · ASR** | [SenseVoiceSmall](https://huggingface.co/Abandon-ht/SenseVoiceSmall-axmodel) · [Qwen3-ASR](https://huggingface.co/Abandon-ht/Qwen3-ASR-0.6B-axmodel) · [Parakeet TDT](https://huggingface.co/Abandon-ht/parakeet-tdt-0.6b-v3-axmodel) |
| **语音合成 · TTS** | [Kokoro](https://huggingface.co/Abandon-ht/kokoro-multi-lang-v1_1-axmodel) · [Supertonic](https://huggingface.co/Abandon-ht/supertonic-3-axmodel) · [Chatterbox](https://huggingface.co/Abandon-ht/chatterbox-axmodel) |
| **本地大模型 · LLM** | [Qwen3-4B](https://huggingface.co/Abandon-ht/Qwen3-4B-LLM8850) · [Qwen2.5-0.5B Merge](https://huggingface.co/Abandon-ht/qwen2.5-0.5b-ha-merged) |
| **视觉推理 · Vision** | [YOLO11](https://huggingface.co/Abandon-ht/YOLO11-axmodel) · [Palm Detection](https://huggingface.co/Abandon-ht/palm_detection_mediapipe_axmodel) · [Hand Pose](https://huggingface.co/Abandon-ht/handpose_estimation_mediapipe_axmodel) |

→ **[Hugging Face / Abandon-ht — 查看全部模型 · Explore all models](https://huggingface.co/Abandon-ht)**

<a id="focus"></a>

## 技术方向与工程实践 · Focus & Engineering

| 方向 · Area | 实践内容 · Engineering Focus |
| :--- | :--- |
| **ASR / TTS** | 多模型适配、VAD、文本前端与语音运行时集成。<br />Multi-model adaptation, VAD, text frontends and speech runtime integration. |
| **LLM** | 本地推理、prefill / KV cache 工作流与分词器工具。<br />Local inference, prefill / KV-cache workflows and tokenizer tools. |
| **计算机视觉 · Vision** | 检测、分割、姿态与多媒体推理链路。<br />Detection, segmentation, pose and multimedia inference pipelines. |
| **部署工程 · Deployment** | ONNX 图适配、量化校准、NPU 编译与 CPU / NPU 协同。<br />ONNX graph adaptation, quantization, NPU compilation and CPU / NPU integration. |
| **嵌入式交互 · Embedded** | ESP32 / Linux、音频采集、UART / I2S 与应用编排。<br />ESP32 / Linux, audio I/O, UART / I2S and application orchestration. |

<p><img src="https://raw.githubusercontent.com/Abandon-ht/Abandon-ht/main/assets/voice-pipeline.svg?v=3" width="100%" alt="端侧语音交互 / On-device voice: Audio → VAD / KWS → ASR → LLM → TTS → Playback" /></p>

<a id="open-source"></a>

## 开源参与 · Open Source

为 **sherpa-onnx** 提交 AX650 ZipVoice TTS 后端实现，让语音合成模型在端侧硬件上运行。<br />
Contributed an **AX650 ZipVoice TTS backend proposal** to **sherpa-onnx**, bringing speech synthesis to on-device hardware.

→ [上游提案与实现 · Upstream proposal & implementation: PR #4038](https://github.com/k2-fsa/sherpa-onnx/pull/4038)

欢迎在对应项目的 **Issues / Discussions** 中交流模型部署、设备适配与使用体验。<br />
Feel free to discuss model deployment, device integration and feedback in the relevant project's **Issues / Discussions**.

<a id="about"></a>

## 关于小佬鼠 · About LittleMouse

**才疏学浅的小佬鼠，还在学习，也还在拆解世界。**<br />
**A curious LittleMouse, always learning—and taking the world apart to understand it.**

我容易被「有结构、有原理、有思想，能拆开研究」的东西吸引。<br />
I'm drawn to things with structure, underlying principles and ideas worth taking apart.

<details>
<summary><b>代码之外，我喜欢什么？ · What catches my curiosity beyond code?</b></summary>

| 兴趣 · Interest | 我喜欢拆解的东西 · What I Like to Explore |
| :--- | :--- |
| **知识 · Ideas** | 哲学、认知科学、语言与思维，以及神学、历史和思想。意识如何形成？语言与抽象思考是什么关系？自由意志与决定论如何相处？<br />Philosophy, cognitive science, language and thought, theology and history—especially consciousness, abstract thinking, free will and determinism. |
| **科技 · Systems** | Apple Silicon、CPU / GPU / NPU 架构、操作系统、统一内存、HDR、音频系统与性能分析。<br />Apple Silicon, CPU / GPU / NPU architectures, operating systems, unified memory, HDR, audio systems and performance analysis. |
| **人工智能 · AI** | Transformer、Attention、KV cache、量化与推理加速；vLLM、SGLang、llama.cpp、MLX；ASR、TTS、Agent、多模态、论文与 benchmark。也喜欢自己跑模型、做测试。<br />Model architectures, inference systems, speech, agents and multimodal AI. I enjoy reading papers, running models and testing how they perform. |
| **古典音乐 · Classical Music** | 尤其喜欢巴赫与复调，也喜欢肖邦、贝多芬、舒伯特、德彪西等。主题、对题、卡农、倒影，以及和声、织体与乐曲结构，都值得细听。<br />Especially Bach and counterpoint, alongside Chopin, Beethoven, Schubert, Debussy and others—subjects, countersubjects, canons, inversion, harmony, texture and musical form. |
| **游戏 · Games** | 有世界观、复杂叙事、哲学问题或独特系统的作品；也会研究 NPC AI、图形渲染、超分辨率与游戏引擎。<br />Rich worlds, layered narratives, philosophical questions and distinctive systems—as well as NPC AI, rendering, upscaling and game engines. |

所以，我的推荐算法大概比较难伺候 😂<br />
My recommendation algorithm has unusually specific tastes. 😂

</details>

<p align="center"><a href="https://github.com/Abandon-ht?tab=repositories">全部仓库 · Repositories ↗</a> · <a href="https://huggingface.co/Abandon-ht">Hugging Face ↗</a> · <a href="https://x.com/Abandon_ht">X ↗</a> · <a href="https://space.bilibili.com/425988695">Bilibili ↗</a></p>

---

<p align="center"><sub>贴近硬件，让智能走向端侧。<br />Build close to the hardware. Bring intelligence to the edge.</sub></p>

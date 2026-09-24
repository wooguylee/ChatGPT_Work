# Hugging Face 모델 중복 제외 인덱스

이 파일은 `huggingface-model-trends` 자동화의 **중복 제거 기준(source of truth)** 입니다. 새 채팅의 대화 기억보다 이 파일을 우선합니다.

## 중복 판정 규칙

- 아래에 있는 모델/계열은 다시 소개하지 않습니다.
- 같은 계열의 크기 변형, 모델명 변경, 양자화, GGUF/ONNX/MLX/FP8/NVFP4 등 포맷 변환, 경미한 미세조정, 직접 파생본도 원본과 사실상 동일하면 제외합니다.
- 아키텍처·모달리티·핵심 학습법이 크게 바뀐 명백한 차세대 모델은 1차 출처로 차이를 확인한 경우에만 별도 후보로 인정합니다.
- 일일 보고서 저장이 성공한 뒤에만 새로 소개한 모델/계열을 이 파일에 추가합니다.

## 기존 누적 제외 목록 — 2026-08-26 마이그레이션 기준

thinkingmachines/Inkling; zai-org/GLM-5.2; baidu/Unlimited-OCR; google/gemma-4-31B-it; OpenMOSS-Team/MOSS-Transcribe-Diarize; nvidia/Cosmos3-Edge; tencent/Hy3; ATH-MaaS/OvisOCR2; openbmb/MiniCPM-RobotManip·MiniCPM-RobotTrack; Cactus-Compute/needle·needle2; poolside/Laguna-S-2.1; prism-ml/Ternary-Bonsai-27B·Bonsai-27B; Motif-Technologies/Motif-3-Beta; nvidia/Nemotron-3-Embed-1B; Wan-AI/Wan-Dancer-14B; upstage/Solar-Open2-250B; Nanbeige/Nanbeige4.2-3B; microsoft/Mage-Flow; Krea 2; nvidia/Nemotron-3.5-ASR-Streaming; Antares; Kwaipilot/KAT-Coder-V2.5; PaddlePaddle/HPD-Parsing; internlm/Intern-S2; swiss-ai/Apertus-v1.5; microsoft/Fara1.5; FINAL-Bench/Aether-5Attn; Soofi-S; Lightricks/LTX-2.3·LTX-2.5; inclusionAI/LLaDA2.2; microsoft/VibeVoice-ASR; Inflect v2; moonshotai/Kimi-K2.7-Code·Kimi-K3; deepseek-ai/DeepSeek-V4; MiniMaxAI/MiniMax-M3·MiniMax-H3·MiniMax-Music3; Anima; amd/Instella-MoE-16B-A3B; InternScience/Agents-A1; DIAMOND; nvidia/Cosmos-H-Dreams; nvidia/Qwen-Image-Flash; lightonai/LightOnOCR-2; k2-fsa/OmniVoice; microsoft/Mage-VL·Mage-ViT; LiquidAI/LFM2.5-Encoder·LFM2.5-2.6B·LFM2.5-VL-3B; nyralabs/CrisperWhisper2.0; nvidia/LocateAnything-3B; ecmwf/AIFS Single v2; skt/A.X-K2(A.X-K2-ALM 포함)·KRAFTON/A.X-K2-Raon-Speech; Audio8/Audio8-TTS-Preview·Audio8-ASR-0.1B; qvac/VisionPsy-Nano; FermionResearch/Neutrino-8B; XYZAILab/XYZ-Aquila; mindlab-research/Macaron-V1; lightonai/mDenseOn·mLateOn; lvladikov/SeedVR2-1.4B; acvlab/ABot-World-0; LGAI-EXAONE/K-EXAONE-2.0; sensenova/SenseNova-U1.5-8B-MoT; empero-ai/Qwythos-27B; BAAI/AREX; Alibaba-DAMO-Academy/RynnBrain1.1; deepreinforce-ai/Ornith-1.0 및 직접 미세조정본; H-EmbodVis/TurboVLA; feyninc/FeyNobg; jinaai/jina-reranker-v3.5; vovaRL/NanoColibri-Instruct·Colibri-Nano; meituan-longcat/LongCat-Flash-Lite-Sparse; bench-labs/PixelModel-v5; harrrshall/BarunLM-35M; Trelis/tiron; Aratako/Irodori-TTS-v4-Small; openpangu/openPangu-2.0; tsinghua-sigs-robot-lab/VeriLoop Coder; ASLP-lab/MeanVC2; nlpai-lab/LAMAR; google/DiffusionGemma; OpenMOSS-Team/MOSS-TTS-Realtime; Alibaba-NLP/UEmbed; Efficient-Large-Model/SANA-Video; inclusionAI/Ling-3.0; deepgrove/Maple; mistralai/Shieldstral; nvidia/NVIDIA-NemotronLabs-VoiceChat-11B; nvidia/Alpamayo2-Super; nvidia/NVIDIA-Nemotron-Parse-2.0; sand-ai/MAGI-2; jdopensource/JoyAI-Video-Edit; SyzygyResearch/Mach-1-Additive; AxiomicLabs/GPT-X2.5; Wan-AI/Wan2.2-Animate-2; endless-frontier/BigBang-v1; Boogu/Boogu-Image-0.1; KBlueLeaf/TIPOv2; kulibinai/CADENA; nvidia/MagpieTTS Multilingual; ai9stars/G9v3; OS-Copilot/OS-Shepherd; SupraLabs/Supra2-100M; paige-ai/Prism2; openbmb/MiniCPM-o-4.5; google/TabFM; OpenMOSS-Team/MOSS-VL-Realtime; MCG-NJU/VideoChat3-4B; EximiusLabs/Fusion Embedding 2; meta-models/Muse-Glimmer-30B; IndexTeam/IndexTTS-2.5; H-EmbodVis/SimWAM; erikkaum/lattice-retrieval; bench-labs/AudioModel-v1; nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B; webAI-Official/TwIL-LM3; SupraLabs/SupraElegans-500k; Qwen/Qwen3.8-2.4T-A95B; CohereLabs/North-Micro-Vision-Instruct; dots-studio/dots3-note; bosonai/Higgs-TTS-3·Higgs Audio v3; jinaai/jina-embeddings-v5-omni; xiaomi-research/MiLMMT-46; FireRedTeam/FireRedTTS3; Longin-Yu/PaDoc; pymaster/VocalRender; kcz358/Aero-Realtime; bench-labs/ObjectModel-v1; AlayaLab/Evoke; ARTPARK-IISc/SraVaani-1.0; XiaomiRobotics/Xiaomi-Robotics-1; mispeech/MiDashengLM-Gen; Alibaba-DAMO-Academy/RynnValue; Qwen/Qwen3.8-27B; guidelabs/Steerling-8B; TeraSpace/TeraTTSv2; TencentARC/SCoPE; inspatio/QuerySplat; openbmb/VoxCPM2; tencent/EVIE; YJX-Xiaomi/ControlFoley; kandinskylab/KVAE-Audio; NeoQuasar/Kronos; tencent/UI-Mate-27B; danish-foundation-models/DFM-Mimir; sii-research/tau-0-vla; AlayaLab/Marionette; dxtech-asia/deepx-embedding-v1; superwhisper/s1-mini; nineninesix/gepard-1.0; KRAFTON/Raon-OpenTTS; netease-youdao/Confucius4-TTS; webAI-Official/webAI-ColVec1.1; ornith-ai/Ornith-1.5-35B-A3B; AntResearch/4DAnyone; theforecastingcompany/t0-alpha; nvidia/cmd(Context-Matched Distillation); ASLP-lab/CN-MultiDialect-ASR; numind/NuExtract3; StarDoc-AI/NaviDC-OCR; WPS-Qingqiu/OmniAlign; patronus-studio/wolf-defender-prompt-injection; google/TIPSv2; llm-jp/llm-jp-4-33b-thinking·LLM-jp-4 33B; openbmb/MiniCPM5-1B; BananaMind/BananaMind-2.1-Unified; bench-labs/cagliostro-v1; facebook/MoEViE 계열(B16/L16/H14).

## 날짜가 확인된 과거 보고서 계열

### 2026-08-16
- AlayaLab/Evoke 및 EVOKE 직접 변형본
- ARTPARK-IISc/SraVaani-1.0 및 직접 변형본·ONNX 배포본
- XiaomiRobotics/Xiaomi-Robotics-1 계열(5B·RoboCasa·VLABench 등 동일 기반 직접 파생본)
- mispeech/MiDashengLM-Gen 및 직접 변형본
- Alibaba-DAMO-Academy/RynnValue 계열(4B·8B 및 직접 변형본)

### 2026-08-17
- Qwen/Qwen3.8-27B 및 직접 변형본(FP8·GGUF·양자화 포함)
- guidelabs/Steerling-8B 및 직접 변형본·어댑터·단순 양자화본
- TeraSpace/TeraTTSv2 및 직접 변형본
- TencentARC/SCoPE 및 직접 변형본
- inspatio/QuerySplat 및 직접 변형본

### 2026-08-18
- openbmb/VoxCPM2 및 직접 변형본
- tencent/EVIE-Preview-4.5B 및 EVIE 계열 직접 변형본
- YJX-Xiaomi/ControlFoley 및 직접 변형본
- kandinskylab/KVAE-Audio 및 직접 변형본
- NeoQuasar/Kronos-base 및 Kronos 금융 K-line 계열(동일 체크포인트·크기 변형·토크나이저 포함)

## 이 채팅에서 마이그레이션한 소개 모델
### 2026-08-25
- FireRedTeam/FireRedAudio 및 FireRedAudio 직접 크기·양자화·포맷·경미한 파생본
- openbmb/MiniCPM5-1B — 기존 누적 목록에도 포함되어 있으며 MiniCPM5-1B 직접 변형본 전체 제외
- TomoroAI/tomoro-colqwen3-embed-4b 및 직접 양자화·포맷·경미한 파생본
- ayousanz/kodama-ja-streaming-small 및 직접 ONNX/양자화·포맷·경미한 파생본
- ai-sage/Giga-Embeddings-instruct-10B-A1.8B-0826 및 같은 Giga-Embeddings 0826 계열의 단순 크기/포맷/양자화 변형본

### 2026-08-26
- ibm-granite/granite-4.2-30b 및 Granite 4.2 계열의 단순 크기·양자화·GGUF/FP8/FP4/포맷 변형본
- apodex/Apodex-1.1-mini 및 Apodex 1.1 직접 변형본
- tencent/WeMM-Embedding-9B 및 WeMM-Embedding 계열의 단순 크기·양자화·포맷 변형본
- ibm-granite/granite-speech-5.0-470m-turboctc 및 Granite Speech 5.0 TurboCTC 직접 변형본(라이선스만 다른 NC 배포 포함)
- fastino/gliner2.5-multi-v1 및 GLiNER2.5 계열의 small/base/multi 단순 크기·포맷·양자화 변형본

### 2026-08-27
- Qwen/Qwen3.8-Flash-Next 및 직접 양자화·GGUF/FP8/NVFP4·포맷·경미한 파생본. 기존 Qwen3.8-27B와 달리 QSA·Gated Residual·N-gram Embedding 기반 Qwen4-preview architecture로 별도 계열 판정
- zai-org/GLM-5.3-Flash 및 직접 양자화·포맷·경미한 파생본. 기존 GLM-5.2와 달리 새 base model·native multimodal·hybrid sparse/linear attention·mHC를 도입해 별도 계열 판정
- BreezeBlue/Breeze-TTS-2 및 직접 checkpoint·adapter·양자화·포맷·경미한 파생본
- thomsonreuters/Thomson-1.0-Small 및 Thomson-1.0-Small의 직접 양자화·포맷·경미한 파생본(Qwen3.6-35B-A3B/Snowdon1.1-Small lineage)
- open-gigaai/GigaBrain-0.7-3.5B-Base 및 GigaBrain-0.7 동일 base checkpoint의 단순 embodiment fine-tune·양자화·포맷 파생본
### 2026-08-28
- kyutai/pocket-tts 및 직접 양자화·ONNX/MLX/WASM/C++/C# 포팅·포맷·경미한 파생본
- PerceptronAI/Isaac-0.5 계열(공식 base/action checkpoints 포함) 및 단순 양자화·포맷·직접 파생본
- briaai/FIBO 계열(FIBO base·Fibo-1.5 포함) 및 DMD/DMD-R few-step·단순 양자화·포맷·경미한 미세조정 파생본

### 2026-08-29
- tencent/Hy4-preview 및 Hy4 계열의 FP8·양자화·GGUF/포맷·경미한 파생본. 기존 Hy3와 달리 Gated DSA + IndexCache, iHC residual pathway, 1M context, 256 routed experts와 native MTP를 결합한 차세대 architecture로 별도 계열 판정

### 2026-08-30
- pipecat-ai/phonellm-alpha-1 및 PhoneLLM Alpha 1의 단순 양자화·GGUF/FP8/포맷·크기·경미한 파생본. Nemotron 3 Nano 기반 아키텍처는 유지하지만 full-parameter SFT로 전화·실시간 음성 Agent의 저지연 비추론 tool/function calling을 핵심 목적으로 특화해 별도 계열로 판정
- FermionResearch/Phonon-1 및 Phonon-1-Big 등 동일 Phonon-1 계열의 단순 크기·양자화·MLX/ONNX/포맷 파생본. Qwen3-ASR-0.6B 계보지만 작성자 설명상 2.4-bit/weight 조건을 학습 단계부터 적용한 low-bit on-device ASR로 학습 방법과 운용 목적 변화가 커 별도 계열로 판정

### 2026-08-31
- samuel-vitorino/sopro-v2-turbo 및 Sopro V2 계열의 단순 크기·ONNX/INT8/양자화·브라우저 포팅·포맷·경미한 파생본. Sopro V1 대비 tokenizer·AR backbone·acoustic generation·vocoder를 크게 재설계하고 500M teacher에서 120M student distillation + reflow 2-step acoustic solver를 도입한 차세대 계열로 판정
- Muse-Ltd/Muse-Robotics-1 및 동일 checkpoint의 단순 크기·양자화·포맷·경미한 embodiment fine-tune 파생본. 약 120M 규모의 fully-trainable VLA로 vision/language/fusion/action을 end-to-end 공동학습하며, 8 latent plan tokens의 3회 반복 deliberation과 rectified-flow action chunk generation을 결합한 별도 계열로 판정

### 2026-09-01
- deepseek-ai/DeepSeek-V4-Flash-Vision-Exp 및 동일 체크포인트의 단순 양자화·GGUF/FP8·포맷·경미한 fine-tune 파생본. 기존 DeepSeek-V4 계열이 누적 목록에 있으나 공식 모델 카드가 DeepSeek-V4 최초의 experimental multimodal model로 명시하며 visual modules(vision encoder/aligner)와 continued training을 도입해 modality와 multimodal Agent 입력 구조가 크게 바뀌었으므로 별도 멀티모달 분기로 판정
- google/timesfm-3.0-pytorch 및 TimesFM 3.0 동일 체크포인트의 단순 양자화·포맷·직접 fine-tune 파생본. Stacked Mixing Transformer + Variate Attention + CPM Iterative RevIN 구조와 native multivariate·covariate forecasting을 도입한 TimesFM 3.0 계열
- darkps/ice-012-audio 및 ICE-012 Audio 동일 체크포인트의 단순 양자화·포맷·경미한 파생본. Qwen3 기반 causal backbone에 8-codebook audio-token embedding/output heads와 Higgs Audio V2 tokenizer를 결합한 streaming multilingual TTS·voice-cloning 계열

### 2026-09-07
- XHToken/Spark-X2.5-4B 및 Spark-X2.5 계열(1.7B 포함)의 단순 크기·GGUF/MLX·양자화·포맷·경미한 fine-tune 파생본. hybrid full-attention + sliding-window attention, native 1M context, MOPD 기반 post-training을 결합한 compact coding·agent 계열
- IFM/K2-Horizon-MoVA-36B-A4B 및 K2-Horizon 계열(0.9B·7B·36B-A4B·375B-A23B 등)의 단순 크기·GGUF/양자화·포맷·경미한 파생본. MoE + Mixture-of-Values attention과 native 512K context를 핵심으로 하는 reasoning·agent 계열
- Qwen/Qwen-Drive-1.0-4B 및 Qwen-Drive-1.0 계열의 단순 양자화·포맷·경미한 driving fine-tune 파생본. Qwen3.5 VLM backbone은 유지하지만 BEV 3D perception head와 flow-matching Planning Expert를 추가해 3D 인지·VQA·motion planning으로 근본 목적과 출력 구조가 확장되어 별도 계열로 판정
- inclusionAI/LLaDA-Image 및 LLaDA-Image Base/Turbo/FP8 계열의 단순 양자화·포맷·경미한 파생본. 기존 LLaDA2.2 text diffusion LM과 달리 unified diffusion 기반 이미지 생성·편집, image-only pretraining, Twin-DMD few-step distillation을 도입해 modality·생성 방식·목적 변화가 커 별도 이미지 계열로 판정
- LightOriginsHQ/LightNav-0 및 LightNav-0 계열의 단순 양자화·GGUF·포맷·경미한 embodiment 파생본. Qwen3-VL backbone 기반이지만 dual-channel pointing + RVQ action tokenizer로 navigation·object nav·tracking을 trajectory token interface에 통합해 행동 modality와 목적 변화가 커 별도 robotics/VLA 계열로 판정

### 2026-09-09
- TokenRhythm/NeoHorse-1-4B 및 NeoHorse-1 계열의 단순 크기·양자화·GGUF/MLX·포맷·경미한 파생본. Qwen3.5-4B 기반 architecture는 유지하지만 routing-guided agentic post-training, heterogeneous routing harness, curriculum SFT와 on-policy distillation로 Agent/tool 학습 구조가 크게 바뀌어 별도 계열로 판정
- ampixa/sanoTTS 계열(약 294k~2.27M voice variants 포함)의 단순 크기·INT8/GGUF/WASM/MCU 포팅·포맷·경미한 파생본. Piper/VITS·Kokoro teacher distillation을 초소형 runtime graph로 압축해 ESP32-S3·WASM까지 내려가는 edge TTS 계열
- rumik-ai/rumik-oss-1 및 rumik-oss 1 base/직접 양자화·포맷·경미한 파생본. Tiny Aya Fire 기반이지만 Mimi discrete speech token, 8-codebook autoregressive audio generation, 22개 언어 code-switching과 description/inline vocalization control을 결합한 multilingual TTS 계열
- perplexity-ai/pplx-pii-masking 및 직접 양자화·포맷·경미한 파생본. bidirectional Qwen3 encoder에 37-way BIOES PII token head와 conversation sensitivity head를 결합한 privacy masking 계열
- Hcompany/NeoMME 계열(260M·800M base/retriever의 단순 크기·양자화·포맷·직접 task-head 파생본). text token과 raw image patch를 별도 vision tower 없이 single Transformer encoder에서 처리하고 masked discrete-diffusion pretraining을 사용하는 multimodal-native encoder 계열

### 2026-09-10
- nex-agi/Nex-N2.5-mini 및 **Nex-N2.5 계열(mini·Pro·Max)**의 단순 크기·양자화·GGUF/MLX·포맷·경미한 fine-tune 파생본. computer/browser use, 프로그램 실행·테스트, visual feedback 기반 self-correction을 장기 Agent loop에 통합한 차세대 agentic 계열
- inclusionAI/Ling-3.0-flash-VL 및 동일 VL checkpoint의 단순 양자화·포맷·경미한 파생본. 기존 inclusionAI/Ling-3.0 계열이 누적 목록에 있으나 ViT visual encoder + 2-layer projector, VideoRoPE, KDA/Gated MLA hybrid backbone으로 image/video modality와 reasoning·planning·acting·verification 경로가 크게 확장되어 별도 multimodal 분기로 판정
- OrionLLM/OxCoder-9B 및 OxCoder-9B 직접 양자화·GGUF/MLX·포맷·adapter·경미한 파생본. Qwen3.5-9B 기반에 Frontier Agent Traces를 증류해 Claude Code·OpenCode·Codex형 coding trajectory, LSP diagnostics, read-before-write와 minimal-diff 행동을 학습한 agentic coding 계열
- Extropic-AI/Z1T-0 및 Z1T-0의 단순 포팅·양자화·포맷·경미한 파생본. fixed-connectivity sparse probabilistic hardware Z1에 맞춰 4-sparse tanh-linear projection, Dynamic Tanh normalization, Gated Convolutional Attention과 heterogeneous Z1/FPGA decode를 설계한 hardware/architecture co-design 계열
- ibm-granite/granite-timeseries-patchtst-fm-r2 및 PatchTST-FM-r2 동일 checkpoint의 단순 포맷·양자화·경미한 fine-tune 파생본. r1의 표준 Transformer를 Conformer-style block으로 교체하고 50% overlapping patch, Hamming weighting, overlap-and-add inference, 99-quantile probabilistic forecast를 도입한 차세대 time-series foundation model

### 2026-09-11
- deepseek-ai/DeepSeek-V4.1-Flash 및 DeepSeek-V4.1 계열의 단순 크기·양자화·GGUF/FP8/FP4/NVFP4·포맷·경미한 파생본. 기존 DeepSeek-V4 계열과 달리 Causal Encoder-Decoder, CSA2, FP4 KV cache, Single-Pass mHC, Engram, DSpark와 native multimodal 구조를 도입한 새 architecture family로 별도 계열 판정
- m-a-p/YuE2-3B 및 YuE2 계열의 단순 양자화·MLX/포맷·경미한 파생본. symbolic score planning, AR–NAR Mixture-of-Transformers, flow-matching acoustic latent generation과 VAE stereo decoding을 결합한 music generation/agentic editing 계열
- tencent/AuK 및 AuK-Flash 등 AuK 계열의 단순 distillation·양자화·포맷 변형본. MLLM semantic conditioning + joint audio VAE + dual-stream MMDiT→single-stream DiT hybrid rectified-flow로 TTS·speech editing·enhancement·separation을 통합한 speech foundation 계열

### 2026-09-12
- Agnes-AI/Agnes-3.0-Flash 공개 Preview checkpoint 및 Agnes 3.0 Flash Preview의 단순 양자화·GGUF/MLX·포맷·경미한 fine-tune/adapter 파생본. 54개 delta-rule recurrent layer + 18개 global-attention layer의 3:1 hybrid decoder, vision tower, 262K context, adjustable reasoning과 tool calling을 결합한 multimodal reasoning·agent 계열. production API checkpoint는 공개 Preview와 별도이므로 동일 weight로 간주하지 않음
- ai-sage/GigaChat3.5-432B-A28B-Reasoning 및 동일 Reasoning checkpoint의 단순 FP8/BF16·양자화·포맷·경미한 파생본. 432B total/28B active MoE에 MLA + GatedDeltaNet, GatedNorm, 3 MTP heads를 사용하고 6개 domain별 online-RL expert를 on-policy distillation으로 병합한 full-reasoning 분기
- yandex/AliceAI-T5-35B-A0.6B 및 AliceAI-T5 동일 base checkpoint의 단순 크기·양자화·포맷·경미한 fine-tune/adapter 파생본. 34.35B unique parameter의 encoder-decoder sparse MoE, layer당 512 experts 중 top-8 routing, RoPE+YaRN 128K context를 사용하는 text-to-text base 계열
- CohereLabs/North-Small-Translate-1.0 및 North Translate 1.0 동일 architecture의 단순 정밀도·양자화·포맷·경미한 번역 fine-tune 파생본. 218B total/25B active, 128 experts 중 top-8 + shared experts, 4096 sliding-window/global non-positional attention 3:1 혼합과 번역 전용 post-training을 사용하는 multilingual translation 계열. 기존 North-Micro-Vision-Instruct와는 목적·규모·모달리티가 달라 별도 분기로 판정

### 2026-09-13
- nasa-ibm-ai4science/NASA-IBM-Lunar-Foundation-Model 및 NASA-IBM Lunar Foundation Model 동일 backbone의 단순 LoRA·task-head·양자화·포맷·경미한 파생본. ViT-B encoder-decoder에 11개 lunar remote-sensing modality의 modality-wise tokenization, acquisition-geometry context token, NAC/WAC 100× mixed-resolution pretraining과 FlexiViT를 결합한 달 원격탐사 multimodal foundation 계열

### 2026-09-14
- internlm/Atria-Dawn-Preview 및 Atria Dawn Preview FP8·양자화·포맷·경미한 직접 파생본. GLM-5.2 744B MoE foundation 기반이지만 연구·엔지니어링 환경에서 problem analysis→tool use→code/experiment execution→result analysis→failure recovery를 반복하는 end-to-end agent loop와 256K context, Codex/Claude Code/API 연동을 핵심 목적으로 한 별도 agentic post-trained 계열로 판정. base architecture 자체가 새롭다는 의미는 아님
- oruk/orukeet 및 동일 r3 checkpoint의 NeMo·ONNX INT8·native Q8/F16·transcribe.cpp GGUF 포맷/양자화 파생본. NVIDIA Parakeet TDT 0.6B v3 기반이지만 encoder temporal depthwise filter 24,576개 중 12,288개를 fitted/frozen Gabor kernel으로 구조적으로 치환하고 multilingual·multi-accent adaptation을 결합해 단순 fine-tune보다 architecture/학습 방법 변화가 큰 별도 ASR 계열로 판정
### 2026-09-16
- TaichuAI/ZDTaichu5.0-9B 및 ZDTaichu5.0 동일 backbone의 단순 크기·양자화·포맷·경미한 fine-tune 파생본. Qwen3.5-9B + C-RADIOv4-H에 Entropy-Gated Adaptive Recurrent Reasoning을 결합하고 text/image/video, 공간·3D·embodied reasoning, tool use를 통합한 multimodal agent/embodied 계열
- Accio-Lab/occamy-1.0 및 Occamy 1.0 직접 GGUF/NVFP4·양자화·포맷·경미한 파생본. Qwen3.6-35B-A3B architecture는 유지하지만 full-parameter SFT + HDPO, Marathon/Sprint expert merge, Single-Rollout Asynchronous Optimization(SAO)과 장시간 stateful co-work/tool-use 학습으로 agent 학습 방법·근본 목적이 크게 달라 별도 post-trained 계열로 판정
- knowledgator/gliformer-large-v1 및 GLiFormer v1 동일 architecture의 단순 크기·양자화·포맷·경미한 task-head 파생본. 575.6M DeBERTa 기반 layout-aware shared encoder에 inference-time label/schema 조건과 NER·classification·joint relation·nested structured extraction·embedding heads를 통합한 generalist information-extraction encoder 계열

### 2026-09-17
- XingChen-AGI/Xing4.0-29B-A4B 및 Xing4.0-29B-A4B 동일 checkpoint의 FP8·GGUF·양자화·포맷·경미한 fine-tune 파생본. 개발사 카드 기준 29B total/4B active MoE에 mHC + MLA + MTP, 64 routed experts 중 token당 4개 활성 + shared expert, 256K native context(512K 확장 가능)를 결합한 coding·reasoning·agent 계열
- zeroweight-ai/ZeroTTS 및 동일 ZeroTTS weights의 ONNX·정밀도·포맷·경미한 파생본. 202M Vietnamese streaming TTS로 MOSS-Audio-Tokenizer-Nano decoder, speaker-latent conditioning, ONNX Runtime 기반 CPU real-time generation을 핵심으로 하며 공개 repository에는 새 speaker latent를 만드는 voice encoder가 포함되지 않음

### 2026-09-19
- Edge0/Edge0-35B-A3B-preview 및 Edge0 35B A3B preview 동일 base+Recover-LoRA+prerouter checkpoint의 단순 복제·정밀도·포맷·경미한 adapter 파생본. Qwen3.6-35B-A3B 기반이지만 trained prerouter로 다음 expert routing을 예측하고 SSD expert offload와 Recover-LoRA distillation을 결합해 active memory를 전체 parameter 크기와 분리하는 edge-serving 계열로 별도 판정
- Cactus-Compute/needle3 및 Needle 3 동일 checkpoint의 단순 layer-slice·CQ2/CQ4·포맷·LoRA 병합 파생본. 기존 needle·needle2와 달리 Monarch Hadamard MLP, causal-conv GQA, engram n-gram memory, multi-lane hyper-connections, 2~20 layer deployable ladder training을 도입해 명백한 차세대 architecture로 별도 판정
- stable-ai/LimiX-2 및 LimiX-2 400M 동일 checkpoint의 단순 포맷·경미한 fine-tune 파생본. CMN(Contextual Mechanism Network)+CCMM으로 target-centric 예측에서 context-dependent joint mechanism modeling으로 전환하고 SCM synthetic pretraining을 사용하는 structured-data foundation 계열
- jinaai/jina-ocr-v1 및 동일 checkpoint의 단순 양자화·포맷·경미한 OCR fine-tune 파생본. DeepSeek-OCR backbone에 재귀 공유 K=3 FastMTP speculative decoding head와 dense verifiable-reward post-training을 결합한 OCR/document-intelligence 계열
- netease-youdao/Confucius4-R2T2 및 R2T2 동일 checkpoint의 단순 양자화·포맷·경미한 fine-tune 파생본. 기존 Confucius4-TTS와 달리 Qwen3-ASR 기반 ASR이며 stable-prefix·forced alignment·token-level segmentation과 Longest Stable Prefix 학습으로 append-only true streaming transcription을 구현한 별도 ASR 계열

### 2026-09-20
- convaiinnovations/laya 및 Laya English·multilingual·typed-decisions checkpoint 계열의 단순 양자화·포맷·경미한 task fine-tune 파생본. ModernBERT/mmBERT 기반 비생성 typed-decision 구조와 option-marker decision head, RLCD proper-scoring calibration 학습을 결합한 routing·guardrail·scoring 계열
- m-a-p/SheetSage2 및 동일 MERT-v2-FullSong 기반 checkpoint의 단순 adapter·양자화·포맷·경미한 파생본. audio를 melody·chords·beats·key·structure의 editable ABC/MIDI/annotation으로 변환하는 music transcription 계열로, 기존 YuE2 generation 계열과 근본 목적·출력이 달라 별도 판정
- XGENlabs/XGEN-JING의 현재 공개 JING-Flash-v1 bidirectional checkpoint 및 동일 weights의 단순 양자화·포맷·가속 파생본. MiniMax-H3 기반이지만 action·reference image·observation history를 조건으로 first-person video+audio를 생성하는 interactive experience/world-model 목적과 행동 입력 modality가 추가되어 별도 post-trained 계열로 판정. 향후 causal model은 실제 구조 공개 후 재판정
- Linkup-Platform/linkup-sparseup-embed-v1 및 동일 SPARSEUP checkpoint의 단순 양자화·포맷·경미한 fine-tune 파생본. LateOn lineage를 쓰지만 MLM expansion→logit shift→position top-k→max-pool→vocab folding의 learned vocabulary-sparse representation으로 retrieval 출력 구조와 index 방식이 달라 기존 mDenseOn·mLateOn과 별도 sparse-retrieval 계열로 판정
- facebook/VGGT-Omega 계열(VGGT-Omega-1B-512·1B-416-Reproduction·1B-256-Text-Alignment 포함)의 단순 정밀도·포맷·경미한 fine-tune 파생본. single dense prediction head, register aggregation/register attention, dynamic-scene·self-supervised scaling을 도입한 feed-forward 3D reconstruction 계열

### 2026-09-21
- Qwen/Qwen-Image-2.1 및 Qwen-Image-2.1 동일 weights의 단순 quantization·GGUF/FP8/NVFP4·포맷·LoRA·가속 파생본. 기존 Qwen-Image-Flash와 달리 7B 32-layer single-stream DiT, mixed-granularity attention, prefix KV cache reuse, Qwen3-VL 8B condition encoder, native RGBA VAE, unified generation/editing을 도입한 차세대 이미지 계열
- yandex/AliceAI-Foundation-80B-A3B-Base 및 동일 Foundation 80B backbone의 단순 양자화·포맷·경미한 fine-tune/adapter 파생본. 기존 AliceAI-T5와 달리 80B total/3B active decoder-only foundation model을 from scratch로 학습하고 KDA/Gated Attention hybrid + 512-expert MoE + MTP를 사용하는 별도 foundation 계열
- Mapika/decider-2b 및 decider v10 2B 동일 checkpoint의 단순 양자화·포맷·경미한 task fine-tune 파생본. Qwen3.5-2B backbone은 유지하지만 token generation을 제거한 typed one-pass probability decision interface와 proper-scoring supervised training, browser/game outcome 기반 calibration-aware RL로 생성 방식·Agent decision 목적이 크게 달라 별도 post-trained decision 계열로 판정
- cua-ai/cua-s1-forms 및 동일 checkpoint의 단순 양자화·포맷·경미한 파생본. 706,048-parameter byte-level dual 2-layer Transformer + Jev-like option-attention 구조로 GUI form fill/check/click/skip를 한 번에 scoring하는 초소형 computer-use decision 계열
- C-Tianyu/NanoJev 및 unified-games-v1 동일 checkpoint의 단순 양자화·포맷·경미한 파생본. Qwen3-0.6B backbone에 EOS representation + attention Choice head를 추가해 output-token decoding 없이 action candidate probability distribution을 반환하고 Maze/Snake/ViZDoom/Predict Position의 mixed-task decision 학습을 수행하는 별도 Agent decision 계열

### 2026-09-22
- XiaomiMiMo/MiMo-V2.6-Flash-RL을 대표로 하는 MiMo-V2.6 계열(Flash-RL·Pro-RL·공개 Distill variant 포함)의 단순 크기·양자화·GGUF/FP8·포맷·distillation 파생본. native text/image/video/audio, 1M context, mixed-domain asynchronous GRPO, Groupwise Reward Synthesis/Advantage Redistribution, MOPD2와 agent/tool serving을 결합한 omnimodal agent 계열
- inclusionAI/Realtime-Venus 계열(Realtime-Venus-Omni·Realtime-Venus-Audio 및 직접 양자화·포맷·경미한 파생본). MiniCPM-o 4.5 / Omni-Flow 기반이지만 proactive full-duplex AV interaction, interruption handling, 동일 causal timeline의 비동기 `<delegate>` tool delegation, training-free long-video memory를 통합해 interaction·agent/tool 구조가 크게 달라 별도 계열로 판정
- SupraLabs/Supra2-IMG 및 동일 checkpoint의 단순 양자화·포맷·경미한 image fine-tune 파생본. 기존 SupraLabs/Supra2-100M text 계열과 달리 from-scratch 104.1M DiT + frozen Flan-T5-Base + SD-VAE 기반 256×256 text-to-image 모델로 modality·architecture·생성 방식·근본 목적이 모두 달라 별도 계열로 판정

### 2026-09-23
- inclusionAI/Ming-Image-0.1-Design 및 동일 Design checkpoint의 단순 양자화·포맷·경미한 image fine-tune 파생본. 6B text-to-image 디자인 모델로 UI·인포그래픽·포스터·text-rich visual composition과 native RGBA 투명 배경 생성을 핵심으로 하는 Ming-Image 0.1 Design 계열
- radar-generalist/RADAR 및 RADAR/RADAR+ 동일 연구 계열의 단순 checkpoint 복제·포맷·경미한 fine-tune 파생본. 40만+ contrast-enhanced abdominal CT와 1,500만 anatomy-aware image-text pairs를 임상 보고서에서 학습한 abdominal CT generalist vision-language 계열이며 CC BY-NC-SA 4.0 연구 전용 모델

### 2026-09-24
- nvidia/Nemotron-3-Diarization 및 동일 checkpoint의 단순 양자화·포맷·경미한 fine-tune 파생본. 약 99.2M의 31-layer Transformer encoder에 AOSC + FIFO streaming cache를 결합해 최대 8화자의 streaming/offline speaker diarization을 수행하는 계열. 기존 Nemotron-3.5-ASR-Streaming·Nemotron-3-Embed와 목적·출력 구조가 달라 별도 계열로 판정
- paradigma-inc/limite-1b-violetto를 대표로 하는 Limite 1B 계열(base·base-soup·Violetto 포함)의 단순 양자화·포맷·경미한 fine-tune 파생본. 1B dense autoregressive Transformer를 300B 미만 curated tokens로 from scratch pretrain하고 SFT+RL로 competition-level mathematics에 특화한 131K-context reasoning 계열
- vamboai/morena-1.5b-base를 대표로 하는 MORENA 계열(1.5B base/instruct·0.5B mini/mini-instruct·0.2B nano 및 직접 pruning/distillation·양자화·포맷·경미한 파생본). 12개 Latin-script African languages 중심으로 from scratch 학습한 1.485B multilingual foundation 계열

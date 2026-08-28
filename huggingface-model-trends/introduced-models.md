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

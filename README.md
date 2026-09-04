<p align="center">
  <img src="assets/awesome-voice-ai-banner.svg" alt="Awesome Voice AI" width="600"/>
</p>

<p align="center">
  <a href="https://github.com/ALLBOTSIO/awesome-voice-ai/stargazers"><img src="https://img.shields.io/github/stars/ALLBOTSIO/awesome-voice-ai?style=for-the-badge&color=f5a623" alt="GitHub Stars"/></a>
  <img src="https://img.shields.io/badge/Tools-150+-blue?style=for-the-badge" alt="150+ Tools"/>
  <img src="https://img.shields.io/badge/Categories-10-green?style=for-the-badge" alt="10 Categories"/>
  <a href="https://github.com/ALLBOTSIO/awesome-voice-ai/commits/main"><img src="https://img.shields.io/github/last-commit/ALLBOTSIO/awesome-voice-ai?style=for-the-badge&color=purple" alt="Last Commit"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT License"/></a>
</p>

<p align="center">
  <strong>A curated list of voice AI tools, frameworks, platforms, and models.</strong><br/>
  <em>Voice agents, text-to-speech, speech-to-text, voice cloning, telephony, and more.</em>
</p>

<p align="center">
  <a href="#voice-agent-platforms">Voice Agents</a> · <a href="#text-to-speech">TTS</a> · <a href="#speech-to-text">STT</a> · <a href="#voice-cloning">Cloning</a> · <a href="#frameworks">Frameworks</a> · <a href="#telephony-infrastructure">Telephony</a> · <a href="CONTRIBUTING.md">Contribute</a>
</p>

---

## Why This List Exists

Voice AI is the fastest-growing segment of the AI stack in 2026. The global Voice Chat API market is projected to reach $3.5B by 2033. Platforms like Retell AI, Vapi, ElevenLabs, and LiveKit are processing billions of minutes monthly. Gartner predicts 40% of enterprise apps will feature AI agents by end of 2026.

But there's no single place to discover all the tools. This list fixes that.

---

## Contents

- [Voice Agent Platforms](#voice-agent-platforms) — Build and deploy voice AI agents
- [Text-to-Speech](#text-to-speech) — AI speech synthesis and voice generation
- [Speech-to-Text](#speech-to-text) — Transcription, recognition, and understanding
- [Voice Cloning](#voice-cloning) — Clone and generate custom voices
- [Frameworks & SDKs](#frameworks--sdks) — Open-source voice AI frameworks
- [Telephony Infrastructure](#telephony-infrastructure) — SIP, phone numbers, call routing
- [Voice Analytics](#voice-analytics) — Call analysis, sentiment, and QA
- [Voice Commerce](#voice-commerce) — Voice-activated shopping and payments
- [Voice Platforms & Assistants](#voice-platforms--assistants) — Alexa, Siri, Google ecosystem
- [MCP Servers for Voice](#mcp-servers-for-voice) — Model Context Protocol voice integrations

---

## Voice Agent Platforms

Platforms for building, deploying, and managing AI voice agents.

| Tool | Type | Description | Highlights |
|------|------|-------------|------------|
| **[Retell AI](https://www.retellai.com/)** | Commercial | Developer-friendly voice agent platform with drag-and-drop builder | MCP support, Twilio integration, multilingual, real-time workflows |
| **[Vapi](https://vapi.ai/)** | Commercial | Provider-agnostic voice AI orchestration layer | 62M monthly calls, 14+ providers, $0.05/min, 99.99% SLA |
| **[ElevenLabs Conversational AI](https://elevenlabs.io/)** | Commercial | Voice agent platform with industry-leading voice quality | Sub-100ms latency, 11,000+ voices, 70+ languages |
| **[Bland AI](https://www.bland.ai/)** | Commercial | High-volume outbound voice agent platform | Purpose-built for sales campaigns, enterprise telephony |
| **[Dvaarik](https://www.dvaarik.com/)** | Commercial | AI receptionist for voice, WhatsApp, Instagram, and web chat | White-label partner console, 22 scheduled Indian languages plus English, bookings and payment links |
| **[LiveKit Agents](https://github.com/livekit/agents)** | Open Source | Real-time voice agent framework with WebRTC | Fully open source, plugin architecture, MCP support |
| **[Hermes](https://www.buildwithhermes.com/)** | Commercial | Operating platform for AI voice agencies, white-label under the agency brand | Built-in CRM, campaign engine, per-client workspaces, usage billing, from $149/mo |
| **[Synthflow](https://synthflow.ai/)** | Commercial | No-code voice agent builder | White-label, 200+ integrations, appointment booking |
| **[Cognigy](https://www.cognigy.com/)** | Enterprise | Enterprise conversational AI platform | Omnichannel, contact center integration, 100+ languages |
| **[Lindy AI](https://www.lindy.ai/)** | Commercial | AI assistant with voice agent capabilities | Multi-step workflows, triggers, CRM integration |
| **[Air AI](https://www.air.ai/)** | Commercial | Autonomous voice agent for sales and customer service | 40+ minute conversations, calendar booking |
| **[Voiceflow](https://www.voiceflow.com/)** | Commercial | Collaborative voice & chat AI agent builder | Visual builder, team collaboration, multi-channel |
| **[Hamming AI](https://hamming.ai/)** | Commercial | Voice agent testing and evaluation platform | Automated QA, regression testing, performance scoring |
| **[Inworld AI](https://inworld.ai/)** | Commercial | Character-driven voice AI for games and enterprise | Real-time animation, emotional intelligence, gaming SDK |
| **[PlayAI](https://play.ai/)** | Commercial | Voice agent platform with ultra-realistic voices | Sub-200ms latency, voice cloning, custom models |
| **[Thoughtly](https://www.thoughtly.io/)** | Commercial | Enterprise voice agent with human-like conversations | No-code builder, CRM sync, call analytics |
| **[DialogBrain](https://dialogbrain.com/voice/api)** | Commercial | Multi-channel voice agents — calls on Telegram, WhatsApp, Google Meet, and web widgets | Real-time call translation, lipsync avatars, 244+ MCP tools, per-tenant Postgres |

> [Detailed comparison →](categories/voice-agents/)

---

## Text-to-Speech

AI-powered speech synthesis — from real-time voices to studio-quality narration.

### Commercial

| Tool | Latency | Languages | Highlights |
|------|---------|-----------|------------|
| **[ElevenLabs](https://elevenlabs.io/)** | <100ms | 70+ | Industry-leading quality, voice cloning, 11k+ voices |
| **[Play.ht](https://play.ht/)** | <200ms | 60+ | Ultra-realistic, voice cloning, API + widget |
| **[Deepgram Aura](https://deepgram.com/aura)** | <100ms | 10+ | Optimized for voice agents, streaming, low cost |
| **[Amazon Polly](https://aws.amazon.com/polly/)** | <200ms | 30+ | AWS integration, SSML, neural voices |
| **[Google Cloud TTS](https://cloud.google.com/text-to-speech)** | <200ms | 40+ | WaveNet and Neural2 voices, Studio voices |
| **[Gradium](https://gradium.ai/)** | <160ms | 5 | Built for real-time voice agents, streaming WebSocket, instant voice cloning |
| **[Azure Speech](https://azure.microsoft.com/en-us/products/ai-services/text-to-speech)** | <200ms | 100+ | Custom Neural Voice, SSML, avatar support |
| **[Resemble AI](https://www.resemble.ai/)** | <200ms | 25+ | Real-time cloning, emotion control, API |
| **[Cartesia](https://cartesia.ai/)** | <80ms | 10+ | Sonic model, ultra-low latency streaming |
| **[Fish Audio](https://fish.audio/)** | <150ms | 10+ | Open-weight models, voice cloning, multilingual |
| **[CharaVox](https://charavox.com/)** | — | 6 | Character voices, voice cloning, role-specific pages (VoxCPM) |

### Open Source

| Tool | Stars | License | Highlights |
|------|:-----:|---------|------------|
| **[Coqui XTTS](https://github.com/coqui-ai/TTS)** | 36k+ | MPL 2.0 | Voice cloning with 6s sample, multilingual, most downloaded on HF |
| **[Bark](https://github.com/suno-ai/bark)** | 37k+ | MIT | Non-verbal sounds, laughter, music, multi-speaker |
| **[KittenTTS](https://github.com/KittenML/KittenTTS)** | 14k+ | Apache 2.0 | Lightweight ONNX models, CPU inference, built-in voices |
| **[Piper](https://github.com/rhasspy/piper)** | 7k+ | MIT | Lightweight, runs on Raspberry Pi, 20+ languages |
| **[StyleTTS2](https://github.com/yl4579/StyleTTS2)** | 5k+ | MIT | Studio-quality, style diffusion, human-level naturalness |
| **[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)** | 40k+ | MIT | 1-min voice data training, few-shot cloning |
| **[OpenVoice](https://github.com/myshell-ai/OpenVoice)** | 30k+ | MIT | Instant voice cloning, emotion/accent control |
| **[MeloTTS](https://github.com/myshell-ai/MeloTTS)** | 5k+ | MIT | High-quality multi-language, real-time CPU inference |
| **[Parler-TTS](https://github.com/huggingface/parler-tts)** | 4k+ | Apache 2.0 | Text-described voice control, Hugging Face native |
| **[MetaVoice](https://github.com/metavoiceio/metavoice-src)** | 3k+ | Apache 2.0 | Finetuning in 1 minute, emotional speech |
| **[OpenEdAI Speech](https://github.com/matatonic/openedai-speech)** | 2k+ | AGPL | OpenAI API-compatible TTS server, drop-in replacement |
| **[AllTalk TTS](https://github.com/erew123/alltalk_tts)** | 2k+ | AGPL | Multi-engine TTS server, text-generation-webui support |

> [Full TTS comparison →](categories/text-to-speech/)

---

## Speech-to-Text

Transcription, real-time recognition, and audio understanding.

### Commercial APIs

| Tool | WER | Languages | Highlights |
|------|-----|-----------|------------|
| **[Deepgram Nova-3](https://deepgram.com/)** | <8% | 40+ | Fastest streaming, $0.0043/min, voice agent optimized |
| **[AssemblyAI (Slam-1)](https://www.assemblyai.com/)** | <10% | 20+ | Speaker diarization, sentiment, content moderation |
| **[Gladia](https://www.gladia.io/)** | <10% | 100+ | Real-time code-switching, zero-shot language detection |
| **[Speechmatics](https://www.speechmatics.com/)** | <10% | 50+ | On-prem option, real-time, batch, translation |
| **[Rev AI](https://www.rev.ai/)** | <5% | 30+ | Human-verified option, 99% accuracy, legal/medical |
| **[Google Cloud STT](https://cloud.google.com/speech-to-text)** | <12% | 125+ | Chirp model, medical dictation, streaming |
| **[Gradium](https://gradium.ai/)** | <3% | 5 | Semantic VAD turn detection, real-time streaming, voice agent optimized |
| **[Azure Speech](https://azure.microsoft.com/en-us/products/ai-services/speech-to-text)** | <10% | 100+ | Custom speech models, real-time, batch |
| **[Amazon Transcribe](https://aws.amazon.com/transcribe/)** | <12% | 100+ | Medical, call analytics, volume discounts to 67% |

### Open Source

| Tool | Stars | License | Highlights |
|------|:-----:|---------|------------|
| **[AI Dictation](https://github.com/writingmate/aidictation)** | 33 | MIT | Cross-platform voice typing with offline recognition on supported devices |
| **[Whisper](https://github.com/openai/whisper)** | 75k+ | MIT | The standard, 99+ languages, robust in noise |
| **[Faster-Whisper](https://github.com/SYSTRAN/faster-whisper)** | 13k+ | MIT | 4x faster than Whisper, CTranslate2 backend |
| **[Whisper.cpp](https://github.com/ggerganov/whisper.cpp)** | 37k+ | MIT | C/C++ port, runs on CPU/phone/RPi, WASM support |
| **[Vosk](https://github.com/alphacep/vosk-api)** | 8k+ | Apache 2.0 | Offline, lightweight, mobile/embedded, 20+ languages |
| **[NeMo (NVIDIA)](https://github.com/NVIDIA/NeMo)** | 12k+ | Apache 2.0 | Enterprise-grade, Conformer/Canary models, GPU optimized |
| **[Whisper-Streaming](https://github.com/ufal/whisper_streaming)** | 2k+ | MIT | Real-time streaming Whisper with local agreement |
| **[Insanely-Fast-Whisper](https://github.com/Vaibhavs10/insanely-fast-whisper)** | 7k+ | MIT | 150x faster with speculative decoding + batching |
| **[Off Grid AI Desktop](https://github.com/off-grid-ai/off-grid-ai-desktop)** | 33 | AGPL-3.0 | On-device voice dictation and transcription via Whisper.cpp, fully offline on Mac |

> [Full STT comparison →](categories/speech-to-text/)

---

## Voice Cloning

Clone voices from short audio samples for custom TTS.

| Tool | Stars | Type | Highlights |
|------|:-----:|------|------------|
| **[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)** | 40k+ | Open Source | 1-min data training, few-shot, singing + speech |
| **[OpenVoice](https://github.com/myshell-ai/OpenVoice)** | 30k+ | Open Source | Instant cloning, tone/emotion/accent control |
| **[RVC (Retrieval-based VC)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)** | 25k+ | Open Source | Real-time conversion, music community favorite |
| **[Coqui XTTS](https://github.com/coqui-ai/TTS)** | 36k+ | Open Source | 6-second sample cloning, 17 languages |
| **[Bark Voice Clone](https://github.com/serp-ai/bark-with-voice-clone)** | 3k+ | Open Source | Bark + voice cloning, easy speaker prompts |
| **[ElevenLabs](https://elevenlabs.io/)** | — | Commercial | Professional voice cloning, 29 languages |
| **[Resemble AI](https://www.resemble.ai/)** | — | Commercial | Real-time cloning, emotion control, watermarking |
| **[Play.ht](https://play.ht/)** | — | Commercial | Instant cloning, cross-lingual, API access |

> [Full voice cloning comparison →](categories/voice-cloning/)

---

## Frameworks & SDKs

Open-source frameworks for building voice AI applications.

| Framework | Stars | Language | Description |
|-----------|:-----:|----------|-------------|
| **[Pipecat](https://github.com/pipecat-ai/pipecat)** | 8k+ | Python | Voice + multimodal conversational AI by Daily. STT→LLM→TTS pipelines |
| **[LiveKit Agents](https://github.com/livekit/agents)** | 5k+ | Python | Real-time voice agents with WebRTC, MCP support, plugin architecture |
| **[Vocode](https://github.com/vocodedev/vocode-core)** | 3k+ | Python | Low-level modular voice agent toolkit, telephony integration |
| **[Bolna](https://github.com/bolna-ai/bolna)** | 2k+ | Python | Production voice agents with <1s latency, Twilio/Plivo ready |
| **[OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime)** | — | Multi | Native multimodal streaming, voice-to-voice, function calling |
| **[Nimble Pipecat](https://github.com/daily-co/nimble-pipecat)** | 500+ | Python | Lightweight voice agent framework by Daily |
| **[NVIDIA Voice Agent](https://github.com/NVIDIA/voice-agent-examples)** | 500+ | Python | Pipecat-based examples for real-time voice agents |
| **[MCP Voice Assistant](https://github.com/mcp-use/mcp-use-voice-assistant)** | 300+ | Python | Voice assistant powered by MCP, Whisper + ElevenLabs |
| **[Gradbot](https://github.com/gradium-ai/gradbot)** | 100+ | Rust | Open-source voice agent framework built on Gradium TTS/STT APIs |

> [Full framework comparison →](categories/frameworks/)

---

## Telephony Infrastructure

SIP trunking, phone numbers, and call routing for voice AI agents.

| Provider | Type | Highlights |
|----------|------|------------|
| **[Twilio](https://www.twilio.com/voice)** | Commercial | Largest ecosystem, best docs, global coverage, $0.013/min |
| **[Telnyx](https://telnyx.com/)** | Commercial | Private IP network, lowest latency, owns infrastructure |
| **[Plivo](https://www.plivo.com/)** | Commercial | Single-stack (owns telco + AI), 99.99% uptime, HIPAA |
| **[Vonage](https://www.vonage.com/)** | Commercial | Enterprise-grade, video + voice, conversation API |
| **[SignalWire](https://signalwire.com/)** | Commercial | FreeSWITCH creators, AI-native, programmable telco |
| **[Bandwidth](https://www.bandwidth.com/)** | Commercial | Direct carrier, 911/E911, enterprise focus |

> [Full telephony comparison →](categories/telephony/)

---

## Voice Analytics

Call analysis, conversation intelligence, and quality assurance.

| Tool | Type | Description |
|------|------|-------------|
| **[Gong](https://www.gong.io/)** | Commercial | Revenue intelligence, call recording, deal insights |
| **[Chorus.ai](https://www.chorus.ai/)** | Commercial | Conversation intelligence for sales teams (ZoomInfo) |
| **[Observe.AI](https://www.observe.ai/)** | Commercial | Contact center AI, real-time agent assist, QA automation |
| **[Callrail](https://www.callrail.com/)** | Commercial | Call tracking, conversation analytics, lead attribution |
| **[Symbl.ai](https://symbl.ai/)** | Commercial | Real-time conversation intelligence API, sentiment, topics |
| **[Hamming AI](https://hamming.ai/)** | Commercial | Voice agent testing platform, automated regression testing |

> [Full analytics comparison →](categories/voice-analytics/)

---

## Voice Commerce

Voice-activated shopping, ordering, and payments.

| Tool | Type | Description |
|------|------|-------------|
| **[Amazon Alexa Shopping](https://developer.amazon.com/)** | Platform | Voice ordering through Alexa ecosystem |
| **[Google Shopping Actions](https://shopping.google.com/)** | Platform | Voice commerce through Google Assistant |
| **[Ringly.io](https://www.ringly.io/)** | Commercial | AI phone agent for e-commerce, abandoned cart recovery |
| **[PolyAI](https://poly.ai/)** | Commercial | Enterprise voice assistants for ordering and booking |
| **[SoundHound](https://www.soundhound.com/)** | Commercial | Voice AI for restaurants, automotive, hospitality |

> [Full voice commerce comparison →](categories/voice-commerce/)

---

## Voice Platforms & Assistants

Major voice assistant ecosystems and their developer tools.

| Platform | Type | Developer Resources |
|----------|------|---------------------|
| **[Amazon Alexa](https://developer.amazon.com/alexa)** | Platform | Skills Kit, Voice Service, Smart Home API |
| **[Google Assistant](https://developers.google.com/assistant)** | Platform | Actions, Conversational Actions, Home APIs |
| **[Apple Siri / SiriKit](https://developer.apple.com/siri/)** | Platform | Intents, Shortcuts, App Intents framework |
| **[Samsung Bixby](https://bixbydevelopers.com/)** | Platform | Capsules, voice actions, SmartThings |
| **[OpenClaw](https://github.com/nicbarker/openclaw)** | Open Source | Personal AI assistant, 50+ integrations, 210k+ stars |
| **[Open WebUI](https://github.com/open-webui/open-webui)** | Open Source | Self-hosted AI with voice, 124k+ stars, offline capable |
| **[Home Assistant Voice](https://www.home-assistant.io/voice_control/)** | Open Source | Privacy-focused voice control for smart home |

> [Full platform comparison →](categories/voice-platforms/)

---

## MCP Servers for Voice

Model Context Protocol (MCP) servers relevant to voice AI applications.

| Server | Description | Voice Use Case |
|--------|-------------|----------------|
| **[Retell AI MCP](https://github.com/nichochar/retell-mcp-server)** | Manage Retell AI voice agents via MCP | Build and deploy voice agents from any MCP client |
| **[ElevenLabs MCP](https://github.com/elevenlabs/elevenlabs-mcp)** | Text-to-speech and voice cloning via MCP | Generate speech from any AI assistant |
| **[Voice Call MCP](https://github.com/popcornspace/voice-call-mcp-server)** | Initiate voice calls via Twilio + OpenAI | AI-initiated phone calls |
| **[Whisper MCP](https://github.com/nichochar/brave-search-mcp)** | Speech-to-text transcription via MCP | Voice input for any MCP client |
| **[Home Assistant MCP](https://github.com/homeassistant-ai/ha-mcp)** | Smart home control via MCP | Voice-controlled smart home |
| **[Spotify MCP](https://github.com/marcelmarais/spotify-mcp-server)** | Music playback and search via MCP | "Play my playlist" from any voice agent |
| **[DialogBrain MCP](https://docs.dialogbrain.com/)** | Full agent platform via MCP at api.dialogbrain.com/mcp — dispatch calls, translators, agents | Launch a voice call on Telegram/WhatsApp/Meet from any MCP client |

> See **[Alexa-MCPs](https://github.com/ALLBOTSIO/Alexa-MCPs)** for the full 200-server directory of MCP servers optimized for voice assistants.

---

## How Voice AI Architecture Works

```mermaid
graph TD
    A[🗣️ User Speech] --> B[Speech-to-Text<br/>Whisper / Deepgram / AssemblyAI]
    B --> C[AI Agent / LLM<br/>GPT-4o / Claude / Gemini]
    C --> D{Tool Calls}
    D --> E[MCP Servers<br/>Calendar, CRM, Search]
    D --> F[APIs<br/>Twilio, Stripe, etc.]
    E --> C
    F --> C
    C --> G[Text-to-Speech<br/>ElevenLabs / Cartesia / Bark]
    G --> H[🔊 Audio Response]

    style B fill:#4A90D9,stroke:#333,color:#fff
    style C fill:#FF9900,stroke:#333,color:#fff
    style G fill:#28a745,stroke:#333,color:#fff
```

---

## Market Landscape (2026)

```mermaid
pie title Voice AI Market Segments
    "Voice Agent Platforms" : 30
    "Text-to-Speech" : 20
    "Speech-to-Text" : 18
    "Telephony/SIP" : 12
    "Voice Cloning" : 8
    "Analytics" : 5
    "Commerce" : 4
    "Frameworks" : 3
```

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. TL;DR:

1. Fork → Add tool to appropriate section → Submit PR
2. Or [open an issue](https://github.com/ALLBOTSIO/awesome-voice-ai/issues/new?template=submit-tool.yml) to suggest a tool

### Criteria

- Must be a real, working product or actively maintained open-source project
- Must be relevant to voice AI (not general AI/ML)
- Include a brief, factual description — no marketing copy

---

## Star History

If this list helps you, star it so others can find it too.

<a href="https://star-history.com/#ALLBOTSIO/awesome-voice-ai&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ALLBOTSIO/awesome-voice-ai&type=Date&theme=dark" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ALLBOTSIO/awesome-voice-ai&type=Date" width="600" />
  </picture>
</a>

---

## Related Lists

- **[Alexa-MCPs](https://github.com/ALLBOTSIO/Alexa-MCPs)** — 200 MCP servers for voice assistants
- **[awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)** — 84k+ star MCP directory
- **[awesome-ai-agents-2026](https://github.com/caramaschiHG/awesome-ai-agents-2026)** — 300+ AI agent resources
- **[SaaSCity](https://saascity.io)** — SaaS & AI product launch directory (voice AI tools welcome)

---

## License

[MIT](LICENSE) — AI Venture Holdings LLC

<p align="center">
  Built by <a href="https://allbots.io">ALLBOTS.io</a> · A portfolio company of <strong>AI Venture Holdings LLC</strong><br/>
  <sub>⭐ Star this repo to stay updated as new voice AI tools launch</sub>
</p>

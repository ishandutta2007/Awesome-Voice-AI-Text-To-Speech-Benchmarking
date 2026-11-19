# Awesome-Voice-AI-Text-To-Speech-Benchmarking

# Top Voice AI & Text-to-Speech Benchmarking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Neural Text-to-Speech (TTS), Zero-Shot Voice Cloning, TTS Arena Evaluation, MOS/WER Benchmarking & Real-Time Speech Synthesis*  
**Last updated: November 2026**

This repository (`Awesome-Voice-AI-Text-To-Speech-Benchmarking`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Voice AI & Text-to-Speech Benchmarking** — Top Voice AI Text To Speech Benchmarking (Opensource) 🌟 Star if you like it! 🌟. These tools synthesize expressive human-like speech, perform zero-shot voice cloning, evaluate intelligibility (WER/CER) and speaker similarity, host blind ELO TTS arenas, and deploy ultra-low-latency local TTS engines.

**Examples** include ElevenLabs, PlayHT, WellSaid Labs, Murf.ai, Resemble AI, Speechify, LOVO AI, Amazon Polly, Google Cloud Text-to-Speech, Azure AI Speech TTS, and `huggingface/open-tts-leaderboard` (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for open-weight TTS foundation models, lightweight edge/CPU speech synthesis, zero-shot voice cloning engines, and objective/human TTS evaluation harnesses — ideal for speech researchers, voice agent builders, AI engineers, and accessibility developers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ElevenLabs](https://elevenlabs.io)**  
  Leading generative voice AI platform offering ultra-low-latency Flash/Turbo TTS models, instant and professional voice cloning, dubbing studio, and conversational voice agents.

- **[PlayHT](https://play.ht)**  
  Cloud AI voice synthesis and cloning platform featuring real-time streaming APIs, emotional voice style controls, and multi-lingual voice generation.

- **[WellSaid Labs](https://wellsaidlabs.com)**  
  Enterprise text-to-speech studio providing natural studio-grade voice avatars, phonetic pronunciation libraries, and team script collaboration for corporate training and media.

- **[Murf.ai](https://murf.ai)**  
  Cloud AI voiceover studio enabling creators to generate studio-quality narration with pitch, pause, emphasis, and video-sync timeline controls.

- **[Resemble AI](https://resemble.ai)**  
  Enterprise generative voice platform combining real-time speech-to-speech voice cloning, emotional inflection APIs, and PerTh audio watermarking/deepfake detection.

- **[Speechify](https://speechify.com)**  
  Consumer and API text-to-speech platform turning PDFs, articles, and books into natural high-speed audio across mobile, browser, and desktop.

- **[LOVO AI (Genny)](https://lovo.ai)**  
  Cloud AI voice generator and video editing suite offering 500+ expressive voices across 100+ languages for marketing, e-learning, and content production.

- **[Amazon Polly](https://amazon.com)**  
  Managed AWS cloud text-to-speech service supporting Neural, Long-Form, and Generative voices with SSML controls and real-time audio streaming.

- **[Google Cloud Text-to-Speech (Chirp 3 / Journey)](https://google.com)**  
  Enterprise Google Cloud speech synthesis API offering Chirp 3 HD voices, instant custom voice creation, and low-latency streaming synthesis.

- **[Microsoft Azure AI Speech (TTS)](https://microsoft.com)**  
  Cloud speech synthesis service providing neural HD voices, Custom Neural Voice training, SSML prosody control, and viseme facial animation events.

- **[Cartesia (Sonic)](https://cartesia.ai)**  
  Ultra-low-latency state-space model (SSM) voice AI cloud delivering sub-90ms time-to-first-audio streaming synthesis for real-time voice agents.

- **[Artificial Analysis Speech Arena](https://artificialanalysis.ai)**  
  Independent cloud benchmarking leaderboard comparing commercial and open-source TTS models on blind human ELO preference, latency, and price.

## Open-Source GitHub Projects

- **[Open TTS Leaderboard & TTS Arena (huggingface/open-tts-leaderboard)](https://github.com)**  
  Official Hugging Face open-source evaluation benchmark and blind ELO leaderboard ranking open-weight and proprietary TTS models on naturalness, intelligibility, and prosody.

- **[Kokoro-82M & Kokoro-ONNX (hexgrad/kokoro)](https://github.com)**  
  Apache 2.0 licensed, 82-million-parameter open-weight TTS model delivering top-tier naturalness at a fraction of the compute cost, running faster than real time on CPU and GPU.

- **[F5-TTS (SWivid/F5-TTS)](https://github.com)**  
  Diffusion Transformer (DiT) and Flow-Matching open-source TTS model featuring zero-shot voice cloning, multi-speaker dialogue generation, and fast inference.

- **[CosyVoice & CosyVoice 2 (FunAudioLLM/CosyVoice)](https://github.com)**  
  Alibaba's Apache 2.0 open-source multilingual large voice generation model supporting zero-shot voice cloning, cross-lingual synthesis, instruction-controlled emotion, and streaming output.

- **[Fish Speech (fishaudio/fish-speech)](https://github.com)**  
  Leading open-source dual-autoregressive Transformer TTS architecture capable of zero-shot and few-shot voice cloning across English, Chinese, Japanese, and European languages without phoneme dependencies.

- **[Chatterbox (resemble-ai/chatterbox)](https://github.com)**  
  MIT-licensed open-source production-grade TTS model by Resemble AI featuring zero-shot voice cloning, emotion exaggeration control, and built-in Perth perceptual watermarking.

- **[Orpheus TTS (canopyai/Orpheus-TTS)](https://github.com)**  
  Apache 2.0 open-source Llama-based speech-LLM generating highly expressive, human-like speech with inline emotion tags (`<laugh>`, `<sigh>`, `<gasp>`) and ~100ms streaming latency.

- **[Sesame CSM-1B (SesameAILabs/csm)](https://github.com)**  
  Open-source Conversational Speech Model generating context-aware, natural conversational prosody conditioned on preceding dialogue history and speaker turns.

- **[Dia-1.6B (nari-labs/dia)](https://github.com)**  
  Apache 2.0 open-weight 1.6B parameter dialogue-first TTS model generating realistic multi-speaker conversations and non-verbal audio cues directly from transcript tags.

- **[Spark-TTS (SparkAudio/Spark-TTS)](https://github.com)**  
  Open-source single-stream BiCodec speech synthesis system powered by Qwen2.5 enabling fine-grained attribute control (gender, pitch, speaking rate) and zero-shot cloning.

- **[OuteTTS (edwko/OuteTTS)](https://github.com)**  
  Pure language-modeling open-source TTS system compatible with `llama.cpp` and GGUF quantization for local CPU/GPU deployment and zero-shot speaker cloning.

- **[Piper TTS (rhasspy/piper)](https://github.com)**  
  Fast, local, privacy-first open-source neural text-to-speech system built on VITS and ONNX Runtime, optimized for Raspberry Pi, Home Assistant, and edge devices.

- **[Coqui XTTS-v2 & Idiap Coqui-TTS (idiap/coqui-ai-TTS)](https://github.com)**  
  Community-maintained continuation of the renowned Coqui TTS toolkit supporting XTTS-v2 cross-lingual voice cloning across 17 languages with sub-200ms streaming.

- **[MeloTTS (myshell-ai/MeloTTS)](https://github.com)**  
  High-quality, lightweight open-source multilingual TTS library by MyShell supporting English, Spanish, French, Chinese, Japanese, and Korean with real-time CPU inference.

- **[OpenVoice & OpenVoice V2 (myshell-ai/OpenVoice)](https://github.com)**  
  MIT-licensed instant voice cloning engine providing granular control over emotion, accent, rhythm, pauses, and intonation across multiple languages.

- **[StyleTTS 2 (yl4579/StyleTTS2)](https://github.com)**  
  Foundational open-source diffusion-based TTS architecture achieving human-level naturalness and expressive style transfer via adversarial training with large speech language models.

- **[Bark (suno-ai/bark)](https://github.com)**  
  Transformer-based open-source text-to-audio model by Suno generating realistic multilingual speech alongside laughter, sighs, music, and sound effects.

- **[ChatTTS (2noise/ChatTTS)](https://github.com)**  
  Open-source generative speech model specifically optimized for conversational dialogue scenarios with fine-grained control over laughter, pauses, and interjections.

- **[Parler-TTS (huggingface/parler-tts)](https://github.com)**  
  Lightweight open-source TTS model by Hugging Face that generates high-quality speech controlled via natural-language descriptions of speaker gender, pitch, cadence, and recording environment.

- **[Moshi / Kyutai Delayed Streams TTS (kyutai-labs/moshi)](https://github.com)**  
  Open-source full-duplex speech-text foundation model and low-latency streaming TTS engine built in Rust and PyTorch.

- **[Seed-TTS-Eval (BytedanceSpeech/seed-tts-eval)](https://github.com)**  
  Standardized open-source TTS evaluation benchmark measuring Word Error Rate (WER) via Whisper/Paraformer ASR and Speaker Similarity (SIM) via WavLM across hard test sets.

- **[UTMOSv2 & SpeechMOS (sarulab-speech/UTMOSv2)](https://github.com)**  
  Open-source neural Mean Opinion Score (MOS) predictor estimating human perceptual speech quality automatically without requiring expensive human listening panels.

# 🌌 GenAI Universe — Architecture Explorer

> **An interactive deep-dive into the architectures powering modern generative AI.**  
> Animated diagrams. Live API demos. 20+ architectures. One file.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Single File](https://img.shields.io/badge/deployment-single%20HTML%20file-brightgreen)](#)
[![Architectures](https://img.shields.io/badge/architectures-20%2B-purple)](#architectures)
[![Categories](https://img.shields.io/badge/categories-8-orange)](#categories)

---

## ✨ Overview

**GenAI Universe** is a standalone, zero-dependency interactive explorer for generative AI model architectures — from the foundational Transformer to the latest 3D Gaussian Splatting. Each architecture is brought to life with animated canvas diagrams, interactive node tooltips, step-by-step walkthroughs, and a live Anthropic API demo.

Inspired by [Transformer Explainer](https://poloclub.github.io/transformer-explainer/), but expanded to cover the full modern generative AI landscape across **8 modalities** and **20+ architectures**.

**→ [Open `genai-universe.html`](genai-universe.html) in any modern browser. No install. No server.**

---

## 🎬 Features

| Feature | Description |
|---|---|
| 🖼️ **Animated Diagrams** | Canvas-rendered architecture graphs with real-time data-flow particles |
| 🖱️ **Interactive Nodes** | Hover any node for detailed descriptions and mathematical formulas |
| 🎞️ **Step-by-Step Mode** | Auto-play walkthroughs of information flow through each architecture |
| ⚡ **Live API Demo** | Stream real tokens from Claude via the Anthropic API (API key required) |
| 🌊 **Diffusion Demo** | Watch a noise signal denoise step-by-step in real time |
| 📐 **Math & Stats** | Key equations, parameter counts, and model comparisons per architecture |
| 🌑 **Deep Space UI** | Dark glassmorphic theme with Syne + JetBrains Mono typography |

---

## 🗂️ Architectures

### 📝 Text Generation
| Architecture | Representative Models |
|---|---|
| Decoder-only Transformer | GPT-4o, LLaMA 3, Claude 3.5, Gemini 1.5, Mistral, DeepSeek V3 |
| Encoder-Decoder | T5, BART, mT5 |
| Encoder-only (BERT) | BERT, RoBERTa, DeBERTa |
| State Space Model (Mamba) | Mamba-2, Jamba, RWKV |

### 🖼️ Multimodal Text
| Architecture | Representative Models |
|---|---|
| Contrastive Vision-Language (CLIP) | CLIP, SigLIP, ALIGN |
| Vision-Language Model | LLaVA, Flamingo, InternVL |

### 🌐 Omni Models
| Architecture | Representative Models |
|---|---|
| Any-to-Any Unified | GPT-4o, Gemini 2.0, Grok 1.5 |

### 🎨 Image Generation
| Architecture | Representative Models |
|---|---|
| DDPM / DDIM | DDPM, DDIM |
| Latent Diffusion (LDM) | Stable Diffusion 3, DALL-E 3 |
| Diffusion Transformer (DiT) | FLUX.1, Sora (image), PixArt-α |
| Generative Adversarial Network | StyleGAN3, BigGAN |
| Variational Autoencoder | VQ-VAE-2, DALL-E (discrete VAE) |

### 🎬 Video Generation
| Architecture | Representative Models |
|---|---|
| Video DiT | Sora, CogVideoX, OpenSora |
| Autoregressive Video | VideoGPT, Phenaki |

### 🔊 Audio Generation
| Architecture | Representative Models |
|---|---|
| WaveNet (Dilated CNN) | WaveNet, WaveGrad |
| Hierarchical LM (AudioLM) | AudioLM, MusicLM, SoundStorm |
| Flow Matching | Voicebox, E2 TTS, Matcha-TTS |

### 🎙️ Real-time Conversation
| Architecture | Representative Models |
|---|---|
| End-to-end Speech (GPT-4o style) | GPT-4o Voice, Moshi |
| Neural TTS (VITS2) | VITS2, NaturalSpeech3 |

### 📦 3D Generation
| Architecture | Representative Models |
|---|---|
| NeRF / Instant-NGP | NeRF, Instant-NGP, Zip-NeRF |
| 3D Gaussian Splatting | 3DGS, Mip-Splatting, GaussianAvatars |
| Triplane Diffusion | Shap-E, LRM, Zero123++ |

---

## 🚀 Getting Started

### 1. Clone & Open

```bash
git clone https://github.com/rikunarita/genai-universe.git
cd genai-universe
open genai-universe.html   # macOS
# or simply double-click the file in your file explorer
```

### 2. (Optional) Enable Live API Demo

To stream real tokens from Claude, add your Anthropic API key when prompted in the app's **Live Demo** panel. Your key is never stored — it lives only in memory for the session.

> ⚠️ **CORS note**: The live API demo requires running the file from a local server, not `file://`. Use:
> ```bash
> python3 -m http.server 8080
> # then open http://localhost:8080/genai-universe.html
> ```

---

## 🧱 Tech Stack

- **Pure HTML/CSS/JS** — zero frameworks, zero build step, zero dependencies
- **Canvas 2D API** — custom renderer for all architecture diagrams and animations
- **Anthropic Messages API** — streaming completions via `claude-sonnet-4-20250514`
- **Google Fonts** — Syne (display), DM Sans (body), JetBrains Mono (code)

---

## 📄 License

MIT — free to use, modify, and redistribute. Attribution appreciated.

---

---
---

# 🌌 GenAI Universe — アーキテクチャ・エクスプローラー

> **現代の生成AIを動かすアーキテクチャを、インタラクティブに深く探索する。**  
> アニメーション図解。ライブAPIデモ。20以上のアーキテクチャ。1ファイル完結。

---

## ✨ 概要

**GenAI Universe** は、生成AIモデルアーキテクチャを探索するための、インストール不要・依存ゼロのインタラクティブWebアプリです。基礎となるTransformerから最新の3D Gaussian Splattingまで、各アーキテクチャをアニメーション付きキャンバス図、インタラクティブなノードツールチップ、ステップ・バイ・ステップの解説、そしてAnthropicのライブAPIデモで体感できます。

[Transformer Explainer](https://poloclub.github.io/transformer-explainer/) にインスパイアされつつ、**8モダリティ・20以上のアーキテクチャ**へと大幅に拡張しています。

**→ [`genai-universe.html`](genai-universe.html) をモダンブラウザで開くだけ。インストール不要。サーバー不要。**

---

## 🎬 主な機能

| 機能 | 説明 |
|---|---|
| 🖼️ **アニメーション図解** | データフローをリアルタイム粒子で可視化するCanvas描画アーキテクチャグラフ |
| 🖱️ **インタラクティブノード** | ノードにホバーすると詳細説明と数式を表示 |
| 🎞️ **ステップ再生モード** | 各アーキテクチャの情報伝播を自動ウォークスルー |
| ⚡ **ライブAPIデモ** | AnthropicのAPIを介してClaudeからトークンをリアルタイムストリーミング（APIキー必要） |
| 🌊 **拡散モデルデモ** | ノイズが段階的に除去される様子をリアルタイムで観察 |
| 📐 **数式 & 統計情報** | アーキテクチャごとの主要な数式、パラメータ数、モデル比較 |
| 🌑 **Deep Space UI** | Syne + JetBrains Monoを使ったダークグラスモーフィックテーマ |

---

## 🗂️ 収録アーキテクチャ

### 📝 テキスト生成
| アーキテクチャ | 代表的なモデル |
|---|---|
| デコーダのみのTransformer | GPT-4o、LLaMA 3、Claude 3.5、Gemini 1.5、Mistral、DeepSeek V3 |
| エンコーダ-デコーダ | T5、BART、mT5 |
| エンコーダのみ（BERT系） | BERT、RoBERTa、DeBERTa |
| 状態空間モデル（Mamba） | Mamba-2、Jamba、RWKV |

### 🖼️ マルチモーダルテキスト
| アーキテクチャ | 代表的なモデル |
|---|---|
| コントラスティブ視覚言語（CLIP） | CLIP、SigLIP、ALIGN |
| 視覚言語モデル | LLaVA、Flamingo、InternVL |

### 🌐 オムニモデル
| アーキテクチャ | 代表的なモデル |
|---|---|
| 任意→任意統合モデル | GPT-4o、Gemini 2.0、Grok 1.5 |

### 🎨 画像生成
| アーキテクチャ | 代表的なモデル |
|---|---|
| DDPM / DDIM | DDPM、DDIM |
| 潜在拡散モデル（LDM） | Stable Diffusion 3、DALL-E 3 |
| 拡散トランスフォーマー（DiT） | FLUX.1、Sora（画像）、PixArt-α |
| 敵対的生成ネットワーク（GAN） | StyleGAN3、BigGAN |
| 変分オートエンコーダー（VAE） | VQ-VAE-2、DALL-E（離散VAE） |

### 🎬 動画生成
| アーキテクチャ | 代表的なモデル |
|---|---|
| Video DiT | Sora、CogVideoX、OpenSora |
| 自己回帰型動画 | VideoGPT、Phenaki |

### 🔊 音声生成
| アーキテクチャ | 代表的なモデル |
|---|---|
| WaveNet（拡張因果畳み込み） | WaveNet、WaveGrad |
| 階層型言語モデル（AudioLM） | AudioLM、MusicLM、SoundStorm |
| フローマッチング | Voicebox、E2 TTS、Matcha-TTS |

### 🎙️ リアルタイム会話
| アーキテクチャ | 代表的なモデル |
|---|---|
| エンドツーエンド音声（GPT-4o方式） | GPT-4o Voice、Moshi |
| ニューラルTTS（VITS2） | VITS2、NaturalSpeech3 |

### 📦 3D生成
| アーキテクチャ | 代表的なモデル |
|---|---|
| NeRF / Instant-NGP | NeRF、Instant-NGP、Zip-NeRF |
| 3D Gaussian Splatting | 3DGS、Mip-Splatting、GaussianAvatars |
| トリプレーン拡散 | Shap-E、LRM、Zero123++ |

---

## 🚀 使い方

### 1. クローンして開く

```bash
git clone https://github.com/rikunarita/genai-universe.git
cd genai-universe
open genai-universe.html   # macOS
# またはファイルをブラウザにドラッグ＆ドロップ
```

### 2. （任意）ライブAPIデモを有効にする

ClaudeからリアルタイムでトークンをストリーミングするにはAnthropicのAPIキーが必要です。アプリの **Live Demo** パネルでキーを入力してください。キーはセッションのメモリにのみ保持され、保存・送信は一切されません。

> ⚠️ **CORSに関する注意**: ライブAPIデモは `file://` では動作しません。ローカルサーバー経由で開いてください：
> ```bash
> python3 -m http.server 8080
> # ブラウザで http://localhost:8080/genai-universe.html を開く
> ```

---

## 🧱 技術スタック

- **Pure HTML / CSS / JS** — フレームワーク・ビルドステップ・依存ライブラリ一切なし
- **Canvas 2D API** — アーキテクチャ図とアニメーションのカスタムレンダラー
- **Anthropic Messages API** — `claude-sonnet-4-20250514` によるストリーミング補完
- **Google Fonts** — Syne（ディスプレイ）、DM Sans（本文）、JetBrains Mono（コード）

---

## 📄 ライセンス

MIT — 自由に使用・改変・再配布可。クレジット表記は歓迎します。

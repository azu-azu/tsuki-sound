## 🌙 TsukiSound

### Generative Ambient Audio Engine Inspired by the Quiet of the Moon

A generative ambient audio engine that paints the quiet of the moon.

TsukiSound is not designed to measure time—it is made to let you
feel an atmosphere through sound.
The stillness of moonlight, the clarity of night air, the gentle drift of shadows—
all of these are reconstructed through pure sonic layers and natural, organic randomness,
creating an ambient sound engine shaped around quietness.

---

## ✨ Features | 主な特徴

### 🎼 Generative Audio Layers

時間とともに変化する、ジェネレーティブな音響レイヤー。

* **PureTone Engine** — ピュアで減衰の美しい倍音
* **LunarPulse** — 月の鼓動のような低周波の脈動
* **WaveBed / Drone Layers** — 呼吸のように広がる安定した音の床

### 🔊 Professional Mixing Architecture

AVAudioEngine を基盤とした

* Processing
* Mixing
* Playback
* Filters
* Dynamic Scheduling

という複数レイヤーを統合した構造。

### 🌘 Quiet UI

音に集中するための、最小限で静かなインターフェイス。

### 📱 Optional Features

* Circular Waveform Visualization
* Live Activity（再生中インジケータ）
* Clock View（音と時間を並置する世界観 UI）

---

## 🌌 Design Philosophy | デザイン哲学

TsukiSound の核にあるのは **Quiet Tech × Poetic Computing**。

* **Not music, but atmosphere**
  音楽ではなく“空気”をつくる。

* **Natural randomness**
  完全な規則性ではなく、自然界のゆらぎを模倣する。

* **Calm foreground, silent background**
  ユーザーの心を占領しない、穏やかな存在感。

* **Poetic Structure**
  コードやアーキテクチャも“静けさ”の一部として設計する。

---

## 🏗️ Architecture | アーキテクチャ構成

```
TsukiSound/
├── App/                    # Application entry point
├── Core/                   # Audio・サービス層
│   ├── Audio/              # Engine / Synthesis / Mixing / Presets
│   ├── Services/           # Route / Volume / Scheduler / NowPlaying
│   ├── Settings/           # App settings models
│   └── Extensions/
├── Domain/                 # 純粋な概念
│   └── Moon/               # 月のアルゴリズムと描画
├── DesignSystem/           # 色 / トークン / UI パーツ
├── Features/               # 機能別モジュール
│   ├── Audio/              # Audio UI
│   ├── Clock/              # Clock UI（副次機能）
│   └── Settings/
└── Resources/              # Audio / Localization / Assets
```

---

## 🚀 Setup

### Requirements

* iOS 17+
* Xcode 16+
* Swift 5.9+

### Install

```sh
git clone https://github.com/azu-azu/tsuki-sound.git
cd tsuki-sound
open TsukiSound.xcodeproj
```

---

## 🔧 Development

### Build

```sh
xcodebuild -project TsukiSound.xcodeproj -scheme TsukiSound -configuration Debug
```

### Test

```sh
xcodebuild test -project TsukiSound.xcodeproj -scheme TsukiSound
```

---

## 📖 Documentation

ドキュメントは `TsukiSound/Docs/` にまとめています。

* `architecture/` — アーキテクチャ仕様
* `_arch-audio-system-spec.md` — Audioエンジン仕様
* `implementation/` — 実装ガイド
* `report/` — レポート・トラブルシュート

---

## 📝 License

MIT License.

---

## 🤝 Contributing

We welcome pull requests and issue reports!
Before contributing, please review the following steps:

1. Fork the repository and create a new branch
2. Commit your changes
3. Open a pull request

---

## 📞 Support

If you encounter issues or have questions, please open a ticket in
[Issues](https://github.com/azu-azu/tsuki-sound/issues).

---

## 🔒 Privacy Policy

https://azu-azu.github.io/tsuki-sound/privacy.html

---

### ✨ App Store

- v1.4.0 2026/01/30 — Added FullPlayerView, in-app language switch, 3-mode repeat toggle, MiniPlayer waveform visualization, and category/track list navigation split
- v1.3.0 2025/12/19 — Added MP3 playback support with 3 new Gnossienne tracks (No. 1, No. 3, No. 4 Jazz)
- v1.2.1 2025/12/15 — Fixed WaningCrescentMoon arc direction for proper left-lit display
- v1.2.0 2025/12/12 — Added Repeat Mode Toggle for audio playback, applied Pedalboard-based audio effects for smoother ambience
- v1.1.0 2025/12/10 — Added swipe navigation between all tabs, improved back navigation from AudioSettings
- v1.0.0 2025/12/08

---

**TsukiSound**  — Feel the quiet. 🌙

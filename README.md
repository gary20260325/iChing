<div align="center">

# ☯ 旭决天机 | Xu Divination | 旭決天機

**以旭日为引，占一日之运**

[中文](#中文) · [English](#english) · [日本語](#日本語)

<img src="https://img.shields.io/badge/HTML5-single%20file-orange" alt="HTML5"/>
<img src="https://img.shields.io/badge/dependencies-zero-green" alt="Zero Dependencies"/>
<img src="https://img.shields.io/badge/i18n-中文%20%7C%20English%20%7C%20日本語-blue" alt="i18n"/>
<img src="https://img.shields.io/badge/license-MIT-yellow" alt="License"/>

</div>

---

<a id="中文"></a>

## 中文

### 简介

**旭决天机**是一款基于《易经》六十四卦的占卜应用，纯前端实现，无需任何后端服务。打开即用，无需安装。

### 功能特色

| 模块 | 说明 |
|------|------|
| 🃏 **今日一签** | 每日一卦，全屏翻牌交互，金色光效特效 |
| 🔮 **问事占卜** | 心有所疑，卦有所答，支持快捷话题标签 |
| 💫 **缘分合盘** | 双人缘分测算，四维评估（性格/感情/事业/价值观） |
| 🪵 **电子木鱼** | 敲木鱼积功德，支持自动敲击与多档速度 |

### 更多亮点

- **双主题**：素纸朱砂（亮色） / 耿夜旭黑（暗色）
- **三语支持**：中文 / English / 日本語，一键切换
- **算法透明**：起卦过程完全公开，7步推演一目了然
- **翻牌特效**：全屏黑底 + 金色光晕扩散 + 粒子飞散 + 光环涟漪
- **历史记录**：自动保存最近10条，可随时查看或清空
- **分享功能**：支持原生分享，一键复制结果
- **响应式设计**：适配手机、平板、桌面
- **尊重偏好**：支持 `prefers-reduced-motion` 无障碍设置

### 技术特点

- 📄 **单文件架构**：全部代码在一个 HTML 文件中
- 🚫 **零依赖**：无需 npm/webpack，直接打开即用
- 🔒 **纯本地计算**：无需网络请求，所有数据在浏览器端生成
- 💾 **localStorage 持久化**：主题、语言、历史、功德数据自动保存
- 🎵 **Web Audio API**：木鱼音效完全由代码合成，无需音频文件
- 🛡️ **XSS 防护**：用户输入严格转义

### 快速开始

```bash
# 直接用浏览器打开
open iChing.html

# 或使用本地服务器
python3 -m http.server 8080
# 然后访问 http://localhost:8080/iChing.html
```

### 致敬

> 天行健，君子以自强不息 · 致敬旭哥

---

<a id="english"></a>

## English

### Introduction

**Xu Divination** is an I Ching (Book of Changes) divination app built entirely with frontend technologies. No backend, no installation — just open and use.

### Features

| Module | Description |
|--------|-------------|
| 🃏 **Daily Fortune** | One hexagram per day with a dramatic card-flip reveal & golden light effects |
| 🔮 **Ask the Oracle** | Ask any question, receive guidance from the 64 hexagrams |
| 💫 **Destiny Match** | Compatibility analysis with 4 dimensions (Personality, Emotion, Career, Values) |
| 🪵 **Wooden Fish** | Knock the wooden fish to accumulate merit, with auto-knock & speed control |

### Highlights

- **Dual Themes**: Light (Vermillion & Paper) / Dark (Gold & Night)
- **Trilingual**: 中文 / English / 日本語 — switch with one tap
- **Transparent Algorithm**: Full 7-step divination process openly displayed
- **Card Flip FX**: Full-screen golden light explosion, particle scatter, ring ripples
- **History**: Auto-saves last 10 readings, viewable & clearable
- **Share**: Native Web Share API with clipboard fallback
- **Responsive**: Adapts to phones, tablets, and desktops
- **Accessibility**: Respects `prefers-reduced-motion`

### Technical Details

- 📄 **Single File**: Everything in one HTML file
- 🚫 **Zero Dependencies**: No build tools, no npm — just open in browser
- 🔒 **100% Local**: All computation happens in-browser, no server needed
- 💾 **Persistent**: Theme, language, history & merit saved via localStorage
- 🎵 **Synthesized Audio**: Wooden fish sound generated via Web Audio API
- 🛡️ **XSS Protected**: All user input properly escaped

### Quick Start

```bash
# Open directly in browser
open iChing.html

# Or use a local server
python3 -m http.server 8080
# Then visit http://localhost:8080/iChing.html
```

### Credits

> As Heaven maintains vigor through movements, a gentleman should constantly strive for self-improvement · In honor of Brother Xu

---

<a id="日本語"></a>

## 日本語

### 紹介

**旭決天機**は『易経』の六十四卦に基づく占いアプリです。フロントエンドのみで実装されており、バックエンド不要。開くだけですぐ使えます。

### 機能一覧

| モジュール | 説明 |
|-----------|------|
| 🃏 **今日の運勢** | 毎日一卦、カードフリップ演出と金色の光エフェクト |
| 🔮 **占い** | 心の中の疑問に六十四卦が答える |
| 💫 **縁結び** | 二人の相性を四次元（性格・感情・事業・価値観）で分析 |
| 🪵 **木魚** | 木魚を叩いて功徳を積む、自動叩き・速度調整対応 |

### 特徴

- **ダブルテーマ**: 素紙朱砂（ライト） / 耿夜旭黒（ダーク）
- **三ヶ国語対応**: 中文 / English / 日本語 — ワンタップ切替
- **アルゴリズム公開**: 7ステップの占いプロセスを完全公開
- **カードフリップ演出**: フルスクリーン金色光エフェクト・パーティクル・リング波紋
- **履歴機能**: 直近10件を自動保存、閲覧・クリア可能
- **共有機能**: Web Share API対応、クリップボードコピー
- **レスポンシブ**: スマホ・タブレット・デスクトップに対応
- **アクセシビリティ**: `prefers-reduced-motion` に対応

### 技術仕様

- 📄 **シングルファイル**: 全コードが一つのHTMLファイルに
- 🚫 **ゼロ依存**: npm/webpack不要、ブラウザで開くだけ
- 🔒 **完全ローカル**: 全ての計算はブラウザ内で完結
- 💾 **永続化**: テーマ・言語・履歴・功徳をlocalStorageに保存
- 🎵 **Web Audio API**: 木魚の音をコードで合成、音声ファイル不要
- 🛡️ **XSS対策**: ユーザー入力をエスケープ処理

### クイックスタート

```bash
# ブラウザで直接開く
open iChing.html

# またはローカルサーバーを使用
python3 -m http.server 8080
# http://localhost:8080/iChing.html にアクセス
```

### クレジット

> 天行健 君子以自強不息 · 旭兄へ敬意を表す

---

<div align="center">

**Made with ☯ and ❤️**

</div>

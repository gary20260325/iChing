<div align="center">

# ☯ 每日易经 H5 版本 | Daily I Ching H5 | 毎日易経 H5

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

### 项目简介

**每日易经 H5 版本**是一款基于《易经》六十四卦的移动端占卜应用。纯前端单文件实现，零依赖零构建，浏览器直接打开即可使用。

应用内含四大核心模块——今日一签、问事占卜、缘分合盘、电子木鱼，并提供亮色/暗色双主题与中英日三语切换，适合在微信、浏览器等 H5 环境中直接运行。

### 功能模块

| 模块 | 功能说明 |
|------|---------|
| 🃏 **今日一签** | 基于当日日期生成固定卦象，全屏翻牌交互配合金色光效特效，每日一卦洞察先机 |
| 🔮 **问事占卜** | 输入心中所问，支持快捷话题标签（事业/感情/财运/学业/健康），含动爻与变卦的三卦合断体系 |
| 💫 **缘分合盘** | 输入双方姓名与生日，从性格、情感、事业、价值观四维评估缘分指数，共 8 个缘分等级 |
| 🪵 **电子木鱼** | 精细 SVG 木鱼图形，Web Audio API 合成敲击音效，支持自动敲击与三档速度调节 |

### 设计特色

- **双主题切换**：素纸朱砂（暖色亮色主题）/ 耿夜旭黑（金色暗色主题），CSS 变量驱动，过渡动画平滑
- **三语国际化**：中文 / English / 日本語 一键切换，覆盖全部 UI 文案、64 卦解读、每日宜忌及合盘数据
- **翻牌特效**：全屏纯黑背景 + 金色径向光晕扩散 + 双层光环涟漪 + 30 粒子飞散 + 屏幕闪光
- **太极八卦图标**：SVG 绘制阴阳鱼与八卦卦符，持续旋转动画
- **算法透明**：占卜结果可展开查看完整推演过程（7 步），合盘可查看 4 步缘分算法
- **动爻变卦**：问事占卜支持动爻判定与变卦推演，提供逐爻解读与三卦合断
- **背景粒子**：亮色模式花瓣飘落、暗色模式光点上浮，页面不可见时自动暂停节省性能

### 技术实现

| 特性 | 说明 |
|------|------|
| 单文件架构 | 全部 HTML / CSS / JS 集中在一个文件，便于分发和部署 |
| 零外部依赖 | 仅引用 Google Fonts（Noto Serif SC），无需 npm 或构建工具 |
| 纯本地计算 | 种子化伪随机数生成器，同日同问结果一致，无需服务端 |
| 数据持久化 | localStorage 保存主题、语言、占卜历史（最近 10 条）、功德计数 |
| 音效合成 | Web Audio API 实时合成木鱼敲击音效，无需音频文件 |
| 安全防护 | 用户输入严格 HTML 转义，防止 XSS 注入 |
| 响应式适配 | 5 个断点覆盖超小屏手机到桌面端，触控优化 |
| 无障碍 | 支持 `prefers-reduced-motion`，尊重用户动画偏好 |

### 快速开始

```bash
# 方式一：浏览器直接打开
open iChing.html

# 方式二：本地服务器
python3 -m http.server 8080
# 访问 http://localhost:8080/iChing.html
```

### 致敬

> 天行健，君子以自强不息 · 致敬旭哥

---

<a id="english"></a>

## English

### About

**Daily I Ching H5** is a mobile-first divination app based on the 64 hexagrams of the I Ching (Book of Changes). Built as a single HTML file with zero dependencies — just open it in any browser and start.

It features four core modules: Daily Fortune, Ask the Oracle, Destiny Match, and Wooden Fish, with dual themes and trilingual support (Chinese, English, Japanese).

### Modules

| Module | Description |
|--------|-------------|
| 🃏 **Daily Fortune** | One hexagram per day, seeded by date. Full-screen card flip with golden light explosion effects |
| 🔮 **Ask the Oracle** | Ask any question with quick topic tags. Features moving lines & changed hexagram for deeper readings |
| 💫 **Destiny Match** | Enter two people's names & birthdays for a 4-dimension compatibility analysis (Personality, Emotion, Career, Values) |
| 🪵 **Wooden Fish** | Detailed SVG wooden fish with synthesized knock sound via Web Audio API. Auto-knock with 3 speed levels |

### Design

- **Dual Themes**: Light (Vermillion & Paper) / Dark (Gold & Night), driven by CSS variables with smooth transitions
- **Trilingual**: 中文 / English / 日本語 — one-tap switch covering all UI text, 64 hexagram readings, and match data
- **Card Flip FX**: Full-screen black background + golden radial glow + dual ring ripples + 30 particle scatter + screen flash
- **Taiji Icon**: SVG yin-yang with 8 trigrams, continuously rotating
- **Transparent Algorithm**: Expandable 7-step divination process and 4-step match algorithm
- **Moving Lines**: Question mode supports moving line detection, changed hexagram, and combined three-hexagram reading
- **Ambient Particles**: Falling petals (light) / rising light dots (dark), auto-paused when page is hidden

### Technical Details

| Feature | Detail |
|---------|--------|
| Single File | All HTML / CSS / JS in one file for easy distribution |
| Zero Dependencies | Only Google Fonts (Noto Serif SC), no npm or build tools required |
| 100% Local | Seeded PRNG ensures reproducible results, no server needed |
| Persistent | Theme, language, history (last 10), and merit count saved via localStorage |
| Synthesized Audio | Wooden fish knock sound generated via Web Audio API, no audio files |
| XSS Protected | All user input properly HTML-escaped |
| Responsive | 5 breakpoints from small phones to desktops, touch-optimized |
| Accessible | Respects `prefers-reduced-motion` |

### Quick Start

```bash
# Option 1: Open directly
open iChing.html

# Option 2: Local server
python3 -m http.server 8080
# Visit http://localhost:8080/iChing.html
```

### Credits

> As Heaven maintains vigor through movements, a gentleman should constantly strive for self-improvement · In honor of Brother Xu

---

<a id="日本語"></a>

## 日本語

### プロジェクトについて

**毎日易経 H5 バージョン**は、『易経』の六十四卦に基づくモバイル占いアプリです。シングルHTMLファイルで実装され、依存関係ゼロ。ブラウザで開くだけですぐ使えます。

今日の運勢、占い、縁結び、木魚の4つのコアモジュールを搭載し、ライト/ダーク二つのテーマと中日英三ヶ国語に対応しています。

### 機能モジュール

| モジュール | 説明 |
|-----------|------|
| 🃏 **今日の運勢** | 日付をシードとした毎日一卦。フルスクリーンカードフリップと金色光エフェクト |
| 🔮 **占い** | 心の中の疑問を入力、クイックタグ対応。動爻と之卦による三卦合断システム |
| 💫 **縁結び** | 二人の名前と生年月日を入力、四次元（性格・感情・事業・価値観）で相性分析 |
| 🪵 **木魚** | 精細なSVG木魚、Web Audio APIで敲击音を合成。自動叩き・3段階速度調整 |

### デザイン

- **ダブルテーマ**: 素紙朱砂（ライト）/ 耿夜旭黒（ダーク）、CSS変数駆動、スムーズな切り替え
- **三ヶ国語対応**: 中文 / English / 日本語 — ワンタップ切替、全UI文・64卦解説・縁結びデータ対応
- **カードフリップ演出**: フルスクリーン黒背景 + 金色放射光 + ダブルリング波紋 + 30パーティクル散乱
- **太極八卦アイコン**: SVG陰陽魚と八卦卦符、回転アニメーション
- **アルゴリズム公開**: 展開可能な7ステップ占いプロセスと4ステップ縁結びアルゴリズム
- **動爻・之卦**: 占いモードで動爻検出と之卦推演、逐爻解説と三卦合断を提供
- **環境パーティクル**: ライトモードは花びら落下、ダークモードは光点上昇、非表示時は自動一時停止

### 技術仕様

| 特性 | 説明 |
|------|------|
| シングルファイル | 全HTML/CSS/JSを一ファイルに集約、配布・デプロイが容易 |
| ゼロ依存 | Google Fonts（Noto Serif SC）のみ参照、npm/ビルドツール不要 |
| 完全ローカル | シード化疑似乱数生成器で再現可能な結果、サーバー不要 |
| 永続化 | テーマ・言語・履歴（直近10件）・功徳をlocalStorageに保存 |
| 音声合成 | Web Audio APIで木魚の敲击音をリアルタイム合成、音声ファイル不要 |
| XSS対策 | ユーザー入力をHTMLエスケープ処理 |
| レスポンシブ | 5つのブレークポイントで小画面スマホからデスクトップまで対応 |
| アクセシビリティ | `prefers-reduced-motion` に対応 |

### クイックスタート

```bash
# ブラウザで直接開く
open iChing.html

# ローカルサーバーを使用
python3 -m http.server 8080
# http://localhost:8080/iChing.html にアクセス
```

### クレジット

> 天行健 君子以自強不息 · 旭兄へ敬意を表す

---

<div align="center">

**Made with ☯ and ❤️**

</div>

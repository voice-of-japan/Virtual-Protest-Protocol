# Reclaim Flowers (RF) Project: Digital Altar Protocol
> **"A Silent Sanctuary for Every Precious Life, Beyond Borders and Politics."**

## [Manifesto / 宣言]

世界には不条理な死があふれています。  
亡くなった命には親兄弟・妻や子などの悲しみが染みついています。  
尊い命の喪失を等しく悼むため、この献花台を設けます。

The world is overflowing with irrational and unjust deaths.  
Every life lost is steeped in the profound grief of parents, siblings, spouses, and children.  
We establish this Digital Altar to honor and mourn the loss of every precious life, equally and without exception.

---

## 1. Overview / プロジェクト概要
"Reclaim Flowers" は、政治、国境、紛争を超え、不条理に失われたすべての命を静かに悼むためのデジタル献花台プロトコルです。SNS上の議論や対立を排し、純粋な「祈り」と「喪失の共有」を可視化します。

## 2. Technical Specifications / 技術仕様
この「静かな聖域」を構築するため、極限まで軽量かつ安全な設計を目指します。

### 2.1 Visuals (2D Physics Altar)
- **Physics Engine:** [Matter.js](https://brm.io) 等を使用し、物理演算による重力をシミュレート。
- **Interaction:** ユーザーが20〜30種類の花（PNG）から一輪を選択し、献花台へ。
- **Accumulation:** 世界中から捧げられる花がリアルタイムに降り積もる演出。無数の花が重なり合うことで、失われた命の数と弔いの総量を可視化します。特定の人数制限は設けず、すべての祈りを一つの台で受け止めます。

### 2.2 Multi-language Ticker (Raw Voices)
- **Principle:** 投稿された弔文（最大80文字）は**翻訳せず原文のまま**テロップ表示。
- **Effect:** 多言語が混ざり合うことで、悲しみの普遍性を可視化。アーカイブは行わず、その瞬間の祈りだけを尊びます。

### 2.3 AI Moderator (Sanctuary Guard)
- **Technology:** OpenAI API 等によるリアルタイム・フィルタリング。
- **Role:** 政治的スローガン、攻撃的な議論、ヘイトスピーチを遮断。純粋な弔意のみを通過させる「デジタルな静寂」を守ります。

## 3. Implementation Concept / 実装コンセプト
不条理な死が発生している具体的な場所・時期ごとに、個別の献花台を設置します。

*   **Case Study: "Gaza Mar.2026 Israel"**
    *   **Principle:** 全ての犠牲者への弔意が同じ一つの献花台に共存し、敵味方の区別なく、悲しみの普遍性を可視化します。

## 4. Technology Stack / 推奨技術
- **Frontend:** React / Vue.js / Matter.js (for 2D physics)
- **Backend:** Firebase / Supabase (Serverless architecture)
- **Security:** [Cloudflare](https://www.cloudflare.com) (DDoS protection)
- **Donation:** [Stripe](https://stripe.com) (No ads, no data mining)

## 5. Operation Policy / 運営方針
- **Non-Profit:** 広告なし、データ収集なし。創設者の個人資金と寄付で運営。
- **Privacy First:** 完全匿名。ユーザー追跡や個人情報のログ保存を一切行わない「究極のプライバシー保護」。

## 6. Message from Founder
**相澤 (Otoya Aizawa / Voice of Japan)**
75歳の元魚屋として、次世代に分断と1,300兆円もの借金の負債を遺さないための、私の最後の挑戦です。
銃声や怒号を止める力は私にはありません。しかし、その下で零れ落ちた涙を、**一つの場所で共に受け止めることはできる**と信じています。
この「Silent Sanctuary」を築くために、あなたの知恵と技術を貸してください。

---
### Join the Protocol
If you resonate with this mission, please open an Issue or contact us via GitHub.
[GitHub Repository: Virtual-Protest-Protocol]( https://github.com/voice-of-japan/Virtual-Protest-Protocol/blob/main/README.md)

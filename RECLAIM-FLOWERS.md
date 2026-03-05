# Reclaim Flowers (RF) Project: Digital Altar Protocol
"A Silent Sanctuary for Every Precious Life, Beyond Borders and Politics."

## Manifesto / 宣言
世界には不条理な死があふれています。  
亡くなった命には親兄弟・妻や子などの悲しみが染みついています。  
尊い命の喪失を等しく悼むため、この献花台を設けます。

The world is overflowing with irrational and unjust deaths.  
Every life lost is steeped in the profound grief of parents, siblings, spouses, and children.  
We establish this Digital Altar to honor and mourn the loss of every precious life, equally and without exception.

## 1. Overview / プロジェクト概要
"Reclaim Flowers" は、政治、国境、紛争を超え、不条理に失われたすべての命を静かに悼むためのデジタル献花台プロトコルです。SNS上の議論や対立を排し、純粋な「祈り」と「喪失の共有」を可視化します。

"Reclaim Flowers" is a digital altar protocol designed to quietly mourn all lives lost unjustly, beyond politics, borders, and conflicts. It avoids debates or confrontations on social media, visualizing pure "prayers" and shared grief.

## 2. Technical Specifications / 技術仕様
この「静かな聖域」を構築するため、極限まで軽量かつ安全な設計を目指します。

To build this "Silent Sanctuary," we aim for an extremely lightweight and secure design.

### 2.1 Visuals (2D Physics Altar)
- **Physics Engine**: Matter.js 等を使用し、物理演算による重力をシミュレート  
- **Interaction**: ユーザーが20〜30種類の花（PNG）から一輪を選択し、献花台へ  
- **Accumulation**: 世界中から捧げられる花がリアルタイムに降り積もる演出。無数の花が重なり合うことで、失われた命の数と弔いの総量を可視化します。一定量で上限を設定し、ブラウザ負荷を軽減します。

- **Physics Engine**: Using Matter.js or similar, simulates gravity with 2D physics  
- **Interaction**: Users select one flower from 20–30 PNG options and place it on the altar  
- **Accumulation**: Flowers offered from around the world fall and accumulate in real time. The overlapping flowers visually represent the number of lives mourned. A maximum limit is set to reduce browser load.

### 2.2 Multi-language Ticker (Raw Voices)
- **Principle**: 投稿された弔文（最大80文字）は翻訳せず原文のままテロップ表示  
- **Effect**: 多言語が混ざり合うことで、悲しみの普遍性を可視化。アーカイブは行わず、その瞬間の祈りだけを尊びます。

- **Principle**: Submitted condolence messages (max 80 characters) are displayed in their original language without translation  
- **Effect**: The mix of languages visualizes the universality of grief. No archives are kept, honoring only the prayer in the moment.

### 2.3 AI Moderator (Sanctuary Guard)
- **Technology**: OpenAI API 等によるリアルタイム・フィルタリング  
- **Role**: 政治的スローガン、攻撃的な議論、ヘイトスピーチを遮断。純粋な弔意のみを通過させる「デジタルな静寂」を守ります。

- **Technology**: Real-time filtering using OpenAI API or similar  
- **Role**: Blocks political slogans, aggressive arguments, and hate speech, allowing only genuine condolence messages to pass, maintaining digital silence.

## 3. Implementation Concept / 実装コンセプト
不条理な死が発生している具体的な場所・時期ごとに、個別の献花台を設置します。

- **Case Study**: "Gaza Mar.2026 Israel"  
- **Principle**: 全ての犠牲者への弔意が同じ一つの献花台に共存し、敵味方の区別なく、悲しみの普遍性を可視化します。

Separate altars are set up for each specific place and time where unjust deaths occur.  
- **Case Study**: "Gaza Mar.2026 Israel"  
- **Principle**: Condolences for all victims coexist on a single altar, without distinguishing friend or foe, visualizing the universality of grief.

## 4. Technology Stack / 推奨技術
- **Frontend**: React / Vue.js / Matter.js (for 2D physics)  
- **Backend**: Firebase / Supabase (Serverless architecture)  
- **Security**: Cloudflare (DDoS protection, cached delivery for speed and stability)  
- **Donation**: Stripe (No ads, no data mining)

## 5. Operation Policy / 運営方針
- **Non-Profit & Privacy First**  
  広告なし、データ収集なし。ユーザー追跡や個人情報のログ保存は一切行わず、完全匿名で運営します。運営資金は創設者の個人資金と寄付によって賄われ、透明性と信頼性を確保します。

- **Non-Profit & Privacy First**  
  No ads, no data collection. User tracking or personal information logging is not performed; the project is fully anonymous. Operational costs are covered by the founder's personal funds and donations, ensuring transparency and trust.

- **AI-Managed Autonomous Operation**  
  運営はAIに任せ、外部管理者の介入なしで自動運営されます。政治的・攻撃的・ヘイトスピーチなどはリアルタイムで遮断され、純粋な弔意のみが通過します。

- **AI-Managed Autonomous Operation**  
  The altar is managed entirely by AI without external intervention. Political, aggressive, or hateful content is blocked in real-time, allowing only pure condolences to be displayed.

- **One-Way Experience**  
  投稿者は花を選び、弔文を入力し献花するのみ。Infoや掲示板など、議論を呼ぶ機能は一切設置せず、完全な一方通行の体験を提供します。

- **One-Way Experience**  
  Users select a flower, enter a condolence message, and offer it. No forums or discussion boards are provided; the experience is completely one-way.

- **No Archive / Auto-Reset**  
  投稿や弔文のアーカイブは行わず、ログは残しません。  
  献花台は一定の条件（花の量や期間）を超えると自動的に消滅し、必要期間内であれば新しい献花台が自動生成されます。

- **No Archive / Auto-Reset**  
  No archiving of messages is done; no logs are kept.  
  Altars automatically disappear when a set condition (number of flowers or duration) is met, and new altars are automatically generated within the necessary timeframe.

- **Cloudflare Integration**  
  全ての静的コンテンツ（花画像・CSS・JS）は Cloudflare を経由して配信され、高速で安定したアクセスを確保するとともに、DDoS攻撃や不正アクセスから保護されます。

- **Cloudflare Integration**  
  All static content (flower images, CSS, JS) is served via Cloudflare to ensure fast and stable access and protect against DDoS attacks and unauthorized access.

## 6. Message from Founder
相沢 (Otoya Aizawa / Voice of Japan) 75歳の元魚屋として、次世代に分断や過大な負債を遺さないための、私の最後の挑戦です。  
銃声や怒号を止める力は私にはありません。しかし、その下で零れ落ちた涙を、一つの場所で共に受け止めることはできると信じています。  
この「Silent Sanctuary」を築くために、あなたの知恵と技術を貸してください。

Otoya Aizawa (Founder / Voice of Japan), a 75-year-old former fishmonger, sees this as his final challenge to prevent leaving future generations with division and excessive debt.  
I cannot stop gunfire or shouting, but I believe we can together receive the tears that fall beneath them in a single place.  
Please lend your wisdom and skills to help build this "Silent Sanctuary."

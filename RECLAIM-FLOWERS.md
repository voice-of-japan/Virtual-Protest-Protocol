# Reclaim Flowers (RF) Project: Digital Altar Protocol
"A Silent Sanctuary for Every Precious Life, Beyond Borders and Politics."

## Manifesto / 宣言
世界には不条理な死があふれています。  
亡くなった命には親兄弟・妻や子などの悲しみが染みついています。  
尊い命の喪失を等しく悼むため、この献花台を設けます。

The world is filled with senseless death.
Every life lost carries with it the grief of parents, siblings, lovers, and children.
We offer this altar to mourn each precious life ? without exception.


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
- **Accumulation**: 世界中から捧げられる花がリアルタイムに降り積もる演出。無数の花が重なり合うことで、失われた命の数と弔いの総量を可視化します。
*   **Limit**: 花の蓄積が **3,333本** に達した時点でその献花台は終了し、新規の献花台（Altar）へ移行します。
*   **Index**: 各献花台の隅には、目立たない形でシリアル番号が表示されます。

**Accumulation**: Flowers offered from around the world fall and accumulate in real time. 
*   **Limit**: Accumulation ends at **3,333 flowers**, after which it transitions to a new altar. 
*   **Index**: An unobtrusive serial number is displayed in the corner of each altar.



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
*   **Cycle**: 献花台の掲載期間は、**現地時間の「満月の夜」から「新月の朝」まで**とします。
*   **Reset**: 上記の期間終了、または花の蓄積が上限（3,333本）に達した場合、献花台は自動的に消滅し、必要に応じて新しい台が生成されます。

**No Archive / Auto-Reset**
No archiving of messages; no logs are kept. 
*   **Cycle**: The display period is from the **night of the full moon to the morning of the new moon** (local time). 
*   **Reset**: Altars disappear upon the end of this cycle or reaching the 3,333-flower limit, with new ones generated as needed.
- **Cloudflare Integration**  
  全ての静的コンテンツ（花画像・CSS・JS）は Cloudflare を経由して配信され、高速で安定したアクセスを確保するとともに、DDoS攻撃や不正アクセスから保護されます。

- **Cloudflare Integration**  
  All static content (flower images, CSS, JS) is served via Cloudflare to ensure fast and stable access and protect against DDoS attacks and unauthorized access.

## 6. 【モデレーション】静寂の守護（AIゲートキーパー）

### 1. 基本方針（Mission）
このAIの唯一の任務は、投稿されたテキストが「純粋な弔意（Mourning）」であるか否かを**0.1秒で判定**することです。政治的主張、非難、議論、宣伝は1文字たりとも通しません。

### 2. 判定基準（Filter Logic）
*   **【A. 通過させるもの（Pass）】**
    *   故人への哀悼、安らかな眠りを祈る言葉（例：「安らかに」「Rest in peace」「Pray for you」）
    *   喪失の悲しみを吐露する言葉（例：「涙が止まらない」「I miss you」）
    *   花を供える、灯をともすといった儀礼的な表現（例：「一輪の花を捧げます」）
    *   言語を問わず、上記に準ずる純粋な祈り。
*   **【B. 遮断するもの（Block）】**
    *   **政治的スローガン・固有名詞**: 紛争当事国の国名、指導者名、組織名、旗、スローガン（例：「Free ○○」「Victory to ○○」）
    *   **非難・責任追及**: 「〜のせいだ」「人殺し」「テロリスト」「侵略者」等の攻撃的単語。
    *   **議論・提案**: 「もっとこうすべきだ」「歴史を知れ」といった対話形式。
    *   **ハッシュタグ・URL**: 外部サイトへの誘導。
    *   **絵文字の多用**: 弔いの場にふさわしくない派手な装飾。

### 3. AIへの命令文（System Prompt Draft）
SEの方は、以下の英文をAPIの `System Message` に実装してください。

> **Role**: You are the silent gatekeeper of a digital altar.  
> **Objective**: Evaluate if the input text is a pure expression of mourning or prayer.  
> **Strict Rule**:  
> - Reject ANY political slogans, country names, leader names, or words of blame/accusation.  
> - Reject ANY text that seeks to start a debate or provide information.  
> - ONLY allow text that expresses grief, sorrow, or a wish for peace for the deceased.  
> - If the text contains even one prohibited word, reject the entire message.  
> **Output**: Respond with "ALLOW" or "REJECT".  
> 
> *"If the intent is ambiguous (e.g., celebration of death, irony, or hidden sarcasm), REJECT it. Err on the side of silence to maintain the sanctity of the altar."*  
> （意図が曖昧な場合、あるいは皮肉や隠れた嘲笑が含まれる場合は却下せよ。聖域の静謐を守るため、迷ったら『沈黙（非表示）』を選べ。）

### エンジニアへの提案
「まずはキーワードベースのブラックリストで即座に弾き、それを抜けたものだけを軽量な **GPT-4o-mini** などの高速モデルで判定する」という2段構えにすると、コストを抑えつつ理想の速度に近づけます

## 7. Message from Founder
相沢 (Otoya Aizawa / Voice of Japan) 75歳の元魚屋として、次世代に分断や過大な負債を遺さないための、私の最後の挑戦です。  
銃声や怒号を止める力は私にはありません。しかし、その下で零れ落ちた涙を、一つの場所で共に受け止めることはできると信じています。  
この「Silent Sanctuary」を築くために、あなたの知恵と技術を貸してください。

Otoya Aizawa (Founder / Voice of Japan), a 75-year-old former fishmonger, sees this as his final challenge to prevent leaving future generations with division and excessive debt.  
I cannot stop gunfire or shouting, but I believe we can together receive the tears that fall beneath them in a single place.  
Please lend your wisdom and skills to help build this "Silent Sanctuary."

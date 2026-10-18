# Virtual Protest Protocol (VPP)

### **AI時代において、個人の「声」に力を取り戻す**
### **Empowering Human Voices in the AI Era**

---

# Part A. Overview / 概要

## 1. 哲学：なぜVPPなのか / Philosophy: Why VPP?

As a 75-year-old pioneer, I refuse to leave a legacy of silence and division. VPP is the **"Active (動)"** side of our mission: reclaiming civic space by visualizing the **collective energy and heat** of those often dismissed in modern society.

75歳の開拓者として、私は沈黙と分断を遺したくありません。VPPは私たちの活動の「動」の側面であり、集団的な「人の気配と熱量」を可視化し、市民の場（シビック・スペース）を取り戻すためのインフラです。

## 2. コンセプト：熱量と気配の可視化 / Concept: Manifestation of Energy

To ensure the protocol is accessible to everyone, we adopt a **"Minimum-Spec, Maximum-Impact"** architecture. This "lightness" is our technical answer to inclusivity.

誰一人取り残さないため、「最小スペックで最大の影響」を生む設計を採用しています。この「軽さ」こそが、参加の障壁を取り払うための回答です。

## 3. 実装の肝：超軽量な存在証明 / Lean Manifestation

- **3.1 Four-Frame Sprite Avatars (Motion & Presence):** Manifesting "Collective Energy" with ultra-lightweight assets (standing / walking).
  （4枚のスプライト：画像4枚で一人を表現。極限の軽さで「人の気配と熱量」をデジタル空間に生み出します。）
- **3.2 Cell-Based Unit Management (50-Person Clusters):** Scalable "Heat of the Crowd" without overloading the engine.
  （50人を1単位とするセル管理：低スペック端末でも「群衆の熱量」を体感可能にします。）

## 4. 技術と運営方針 / Technology & Policy

- **Visuals:** React / Matter.js (2D physics for gathering avatars).
- **AI moderation (current):** a third-party AI API (OpenAI) classifies each statement. The text is sent to that service for the check only. Retention on the provider's side follows the provider's own terms.
- **AI moderation (roadmap):** we will evaluate self-hosted open-source models, so that statements no longer need to leave our infrastructure (see 11.x).
- **Policy:** Non-profit. No advertising. No tracking of participants. No sale of participant data. Funded by the founder's personal funds, donations, and grants.

- **ビジュアル：** React / Matter.js（アバターが集まる2D物理演算）。
- **AIモデレーション（現在）：** 外部のAI API（OpenAI）が発言を判定します。判定のためだけに、発言の文章が外部サービスに送られます。提供元での保持は、提供元の規約に従います。
- **AIモデレーション（ロードマップ）：** 発言が外部に出ないよう、自前運用のオープンソースAIを検討します（11.x参照）。
- **方針：** 非営利。広告なし。参加者の追跡なし。参加者データの販売なし。創設者の個人資金、寄付、助成金で運営します。

## 5. 詳細仕様への案内 / Guide to Detailed Specifications

*The following sections provide the technical framework and strategic roadmap.*
（以下のセクションでは、技術的フレームワークと戦略的ロードマップを記述します。）

---

# Part B. Specification / 詳細仕様

## 1. 技術的要件と背景 / Technical Requirements & Background

To visualize "Mass Momentum" on the web, we require low-latency synchronization and high-performance 2D rendering that works on restricted networks.

ウェブ上で「群衆の躍動」を可視化するため、制限されたネットワーク環境でも動作する低遅延同期と高性能な2Dレンダリングを追求します。

## 2. 基本原則 / Core Principles

**[JP]**
- 非暴力を前提とする
- 沈黙（判断保留）を意思として可視化する
- 個人を特定しない
- 示威行動を「数」ではなく「分布」として扱う

**[EN]**
- Non-violence as a prerequisite
- Visualization of silence and undecided positions
- No personal identification
- Treating public will as distribution rather than sheer numbers

## 3. 意思表示方式（三択制） / Three-Option System

**[JP]** 参加者は以下のいずれかを選択します。
- Yes（賛成）
- No（反対）
- Observe（注視・判断保留）

**[EN]** Participants choose one of the following options:
- Yes (Support)
- No (Opposition)
- Observe (Undecided / Watching)

## 4. 可視化方法（リアルタイム・バー） / Visual Indicator

**[JP]** デモ画面の下部に、Yes（緑）／No（赤）／Observe（グレー）の比率を、数値付きのダイナミック・バーとして常時表示します。これにより、民意のバランスを直感的に可視化します。

**[EN]** A dynamic bar displaying the ratio of Yes (green), No (red), and Observe (gray) is shown at the bottom of the demonstration screen in real time. This allows intuitive visualization of public opinion balance.

## 5. 参加資格と示威行動の実施範囲 / Eligibility and Protest Scope

**[JP]**
- 参加は国内在住者を前提とする
- 発言は国内で使用される国語に限定する
- **示威行動は国内でのみ実施する**

扱う議題（テーマ）は国内問題に限定しない。たとえば、日本のサイトにおいて、ウクライナ侵攻に抗議する意思表示を行うことは可能である。ただし、示威行動を他国の仮想空間（例：赤の広場など）で実施しない。これは、参加者が国外の権力や攻撃対象となるリスクを避けるためである。

居住地の確認を行う場合も、識別可能な情報を保存してはならない。

**[EN]**
- Participation is intended for residents within the country
- Statements must be made in the national language
- **Demonstrations are conducted only within the domestic virtual space**

The subject matter is not limited to domestic issues. For example, participants on a Japanese platform may express opposition to the invasion of Ukraine. However, demonstrations are not conducted in foreign symbolic locations (e.g., Red Square). This restriction exists to reduce the risk of participants becoming targets of external authorities or attacks.

Any residency check must not store identifying information.

## 6. 参加方法と属性選択 / Participation and Attributes

**[JP]** 参加時に以下を選択・記入します。

- **a. ハンドルネーム：** 12文字以内。本名および本名を想起させるものは禁止。AIモデレーターによる重複チェックを行う。
- **b. 年齢層：** 18–39 / 40–64 / 65+。米国版は18歳以上のみ。他国では、現地法に従い、18歳未満（u18）の区分を設ける場合がある。
- **c. 性別：** 男 / 女 / non
- **d. 居住地域：** 州・地方など。個人が特定されにくい、広い単位とする。
- **e. 主張テキスト：** 80文字以内。AIモデレーターによる内容チェックを実施する。
- **f. アバターの選択：** 20種類以上のコンセプト（Issue #5）から、自分の分身となる2Dアバターを選択する。
- **g. 立場の選択：** Yes（緑）/ No（赤）/ Observe（灰色）のいずれかを選択する。その色はハンドルネームの枠に反映され、自らの立場を明確にした状態でデモ空間へ入場する。

**[EN]** Participants provide the following:

- **a. Handle name:** up to 12 characters. Real names and names suggesting a real name are prohibited. Checked for duplication by the AI moderator.
- **b. Age group:** 18–39 / 40–64 / 65+. The U.S. version is limited to participants aged 18 or older. In other countries, an under-18 (u18) band may be offered where local law permits.
- **c. Gender:** Male / Female / Non-binary
- **d. Region of residence:** state or region; broad units that make identifying an individual harder.
- **e. Statement text:** up to 80 characters. Content is checked by the AI moderator.
- **f. Avatar selection:** choose a 2D avatar as your digital twin from over 20 unique concepts (defined in Issue #5).
- **g. Stance selection:** Yes (Green), No (Red), or Observe (Gray). The color is reflected in the frame of your handle name, so you enter the protest space with a visible position.

### 6-2. Privacy and Data Protection / プライバシー保護

To protect participants, VPP follows the principles of "Privacy by Design" and data minimization, drawing on the privacy principles of **GDPR** and **CCPA/CPRA**.
参加者の安全のため、VPPは「プライバシー・バイ・デザイン」とデータ最小化の原則に従い、GDPRやCCPA/CPRAのプライバシー原則を参考に設計します。

- **Minimal attributes (最小限の属性):** Age is collected only in broad bands, and no names, e-mail addresses, or accounts are collected. This lowers the risk of re-identification, but does not eliminate it: in small regions, a combination of gender, age band, region, and statement text could still point to a person. To reduce this risk, we use broad regional units, do not display attributes next to statements, and plan not to publish statistics for very small groups.
  年齢は広い区分のみで収集し、氏名・メールアドレス・アカウントは収集しません。再識別のリスクは下がりますが、ゼロにはなりません。人口の少ない地域では、性別・年齢層・地域・発言文の組み合わせから、個人が推測される可能性があるためです。対策として、広い地域単位を使い、属性を発言の横に表示せず、極めて少人数の集計は公表しない方針です（計画）。
- **No IP storage by the application (アプリはIPアドレスを保存しない):** The application is designed not to store IP addresses, and not to keep logs that link a person to an avatar. Requests pass through Cloudflare, which processes network-level data under its own policies.
  アプリケーションは、IPアドレスを保存せず、個人とアバターを結びつけるログを保持しないように設計されています。通信はCloudflareを経由し、ネットワークレベルのデータは同社の規約に従って処理されます。
- **Legal status (法的な位置づけ):** VPP has not yet undergone a formal legal review. Statements about legal compliance or exemptions will be added only after such a review.
  VPPは、まだ正式な法務レビューを受けていません。法令への適合や適用除外に関する記述は、レビューの後に追加します。

## 7. アバター仕様 / Avatar System

**[JP]** 数十種類のアバターを提供します。
- 真面目なもの
- ユーモラスなもの
- 著作権を侵害しないデフォルメヒーロー
- 擬人化された動物
- 民族衣装 など

各アバターは3〜4種類の動作を持つ静止画で構成され、最終画像には吹き出し形式で主張テキストを表示します。詳細はIssueにて議論・記載します。

**[EN]** Dozens of avatars are provided, including:
- Serious styles
- Humorous styles
- Non-copyright-infringing stylized heroes
- Anthropomorphized animals
- Traditional ethnic costumes

Each avatar consists of 3–4 static poses, with the final image displaying the statement in a speech bubble. Details are discussed in Issues.

## 8. デモ・集会の時間管理 / Time and Cell Management

**[JP]**
- 稼働時間：現地時間 10:00–20:00（時間外は、表紙のみ閲覧可能）

50人を1セルとして管理し、満杯になり次第、次のセルへ移行します。

**[EN]**
- Operating hours: 10:00–20:00 local time (outside these hours, only the cover page is available)

Participants are grouped into cells of 50. Once a cell is full, a new one is created.

## 9. パレードの視覚的設計と能動的参加 / Visual Design & Active Engagement

**A. 意見の混在による分断の解消と統計の可視化 / Mixed Opinions & Statistical Clarity**

- **JP:** 各セル内では、賛成・反対・注視（Observe）のアバターが分け隔てなく混在して表示されます。視覚的な分断（エコーチェンバー）を避ける一方で、**各項目の正確な集計実態は、常に下段のリアルタイム・バー（項目4参照）によって一目で把握できる**設計となっています。
- **EN:** Within each cell, **YES, NO, and OBSERVE** avatars march together. While avoiding visual polarization, the **precise statistical breakdown is always clearly visible on the real-time bar at the bottom (see item 4)**.

**B. クリックによる意思表示の証明 / Engagement via Clicking (Anti-Bot)**

- **JP:** アバターは、ユーザーにクリック（タップ）されることで動作し、個人の主張（吹き出し）を表示します。これにより、単なる数値だけでなく、放置アカウントや自動ボットではない「生きた人間の積極的な関与」を示します。
- **EN:** Avatars act and show their statement bubble when clicked (tapped). This indicates active engagement by a living person, rather than an abandoned account or an automated bot.

## 10. 反暴力AIモデレーション / Transparent AI Moderation

**[JP]**
- AIモデレーターが発言をリアルタイムで判定します。
- 暴力的表現に対しては「書き直し」を推奨します。
- 物理的・言語的暴力を排除します。
- 規制内容（禁止する表現の定義）は、このリポジトリで公開します。
- AIは誤判定をすることがあります。判定に迷う場合の扱いは、各サイトの方針として明示します。

**[EN]**
- AI moderators check statements in real time.
- Violent expressions trigger rewrite suggestions.
- Physical and verbal violence are excluded.
- The moderation rules (definitions of prohibited expressions) are published in this repository.
- The AI can make mistakes. How each site handles uncertain cases is stated in that site's policy.

## 11. プライバシー設計 / Privacy by Design

**[JP]** デモ終了後、性別・年齢層・居住地などの統計データを除き、すべての個人識別情報および発言ログを即時破棄します。

**[EN]** After the demonstration ends, all personally identifiable information and statements are deleted immediately, except for aggregated statistical data such as gender, age group, and region.

### 11.x. Roadmap for Privacy & Resilience / プライバシーと堅牢性のロードマップ

We are exploring the following four-pillar strategy. None of these is implemented in the current MVP.
（以下の4本柱を検討しています。いずれも、現在のMVPでは実装されていません。）

- **Anonymity via Zero-Knowledge Proofs (ZKP) / ゼロ知識証明による匿名性:** allow users to prove they are valid participants without revealing their identity or metadata to the server. See [Zero-knowledge proof](https://en.wikipedia.org/wiki/Zero-knowledge_proof).
  （サーバーにアイデンティティを明かさず、「正当な参加者であること」のみを証明する仕組みを目指します。）
- **Anti-bot measures via client-side Proof of Work / クライアントサイドPoWによるボット対策:** requiring a few seconds of computation (e.g., [Hashcash](https://en.wikipedia.org/wiki/Hashcash)) before submission raises the cost for bots without collecting personal data.
  （投稿前に数秒の計算処理を要求し、個人情報を収集せずにボットの攻撃コストを高めます。）
- **Double-submission prevention via nullifiers / ヌルファイアによる二重投稿の排除:** detect repeated use of the same anonymous credential within a single protest session, to support "one person, one voice" without compromising anonymity.
  （特定のデモ内で、同じ匿名資格が二度使われることを検知します。）
- **Open-source, self-hosted AI moderation / オープンソースAIによるモデレーション:** evaluate self-hosted open-source models, guided by community-defined, published guidelines, so that statements do not need to be sent to third-party services.
  （コミュニティが合意した、公開ガイドラインに基づく、自前運用のオープンソースAIを検討します。発言を外部サービスに送る必要がなくなります。）

## 12. 運営方針・国別仕様 / Operation Model

**[JP]**
- 全ての国・地域で、非営利の方針を適用する
- 運営費を除いた余剰は、他国・地域サイトの支援に充当する

連帯の象徴として、各国サイトのURLは `voice-of-{nation}` 形式を推奨します。示威行動の事案は運営側が提示し、原則として、複数の大手新聞に掲載されたトピックを対象とします。

**[EN]**
- The non-profit policy applies in every country and region
- Any surplus beyond operating costs supports other regions

As a sign of solidarity, the URL format `voice-of-{nation}` is recommended. Demonstration topics are proposed by operators and generally limited to issues covered multiple times by major newspapers.

## 13. 米国版仕様（概要） / U.S. Version Overview

**[JP]** 米国にはVOAが存在するため、名称は **Virtual Demo & Rally @ Home [Will of America]** とします。

資金：
- ドネーション
- 助成金

広告の掲載や、参加者データの販売は行いません。

- 属性：性別／年齢層／居住州
- 支持政党は取得しない
- 参加資格は18歳以上

**[EN]** Due to the existence of VOA, the U.S. version is titled **Virtual Demo & Rally @ Home [Will of America]**.

Funding:
- Donations
- Grants

No advertising is placed, and no participant data is sold.

- Attributes: gender, age group, state
- Political party affiliation is not collected
- Participants must be 18 years or older

## 14. 開発協力・パートナーシップの呼びかけ / Call for Collaboration & Partnership

We seek technologists and visionaries who believe in the power of **"Democratic Tech."** Let's build a "Visible Plaza" together where no voice is left behind.

「民主主義のための技術」を信じる技術者やビジョナリーを募集しています。誰の声も置き去りにされない「可視化された広場」を共に築きましょう。

---

# 技術仕様とガバナンス / Technical Architecture & Governance

このプロジェクトは、思想を確実に実行するために「設計による自治（Governance by Design）」を採用しています。
This project adopts "Governance by Design" so that its principles are carried out by the system itself.

### 1. Privacy by Design (No Application Logs) / 設計によるプライバシー

- **Implementation:** **Cloudflare Workers** process data in memory. The application does not persist IP addresses or request logs.
- **Privacy:** Because the application does not store identifying information, the administrator has no access to it. Infrastructure providers (e.g., Cloudflare) process network-level data under their own policies.
- **実装：** Cloudflare Workersで、データをメモリ内で処理します。アプリケーションは、IPアドレスやリクエストログを保存しません。
- **プライバシー：** アプリケーションが識別情報を保存しないため、管理者もそれにアクセスできません。インフラ提供者（Cloudflareなど）は、ネットワークレベルのデータを、自社の規約に従って処理します。

### 2. AI-Assisted Moderation (The Silent Gatekeeper) / AIによるモデレーション

- **Logic:** Moderation is delegated to an automated AI agent ("The Silent Gatekeeper") based on semantic analysis and published rules. There is no human review step in the runtime pipeline.
- **Limits:** This reduces individual bias and pressure, but does not guarantee neutrality. The AI can make mistakes, and the rules themselves reflect choices. All rules and any changes to them are public in this repository.
- **ガバナンス：** モデレーションは、意味解析と、公開されたルールに基づく自律型AI「静かなる門番」に委ねられます。実行時に、人間が確認する工程はありません。
- **限界：** これにより、個人の偏見や外部からの圧力は減りますが、中立性は保証されません。AIは誤ることがあり、ルール自体にも選択が含まれます。すべてのルールと、その変更は、このリポジトリで公開されます。

### 3. Known Limitations / 既知の限界

- Re-identification risk is reduced, not eliminated (see 6-2).
- Bot resistance is limited in the MVP; stronger measures are in the roadmap (11.x).
- Moderation can wrongly block or allow content.
- The system depends on third-party services (Cloudflare, an AI API).
- 再識別のリスクは、下がりますが、ゼロにはなりません（6-2参照）。
- MVPでのボット対策は限定的です。強化はロードマップにあります（11.x）。
- モデレーションは、誤って遮断または通過させることがあります。
- 第三者のサービス（Cloudflare、AI API）に依存しています。

---

# 立案者について / About the Author

As the founder of **"Voice of Japan"** and a veteran of early viral internet content (such as the **Crimson Room** era), I have spent decades observing the intersection of technology and human emotion. I understand that "Content + Purpose" is what drives massive, organic participation.

This protocol is my final challenge as a 75-year-old former fishmonger: to ensure that the marginalized can stand together and their **"Collective Heat"** can be felt by the world.

「日本の声」創設者であり、かつてバイラルなネットコンテンツ（クリムゾンルーム等）を運営した経験から、私は技術と人間の感情が交差する場を見つめてきました。「コンテンツと大義」こそが、自発的で大規模な参加を生む原動力であると確信しています。

75歳の元魚屋として、これが私の最後の挑戦です。声なき人々が共に立ち上がり、その「集団的な熱量」を世界に届けるための場所を遺すために、力を貸してください。

---

# Project Status / プロジェクトの現状

**Reclaim Flowers (RF)** is the first concrete implementation of the VPP philosophy: a shared, anonymous, temporary digital altar. Implementation details are in [`RECLAIM-FLOWERS.md`](./RECLAIM-FLOWERS.md).

デジタル献花台 **Reclaim Flowers (RF)** は、VPP理念の最初の具現化で、共有された、匿名の、期間限定のデジタル献花台です。実装の詳細は [`RECLAIM-FLOWERS.md`](./RECLAIM-FLOWERS.md) を参照してください。

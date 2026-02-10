# Virtual Protest Protocol (VPP)

> [!IMPORTANT]
> **Why we are building VPP**  
> To understand the social mission and the deep personal experiences (Fukushima recovery) behind this project, please read our statement in **[Issue #6](https://github.com)**.
> 
## 1. 概要 / Abstract

### [JP]
VPP（Virtual Protest Protocol）は、  
2Dアバターを用いたデジタル空間における示威行動（デモ・集会）のための  
**オープンソース・プロトコル**です。

SNSにおける誹謗中傷の拡散、  
および物理的デモが持つ高コスト・高リスクという課題を回避し、  
「反暴力」と「沈黙の可視化」を軸とした  
**新しい合意形成のための公共インフラ**を提供することを目的とします。

### [EN]
VPP (Virtual Protest Protocol) is an open-source protocol  
for demonstrations and rallies conducted in a digital space using 2D avatars.

It aims to address the issues of online harassment prevalent in social media  
and the high cost and risk of physical protests,  
by providing a public infrastructure for consensus-building  
based on non-violence and the visualization of silence.

---

## 2. 基本原則 / Core Principles

### [JP]
- 非暴力を前提とする  
- 沈黙（判断保留）を意思として可視化する  
- 個人を特定しない  
- 示威行動を「数」ではなく「分布」として扱う  

### [EN]
- Non-violence as a prerequisite  
- Visualization of silence and undecided positions  
- No personal identification  
- Treating public will as distribution rather than sheer numbers  

---

## 3. 意思表示方式（三択制） / Three-Option System

### [JP]
参加者は以下のいずれかを選択します。

- Yes（賛成）
- No（反対）
- Observe（注視・判断保留）

### [EN]
Participants choose one of the following options:

- Yes (Support)
- No (Opposition)
- Observe (Undecided / Watching)

---

## 4. 可視化方法（リアルタイム・バー） / Visual Indicator

### [JP]
デモ画面の下部に、  
Yes（青）／No（赤）／Observe（グレー）の比率を  
数値付きのダイナミック・バーとして常時表示します。

これにより、民意のバランスを直感的に可視化します。

### [EN]
A dynamic bar displaying the ratio of  
Yes (blue), No (red), and Observe (gray)  
is shown at the bottom of the demonstration screen in real time.

This allows intuitive visualization of public opinion balance.

---

## 5. 参加資格と示威行動の実施範囲 / Eligibility and Protest Scope

### [JP]
- 参加は国内在住者を前提とする  
- 発言は国内で使用される国語に限定する  
- **示威行動は国内でのみ実施する**

扱う議題（テーマ）は国内問題に限定しない。  
たとえば、日本のサイトにおいて  
ウクライナ侵攻に抗議する意思表示を行うことは可能である。

ただし、示威行動を他国の仮想空間（例：赤の広場など）で実施しない。  
これは、参加者が国外の権力や攻撃対象となるリスクを避けるためである。

### [EN]
- Participation is limited to residents within the country  
- Statements must be made in the national language  
- **Demonstrations are conducted only within the domestic virtual space**

The subject matter of demonstrations is not limited to domestic issues.  
For example, participants on a Japanese platform may express opposition  
to the invasion of Ukraine.

However, demonstrations are not conducted in foreign symbolic locations  
(e.g., Red Square).  
This restriction exists to reduce the risk of participants  
becoming targets of external authorities or attacks.---

## 6. 参加方法と属性選択 / Participation and Attributes

### [JP]
参加時に以下を選択・記入します。

a. ハンドルネーム  
- 12文字以内  
- 本名および本名を想起させるものは禁止  
- AIモデレーターによる重複チェックを行う  

b. 年齢層  
- u18 / 18–39 / 40–64 / 65u  
- 国内法に抵触しない範囲で設定  

c. 性別  
- 男 / 女 / non  

d. 居住地域  
- 州・地方など  

e. 主張テキスト  
- 80文字以内  
- AIモデレーターによる内容チェックを実施  

### [EN]
Participants provide the following:

a. Handle name  
- Up to 12 characters  
- Real names or identifiable names are prohibited  
- Checked for duplication by AI moderator  

b. Age group  
- u18 / 18–39 / 40–64 / 65u  
- Must comply with domestic laws  

c. Gender  
- Male / Female / Non-binary  

d. Region of residence  

e. Statement text  
- Up to 80 characters  
- Content checked by AI moderator

### 6-2. Privacy Compliance & Data Protection (プライバシー保護と法規制への適合)

To ensure the safety of participants and comply with global privacy standards such as the **CCPA (California Consumer Privacy Act)** and **GDPR**, this protocol implements "Privacy by Design."
参加者の安全を確保し、カリフォルニア州消費者プライバシー法（CCPA）やGDPRなどの国際的なプライバシー基準に準拠するため、本プロトコルは「プライバシー・バイ・デザイン」を実装します。

*   **Statistical Anonymity (統計的匿名性):** 
    Age data is collected only in broad ranges (18-39 / 40-64 / 65+). This granular level makes "re-identification" (identifying a specific individual) mathematically impossible when combined with gender and state.
    年齢データは広範な区分（18-39歳 / 40-64歳 / 65歳以上）でのみ収集されます。この粒度は、性別や居住州と組み合わせても、数学的に特定の個人を再識別（名寄せ）することを不可能にします。
*   **Zero-IP Retention (IPアドレスの不保持):** 
    The system is designed to decouple and discard the user's IP address at the moment of attribute submission. No logs that could link an individual to an avatar are maintained.
    システムは、属性データが送信された瞬間にIPアドレスを切り離し、破棄するように設計されています。個人とアバターを結びつけるログは一切保持されません。
*   **Compliance (法規制への適合):** 
    Since the data collected does not constitute "Personal Information" under CCPA/CPRA, it is exempt from "Right to Opt-Out" requests, ensuring the stability of the statistical protest data.
    収集されるデータはCCPA/CPRAにおける「個人情報」の定義に該当しない非識別化データであるため、「個人情報の販売停止権」等の対象外となり、統計的な示威データの安定性が保たれます。

---

## 7. アバター仕様 / Avatar System

### [JP]
数十種類のアバターを提供します。

- 真面目なもの  
- ユーモラスなもの  
- 著作権を侵害しないデフォルメヒーロー  
- 擬人化された動物  
- 民族衣装 など  

各アバターは3〜4種類の動作を持つ静止画で構成され、  
最終画像には吹き出し形式で主張テキストを表示します。

詳細はIssueにて議論・記載します。

### [EN]
Dozens of avatars are provided, including:

- Serious styles  
- Humorous styles  
- Non-copyright-infringing stylized heroes  
- Anthropomorphized animals  
- Traditional ethnic costumes  

Each avatar consists of 3–4 static poses,  
with the final image displaying the statement in a speech bubble.

Details are discussed in Issues.

---

## 8. デモ・集会の時間管理 / Time and Cell Management

### [JP]
- 受付開始：現地時間 10:00  
- 示威行動時間：18:00–20:00  

50人を1セルとして管理し、  
満杯になり次第、次のセルへ移行します。

### [EN]
- Registration opens at 10:00 local time  
- Demonstrations run from 18:00 to 20:00  

Participants are grouped into cells of 50.  
Once a cell is full, a new one is created.

---

### 9. パレードの視覚的設計と能動的参加 / Visual Design & Active Engagement

> [!IMPORTANT]
> **A. 意見の混在による分断の解消と統計の可視化 / Mixed Opinions & Statistical Clarity**
>
> * **JP:** 各セル内では、賛成・反対・注視（Observe）のアバターが分け隔てなく混在して表示されます。視覚的な分断（エコーチェンバー）を避ける一方で、**各項目の正確な集計実態は、常に下段のリアルタイム・バー（項目4参照）によって一目で把握できる**設計となっています。
> * **EN:** Within each cell, **YES, NO, and OBSERVE** avatars march together. While avoiding visual polarization, the **precise statistical breakdown is always clearly visible on the real-time bar at the bottom (see item 4)**.

> [!TIP]
> **B. クリックによる意思表示の証明 / Engagement via Clicking (Anti-Bot)**
>
> * **JP:** アバターは、ユーザーにクリック（タップ）されることで動作し、個人の主張（吹き出し）を表示します。これにより、単なる数値だけでなく、放置アカウントや自動ボットではない「生きた人間の積極的な関与」であることを証明します。
>
---

## 10. 反暴力AIモデレーション / Transparent AI Moderation

### [JP]
AIモデレーターが発言をリアルタイムで監視します。

- 暴力的表現に対しては「書き直し」を推奨  
- 物理的・言語的暴力を排除  
- 規制内容は明示する  

### [EN]
AI moderators monitor statements in real time.

- Violent expressions trigger rewrite suggestions  
- Physical and verbal violence are excluded  
- Moderation rules are made transparent  

---

## 11. プライバシー設計 / Privacy by Design

### [JP]
デモ終了後、  
性別・年齢層・居住地などの統計データを除き、  
すべての個人識別情報および発言ログを即時破棄します。

### [EN]
After the demonstration ends,  
all personally identifiable information and statements are deleted immediately,  
except for aggregated statistical data such as gender, age group, and region.

### 11.x. Advanced Roadmap for Privacy & Resilience / プライバシーと堅牢性のための高度なロードマップ

To achieve both "complete anonymity" and "democratic integrity" at a professional technical level, we are exploring the following four-pillar implementation strategy:  
（「完全な匿名性」と「民主的な整合性」をプロフェッショナルな技術水準で両立させるため、以下の4つの柱からなる実装戦略を検討しています。）

*   **Absolute Anonymity via Zero-Knowledge Proofs (ZKP) / ゼロ知識証明による絶対的な匿名性:**  
    We aim to adopt [Zero-Knowledge Proofs (ZK-SNARKs)](https://ethereum.org) to allow users to prove they are "valid participants" without revealing their identity, metadata, or IP addresses to the server.  
    （[ゼロ知識証明](https://ja.wikipedia.org)を導入し、サーバーにアイデンティティやIPアドレスを明かすことなく、「正当な参加者であること」のみを数学的に証明する仕組みを目指します。）

*   **Anti-Bot Measures via Client-side PoW (Proof of Work) / クライアントサイドPoWによるボット対策:**  
    By requiring a few seconds of computation (e.g., [Hashcash](https://en.wikipedia.org)) before submission, we can drastically increase the cost for bots without collecting any personal data. This ensures the system remains open to human users while neutralizing mass-attack attempts.  
    （投稿前に数秒の計算処理（[Hashcash](https://ja.wikipedia.org)等）を要求することで、個人情報を収集せずにボットによる攻撃コストを劇的に高め、大量投稿を無効化します。）

*   **Double-Submission Prevention via Nullifiers / ヌルファイアによる二重投稿の排除:**  
    To ensure "one person, one voice" without compromising anonymity, we plan to implement a mechanism (Nullifiers) that detects repeated use of the same anonymous credential within a single protest session.  
    （匿名性を保ったまま「一人一票」を保証するため、特定のデモ内で同じ匿名資格が二度使われることを検知する仕組み（ヌルファイア）を導入します。）

*   **Transparent AI Moderation / AIによる透明性の高いモデレーション:**  
    To avoid human censorship, we will utilize open-source AI models to flag prohibited content based on community-defined guidelines, ensuring neutral and explainable moderation.  
    （人間による検閲を避けつつ、コミュニティが合意したガイドラインに基づき、オープンソースAIが中立かつ説明可能な形で不適切な内容をチェックします。）

---

## 12. 運営方針・国別仕様 / Operation Model

### [JP]
- 米国以外はNPO方式で運営  
- 米国版は収益確保を目指す  
- 運営費を除いた収益は、他国・地域サイトの支援に充当  

連帯の象徴として、  
各国サイトのURLは  
`voice-of-{nation}` 形式を推奨します。

示威行動の事案は運営側が提示し、  
原則として複数の大手新聞に掲載されたトピックを対象とします。

### [EN]
- Operated as an NPO outside the United States  
- The U.S. version aims for revenue generation  
- Profits beyond operating costs support other regions  

As a sign of solidarity,  
the URL format `voice-of-{nation}` is recommended.

Demonstration topics are proposed by operators  
and generally limited to issues covered multiple times by major newspapers.

---

## 13. 米国版仕様（概要） / U.S. Version Overview

### [JP]
米国にはVOAが存在するため、  
名称は  
**Virtual Demo & Rally @ Home [Will of America]**  
とします。

収益構造：
- ドネーション  
- アドセンス  
- デモ経路画像への企業広告掲載  
  （選挙・戦争・内紛などセンシティブ案件では不可）

属性付き参加データは、  
研究機関やメディアへの提供・販売対象となり得ます。

- 属性：性別／年齢層／居住州  
- 支持政党は取得しない  
- 参加資格は18歳以上  

### [EN]
Due to the existence of VOA, the U.S. version is titled  
**Virtual Demo & Rally @ Home [Will of America]**.

Revenue sources include:
- Donations  
- AdSense  
- Corporate ads placed on demonstration route images  
  (excluded for sensitive issues such as elections or wars)

Attribute-based participation data may be provided or sold  
to research institutions and media.

- Attributes: gender, age group, state  
- Political party affiliation is not collected  
- Participants must be 18 years or older  

---

### 14. 開発協力・パートナーシップの呼びかけ / Call for Collaboration & Partnership

**[JP]**
私は技術の専門家ではありません。しかし、2013年から福島第一原発の除染や構内作業、そして賠償相談窓口の最前線に立ち、社会の「分断」と「沈黙」を10年以上見つめ続けてきました。

このプロトコルのビジョンに共感し、誰もが「コスト」や「リスク」を恐れずに、かつ安全に声を上げられる社会をOSS（オープンソース）として共に実装してくれるエンジニアを求めています。また、個人の志を越えて、この仕組みの「受け皿」となり、共に社会実装を推進してくださる支援団体やNPOからのご連絡を心よりお待ちしています。

**[EN]**
I am not a technical specialist. However, since 2013, I have spent over a decade on the front lines of Fukushima?from decontamination and on-site work at the nuclear power plant to the compensation counseling desk?witnessing the "division" and "silence" of our society firsthand.


## 立案者について / About the Author

### [JP]
75歳の元魚屋。  
日本の初期ネット文化を象徴する作品の一つである「Crimson Room」のプロデューサー。  
現在は、福島第一原発事故に関する賠償窓口業務に従事しています。

これまでの経験から、次世代には「格差」や「分断」ではなく、  
誰もが等しく意思を表明し、対立を暴力ではなく合意へと編み直していくための  
**公共の広場**を残したいと考えています。
連絡先：fishspr0038@yahoo.co.jp

---

### [EN]
A 75-year-old former fishmonger.  
Producer of *Crimson Room*, one of the landmark works of Japan’s early internet culture.  
Currently engaged in compensation support work related to the Fukushima Daiichi nuclear power plant accident.

Based on these experiences, I hope to leave the next generation not a society defined by inequality and division,  
but a **public forum** where everyone can express their will on equal footing  
and work toward new forms of consensus without resorting to violence.
Contact:fishapr0038@yahoo.co.jp

## Current Issues / 現在の検討課題

Below are the core issues we are currently addressing to implement the Virtual Protest Protocol (VPP). We welcome your feedback and contributions.  
VPPの実装に向けて現在取り組んでいる主要な課題です。皆様のご意見と貢献を歓迎します。
＃1.[Backend/Policy] 二重投稿防止の実装 / Implementation of Double-Submission Prevention
＃2.Operational Policy for VPP (Virtual Protest Protocol)/運営方針：バーチャル・プロテスト・プロトコル（VPP）
＃3.ウェブサイト構成（案） / Website Structure Proposal
＃4.【募集】バーチャルデモを彩る「多様なアバター」のアイデア / [Brainstorming] Ideas for Diverse 2D Avatars
＃5.Avatar Image
＃6.Why I am building VPP: From the Frontlines of Fukushima to a New Tool for Democracy/なぜ私はVPPを創るのか：福島という現場から、民主主義のための新たな道具へ



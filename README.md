# Virtual Protest Protocol (VPP)

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
- u18 / 19–39 / 40–64 / 65u  
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
- u18 / 19–39 / 40–64 / 65u  
- Must comply with domestic laws  

c. Gender  
- Male / Female / Non-binary  

d. Region of residence  

e. Statement text  
- Up to 80 characters  
- Content checked by AI moderator  

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

## 9. 反暴力AIモデレーション / Transparent AI Moderation

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

## 10. プライバシー設計 / Privacy by Design

### [JP]
デモ終了後、  
性別・年齢層・居住地などの統計データを除き、  
すべての個人識別情報および発言ログを即時破棄します。

### [EN]
After the demonstration ends,  
all personally identifiable information and statements are deleted immediately,  
except for aggregated statistical data such as gender, age group, and region.

---

## 11. 運営方針・国別仕様 / Operation Model

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

## 12. 米国版仕様（概要） / U.S. Version Overview

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

## 13. 開発協力の呼びかけ / Call for Collaboration

### [JP]
私は技術の専門家ではありません。  
このプロトコルのビジョンに共感し、  
OSSとして社会実装を共に行う  
エンジニアおよび支援団体を求めています。

### [EN]
I am not a technical specialist.  
I am seeking engineers and organizations  
who share this vision  
and are willing to implement it as open-source software.

🕊️ VPP: Virtual Protest Protocol (v1.0)
This repository proposes **Virtual Protest Protocol (VPP)** —  
an open, non-partisan protocol for enabling anonymous, low-threshold civic expression in digital space.

本リポジトリは **Virtual Protest Protocol（VPP）** を提案するものです。  
VPP は、デジタル空間において **匿名かつ低負荷で市民的意思表明を可能にする、非党派的・オープンなプロトコル** です。

This specification is proposed in the context of growing challenges around in-person civic action and digital participation, including concerns about safety, accessibility, and social pressure.

本仕様は、対面でのデモや集会、ならびにデジタル空間での市民参加をめぐる課題  
（安全性、参加のしやすさ、社会的圧力など）が高まっている現状を背景として提案されています。

The following sections describe the background, design considerations, and draft specifications that motivated this proposal.
---

VPP is not a political campaign, organization, or platform.  
It is a **public protocol specification** designed to be implemented, adapted, or extended by any individual or organization with appropriate capacity and responsibility.

VPP は、特定の政治運動・団体・サービスではありません。  
本リポジトリは、**適切な能力と責任を有する個人・組織によって実装・改変・拡張されることを前提とした、公共的プロトコル仕様**を提示するものです。

---

The original proposer does not seek to retain ownership, leadership, or control.  
If this protocol proves useful, it is expected — and welcomed — that others will realize it in more suitable forms.

本プロトコルの提唱者は、所有権・主導権・管理権を保持することを目的としていません。  
本提案が有用である場合、**第三者によって、より適切な形で実装・発展されることを想定し、歓迎します。**
2D Avatar-based Digital Assembly System
🌟 Vision / プロジェクトの核心
「家から、アバターで、声を届ける。」

[EN] Realizing "Virtual Demos" where individuals can participate from home using 2D avatars to visualize collective will safely.

[JP] 家庭から2Dアバターを使って参加できる「仮想デモ・集会」を実現し、集団の意思を安全に可視化します。

🛠 Technical Specifications / 実装スペック
👤 2D Avatar Interface / アバター
Avatar Selection: デザイナー提供の数十種類から選択。安全性維持のため自作画像は不可。

Action & Message: 3〜4段階のモーション表示後、最後の画像に**「主張吹き出し（最大80字）」**を表示。

Handle Names: 最大10文字（本名不可）、アバターの頭上に表示。

📊 Visualization & Crowd / 群衆・統計
Dual-Crowd Formation: 「賛成・反対」の二つの巨大な群衆を構成。100人単位の「セル」管理で負荷を軽減。

Real-time Poll: 議題に対する「賛成・反対」数をリアルタイムでバー表示。

Attribute Sync: 属性（性別・年齢層・地域）を、アンケート機能へリアルタイムに反映。

🛡️ National Sovereignty & Safety / 主権維持と安全性
📍 Domestic Only / 国内限定: 各サイトはその国の在住者専用。舞台も国内の実在する場所に限定。

🚫 Non-Interference / 他国干渉の禁止: 参加者と場所を限定し、他国からの世論操作やサイバー攻撃を防御。

🔒 Privacy First / 非収集原則: 個人情報は徹底して非収集。匿名性を保ちつつ、ブラウザ指紋等で二重投稿を排除。

🌐 International Issues / 国際問題: 国際的なトピックについては、別のプロトコルに基づいた専用サイトで別途提供。

💰 Operational Models / 運営モデル
Standard Model (e.g., Voice of Japan) 連帯し、非営利（NPO）方式で運営。voice-of-{nation}.org 標準を採用。

US Model (Will of America) 「Voice of America (VOA)」の権利抵触を避けるため別名称を使用。持続性確保のため、企業スポンサー等を通じた営利・ハイブリッドモデルを検討。

📩 Contact / 連絡先
実装エンジニア、デザイナー、および協力団体を募集しています。

Advocate / 提唱者: [Otoya Aizawa / 相沢 乙矢)
Email: [fishspr@gmai.comE
GitHub Issues: Please open an issue for technical discussions.

MIT License | Virtual Protest Protocol Project

## 1. プロジェクト概要

本プロジェクトは、実空間での示威行動や集会への参加が
心理的・身体的・社会的・政治的理由により困難な人々を含め、
**匿名性と安全性を最大限に確保したうえで、
意思表示を可視化するオンライン・デモ／集会基盤**
を提供することを目的とします。

本システムは、意見の正誤や多数決を目的とするものではなく、
「存在している意思」を可視化し、社会的対話の前提条件を整える
ためのインフラとして位置づけられます。

---

## 2. 全体構造と参加構図

### 2.1 賛成・反対の二極構造

- デモ画面は「賛成」「反対」の2エリアで構成されます
- 参加者は、意思表示としていずれか一方を選択します
- 人数比はリアルタイムでバー表示されます

この構造は、討論や説得を目的とするものではなく、
**立場の分布を直感的に共有するための可視化**です。

アバター設計の基本方針（強調点）

本プロジェクトにおけるアバターは、
**個人を特定せずに意思表示を可視化するための「象徴的存在」**であり、
リアルな人物再現や自己表現の競争を目的としない。

実在人物・著作物を想起させない

年齢・性別・身体条件・文化背景の多様性を肯定する

真面目さとユーモアが共存する

主張そのものが前面に出るよう、アバターは「語りすぎない」

という点を設計の前提とする。

アバター画像カテゴリ案（概要）

※ 各カテゴリの「2」は
男女差・人種差を固定化しない複数バリエーションを意味する。

① 人の基本形（年齢層の可視化）

真面目な人物

子供 ×2

若者 ×2

大人 ×2

高齢者 ×2

② 移動・身体条件の多様性

乳母車

車椅子

自転車

スケートボード

③ 日常性・生活感

寝起きのパジャマ姿＋スリッパ

④ 動物（シンボリック）

鶏／鳩／鶴

嘴に「賛成」「反対」の旗を持つ

⑤ 動物（ユーモア・親しみ）

パンダ（口にプラカード）

象（鼻にプラカード）

拡声器を持つウサギ

犬・猫

⑥ デフォルメ・ヒーロー風（反権威的）

マント＋タイツ姿

胸に「賛成／反対」

マントに
「このマントでは飛べません」ロゴ

⑦ 不条理・匿名性の表現

逆立ち歩きのピエロ

段ボールを被った人

⑧〜⑩ 匿名性の段階表現

仮面の人

服と靴だけの透明人間

真っ黒な影のような人

⑪〜⑮ 比喩・寓意的存在

足が生えた大根・人参

花束を抱えた女性・少女

正義の天秤を持つ人

目玉が大きく、尻尾にトゲを持つ蜂

⑯〜⑰ 緊張と文化

軍服姿

民族衣装

（⑱〜⑳は将来拡張枠）

強調しておきたい思想的ポイント（重要）

可愛い／格好いい競争を起こさない

「誰が言ったか」ではなく
「どれだけの意思が集まったか」を見せる

笑いや違和感も、
言論参加のハードルを下げるための正当な要素と考える

技術仕様との切り分け（明確化）

本項は 思想・設計意図の整理であり

アバター画像の形式（静止画／動画／解像度等）は
### 実装リッファレンス にて別途定義する

補足（重要）

この書き方にしておくと、

デザイナー → 意図が分かる

技術者 → 実装自由度が確保される

外部協力者 → 「思想のあるプロジェクト」と理解できる

という三点が同時に成立します。
### 2.2 セル（Cell）構造による参加管理

- 参加者は 50〜100人単位の「セル」に自動的に割り当てられます
- セルが満員になると、新しいセルが生成されます
- ログイン時、参加者は自動的に自身のセルに配置されます
- 自分自身のアバターのみが強調表示されます

セル構造は、
- 群衆圧力の緩和
- 視認性の確保
- システム負荷の分散

を目的とした設計です。

---

## 3. アバター設計の思想

### 3.1 アバターの役割

アバターは「自己表現」ではなく、
**匿名性を保ったまま社会的存在として可視化されるための媒介**
として設計されます。

- 実在人物や著作物を想起させない
- 特定の政治思想・宗教・国家を象徴しない
- 風刺・多様性・ユーモアを許容する

ことを基本原則とします。

---

### 3.2 アバター仕様（概要）

- 運営側が提供する数十種類の2Dアバター
- 完全オリジナル（著作権非侵害）
- 各アバターは以下を持ちます：
  - 3〜4種類の静止画または短いループ動画
  - 最終フレームに主張テキスト用の吹き出し枠

---

### 3.3 アバター案（分類）

#### 人物系
- 子供／若者／大人／高齢者（各2）
- 乳母車・車椅子・自転車・スケートボード利用者
- パジャマ姿
- 仮面の人物／透明人間／影のような人物

#### デフォルメ・象徴系
- 鶏・鳩・鶴（嘴に賛否の旗）
- パンダ（口にプラカード）
- 象（鼻にプラカード）
- 拡声器を持つウサギ・犬・猫
- 足の生えた大根・人参
- 大きな目と棘の尾を持つ蜂

#### 風刺・寓話系
- マントとタイツ姿（胸に賛否、マントに「このマントでは飛べません」）
- 逆立ち歩きのピエロ
- 段ボールを被った人物
- 正義の天秤を持つ人物

#### 社会性・文化系
- 民族衣装
- 軍服姿（2種）

---

## 4. 投稿・参加条件

### 4.1 ハンドルネーム

- 10文字以内
- 本名不可
- アバター頭上に表示
- 二重投稿防止の補助情報として使用

---

### 4.2 主張テキスト

- 80字以内
- 吹き出しとして表示
- AIモデレーションによる事前チェック
- ハンドルネームクリックで再表示可能

---

### 4.3 属性選択（投稿条件）

以下は統計的可視化を目的とし、個人特定には使用しません。

- 性別：男／女／non
- 年齢層：u18／18–39／40–64／65u
- 居住地域：国内8地域区分

---

## 5. 運用ポリシー

### 5.1 扱うテーマの範囲

- 対象は国内問題に限定します
- デモの対象テーマは運営側が提示します
- 掲示板等での意見募集は参考情報とします

国際問題については、
別サイト・別基準・別言語で対応することを前提とします。

---

### 5.2 時間設計

- 10:00 参加受付開始
- 18:00 デモ開始
- 20:00 終了

時間を区切ることで、
継続的炎上や私的利用を防止します。

---

## 6. セキュリティと倫理設計

- 個人情報の収集は最小限に留めます
- 実名・連絡先・正確な位置情報は収集しません
- AIモデレーションにより暴力的・差別的表現を抑制します

ミャンマーや香港など、
言論弾圧の恐れがある地域の人々については、
日本在住の有志が代理で参加する仕組みを想定します。

この「システム提供そのもの」を
国際的な連帯行為として位置づけます。

---

## 7. 今後の検討課題

- 属性データを集計・可視化へどう反映させるか
- 有効な二重投稿防止手法
- AIモデレーションの精度と透明性
- セル単位集計と全体集計のUI整理

---

本仕様書は完成形ではなく、
**議論・協力・実装を呼び込むための叩き台**
として公開されます。


### 🛠️ Reference Implementation / 実装リファレンス
* **Avatar Engine**: 
    * [EN] Considering using **avtrigen** or similar SVG-based component systems for lightweight, customizable, and safe avatar generation.
    * [JP] 軽量かつ安全なアバター生成のため、**avtrigen** 等のSVGコンポーネントベースのシステムを技術候補として検討しています。
* **Motion & Customization**: 
    * [EN] Extending existing libraries to support 3-4 stage animations and custom designer assets (ethnic costumes, etc.).
    * [JP] 既存ライブラリを拡張し、3〜4段階のアニメーションやデザイナー制作のカスタムパーツ（民族衣装等）への対応を計画しています。

VPP: Virtual Protest Protocol (v1.0)
TL;DR / 要約（最重要）

[EN]
VPP (Virtual Protest Protocol) is an open, non-partisan protocol for enabling anonymous, low-threshold civic expression in digital space.

[JP]
VPP（Virtual Protest Protocol）は、デジタル空間において匿名かつ低負荷で市民的意思表明を可能にする、非党派的・オープンなプロトコルです。

1. Introduction / はじめに

[EN]
This repository proposes Virtual Protest Protocol (VPP) — an open, non-partisan protocol for enabling anonymous, low-threshold civic expression in digital space.

[JP]
本リポジトリは Virtual Protest Protocol（VPP） を提案するものです。
VPP は、デジタル空間において 匿名かつ低負荷で市民的意思表明を可能にする、非党派的・オープンなプロトコル です。

[EN]
This specification is proposed in the context of growing challenges around in-person civic action and digital participation, including concerns about safety, accessibility, and social pressure.

[JP]
本仕様は、対面でのデモや集会、ならびにデジタル空間での市民参加をめぐる課題
（安全性、参加のしやすさ、社会的圧力など）が高まっている現状を背景として提案されています。

2. Nature of the Project / プロジェクトの性格

[EN]
VPP is not a political campaign, organization, or platform.
It is a public protocol specification designed to be implemented, adapted, or extended by any individual or organization with appropriate capacity and responsibility.

[JP]
VPP は、特定の政治運動・団体・サービスではありません。
本リポジトリは、適切な能力と責任を有する個人・組織によって実装・改変・拡張されることを前提とした、公共的プロトコル仕様を提示するものです。

[EN]
The original proposer does not seek to retain ownership, leadership, or control.
If this protocol proves useful, it is expected — and welcomed — that others will realize it in more suitable forms.

[JP]
本プロトコルの提唱者は、所有権・主導権・管理権を保持することを目的としていません。
本提案が有用である場合、第三者によって、より適切な形で実装・発展されることを想定し、歓迎します。

3. Vision / プロジェクトの核心
「家から、アバターで、声を届ける。」

[EN]
Realizing "Virtual Demos" where individuals can participate from home using 2D avatars to visualize collective will safely.

[JP]
家庭から2Dアバターを使って参加できる「仮想デモ・集会」を実現し、
集団の意思を安全に可視化します。

4. Overall Structure / 全体構造
4.1 賛成・反対の二極構造

（※ 原文そのまま）

デモ画面は「賛成」「反対」の2エリアで構成されます
参加者は、意思表示としていずれか一方を選択します
人数比はリアルタイムでバー表示されます

この構造は、討論や説得を目的とするものではなく、
立場の分布を直感的に共有するための可視化です。

4.2 セル（Cell）構造による参加管理

（※ 原文そのまま）

参加者は 50〜100人単位の「セル」に自動的に割り当てられます
セルが満員になると、新しいセルが生成されます
ログイン時、参加者は自動的に自身のセルに配置されます
自分自身のアバターのみが強調表示されます

5. Avatar Design Philosophy / アバター設計の思想
5.1 基本方針（強調点）

（※ 原文そのまま）

本プロジェクトにおけるアバターは、
個人を特定せずに意思表示を可視化するための「象徴的存在」であり、
リアルな人物再現や自己表現の競争を目的としない。

5.2 アバター画像カテゴリ案（具体例・全文）

（※ ここがご指摘の核心部分：以下すべて原文）

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
嘴に「賛成」「反対」の旗

⑤ 動物（ユーモア）
パンダ（口にプラカード）
象（鼻にプラカード）
拡声器を持つウサギ
犬・猫

⑥ デフォルメ・ヒーロー風
マント＋タイツ
胸に「賛成／反対」
マントに「このマントでは飛べません」

⑦ 不条理・匿名性
逆立ち歩きのピエロ
段ボールを被った人

⑧〜⑩ 匿名性の段階
仮面の人
服と靴だけの透明人間
真っ黒な影

⑪〜⑮ 比喩・寓意
足の生えた大根・人参
花束を抱えた女性・少女
正義の天秤
目玉が大きく棘の尾を持つ蜂

⑯〜⑰ 緊張と文化
軍服姿
民族衣装

（⑱〜⑳ 将来拡張枠）

6. Security and Ethics / セキュリティと倫理

（※ 原文そのまま）

個人情報は徹底して非収集
匿名性を保ちつつ、ブラウザ指紋等で二重投稿を排除
ミャンマーや香港など言論弾圧地域については
日本在住の有志が代理参加する仕組みを想定

7. Regional Adaptation: United States
(US Model – Revenue-Enabled Variant)
7.1 Positioning of the US Model

[EN]
The United States model is treated as a special implementation of the Virtual Protest Protocol in which revenue generation is permitted.
All other countries are expected to adopt a non-profit (NPO/NGO-style) operational model.

[JP]
アメリカ合衆国モデルは、Virtual Protest Protocol の中でも 例外的に収益化を認める実装形態として位置づけられます。
それ以外の国・地域においては、NPO／NGO方式での非営利運営を原則とします。

7.2 Purpose of Revenue Generation

[EN]
Revenue generation in the US model is not intended for private profit.
After covering necessary operational and technical costs, surplus revenue will be allocated to the following purposes:

Financial and technical support for implementations in other countries

Development and maintenance of an international version of VPP addressing cross-national and global issues

Long-term operational sustainability, moderation, and security-related expenses

[JP]
USモデルにおける収益化は、私的利益を目的とするものではありません。
必要経費（運営費・技術費・セキュリティ関連費用等）を差し引いた後の収益は、以下の目的に充てられます。

他国における VPP 実装への資金的・技術的支援

国境を越える課題（気候変動、人権、戦争、難民など）を扱う 国際版 VPP の構築と維持

長期的な運営継続、モデレーション、セキュリティ確保に関する費用

7.3 Participation Modes

[EN]
Participants may select one of the following modes:

YES

NO

OBSERVE

OBSERVE does not indicate indifference.
It represents an intentional decision to witness, monitor, and acknowledge the issue without taking a binary position.

[JP]
参加者は以下のいずれかのモードを選択します。

賛成（YES）

反対（NO）

注視（OBSERVE）

OBSERVE は無関心を意味するものではなく、
問題を見届け、監視し、認識するという 積極的な意思表示を指します。

7.4 Revenue Structure (US Only)

[EN]
Permitted revenue sources in the US model include:

Voluntary donations

Advertising placed along virtual protest routes or environments

Use of fully anonymized and aggregated participation data for academic or policy research

The operating entity itself is not required to directly engage in commercial activity.

[JP]
USモデルにおいて認められる収益源は以下の通りです。

任意の寄付

仮想デモ空間・仮想ルート沿いに配置される広告

完全匿名化・統計化された参加データの学術・政策研究用途への提供

なお、運営主体が直接的な営利活動を行うことを必須とはしません。

7.5 Avatar Licensing and Cultural Circulation

[EN]
Popular or symbolic avatars may be licensed for third-party use, including merchandise or media representation.
Such licensing is intended to support sustainability without compromising anonymity or political neutrality.

[JP]
人気や象徴性を持つアバターについては、
第三者による商品化・メディア利用を許諾することが想定されます。
これは匿名性および政治的中立性を損なわない形で、持続可能性を支えるための仕組みです。

7.6 Age Groups and Eligibility

[EN]
Participants are categorized into the following age groups for visualization and statistical purposes:

13–17

18–39

40–64

65+

Individuals under the age of 13 are not eligible to participate in the system.

[JP]
参加者は、可視化および統計処理のため、以下の年齢層に分類されます。

13〜17歳

18〜39歳

40〜64歳

65歳以上

13歳未満の参加は対象外とします。

7.7 Ethical Note

[EN]
The US model is designed to coexist with non-profit implementations worldwide.
Revenue is treated as a means to reinforce global civic infrastructure, not as an end in itself.

[JP]
USモデルは、世界各国の非営利実装と共存することを前提としています。
収益は目的ではなく、グローバルな市民的基盤を支えるための手段として位置づけられます。

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

### 🛠️ Reference Implementation / 実装リファレンス
* **Avatar Engine**: 
    * [EN] Considering using **avtrigen** or similar SVG-based component systems for lightweight, customizable, and safe avatar generation.
    * [JP] 軽量かつ安全なアバター生成のため、**avtrigen** 等のSVGコンポーネントベースのシステムを技術候補として検討しています。
* **Motion & Customization**: 
    * [EN] Extending existing libraries to support 3-4 stage animations and custom designer assets (ethnic costumes, etc.).
    * [JP] 既存ライブラリを拡張し、3〜4段階のアニメーションやデザイナー制作のカスタムパーツ（民族衣装等）への対応を計画しています。

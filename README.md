# Open Digital Protest Protocol (ODPP）

**「沈黙を破り、次世代に反撃の場を」**
 このプロジェクトは、1950年生まれの私（発起人）が、これからの格差社会と負債を背負わせてしまった若い世代への責任と、深い悔恨の念から立ち上げたものです。
「日本の声（Voice of Japan）」は、日本に住む若者、そしてミャンマーや香港など、自由を求めて闘うすべての人々が、物理的な制約を超えて「安全に、かつ効果的に」声を上げられるデジタル・プラットフォームを目指しています。

"Breaking the Silence: Providing a Platform for Resistance to the Next Generation"**
 
 This project was launched by the founder (born in 1950) out of a deep sense of responsibility and regret toward the younger generation. "Voice of Japan" aims to provide a digital platform where young people in Japan—as well as those fighting for freedom in Myanmar, Hong Kong, and beyond—can raise their voices "safely and effectively."

  🕊️ 私たちの目的 / Our Mission
1. **反撃のツールの提供 / Empowerment**: 既存の社会構造の中で声を上げにくい人々に、デジタルな「武器（言葉と連帯）」を提供します。
2. **国境を超えた連帯 / Global Solidarity**: ミャンマーや香港など、民主主義を希求する人々へ支援と場を提供します。 (Providing a space 　　for those seeking democracy in Myanmar, Hong Kong, and beyond.)
3. **フルスペック・オープンソース / Open Source**: この仕組みは誰のものでもありません。より良いものにしてくれる主体を歓迎します。 (We 　　welcome anyone who wishes to take the lead and improve this system.)
 
 [Official Website: 日本の声 (Voice of Japan)](https://voice-of-japan.net)

## 1. Purpose & Vision

The Open Digital Protest Protocol (ODPP) defines a **non-violent, anonymous, visual-first method** for expressing political stances in a digital environment.

Its purpose is **not debate, persuasion, or mobilization**, but the **aggregation and visualization of otherwise unheard voices**, especially from individuals who face social, psychological, or structural barriers to participation in offline demonstrations.

ODPP is designed as a **protocol, not a service**. Any organization, community, or developer may implement it independently.

---

## 2. Scope & Constraints

* **Issue Scope**: Domestic political and social issues only
* **Language**: Japanese
* **Eligibility**: Residents within Japan
* **Non-goals**:

  * No calls for violence
  * No recruitment or organization of real-world actions
  * No threaded discussions or debates

These constraints are intentional and serve as **security, safety, and de-escalation measures**, not ideological limitations.

---

## 3. Core Principles

1. **Non-violence by design**
   Expression is symbolic and visual; no operational coordination is possible.

2. **Symmetry of positions**
   All issues must allow both support and opposition under identical conditions.

3. **Anonymity with minimal accountability**
   Users are not identifiable, yet duplicate participation is discouraged.

4. **Limited expressiveness**
   Constraints on text length and representation reduce escalation and abuse.

5. **Visualization over amplification**
   ODPP prioritizes collective visibility rather than individual virality.

---

## 4. Participation Flow (Mandatory)

### Step 1: Position Selection

Participants must choose one of the following positions:

* **Support**
* **Oppose**

Results are displayed as a **real-time visual bar indicator**, representing relative proportions rather than precise vote counts.

---

### Step 2: Avatar Selection

Participants select an avatar from a predefined set provided by the implementation.

Avatar design guidelines:

* Politically neutral by default
* Copyright-safe
* Categories may include:

  * Serious / formal
  * Humorous / light-hearted
  * Stylized heroes (non-derivative)
  * Anthropomorphized animals

Each avatar includes **3–4 static images or short looping animations**.

The final state displays a **speech-bubble-style overlay** containing the participant’s statement.

---

### Step 3: Handle Name

* Up to **10 characters**
* Must not be a real name
* Used only within a single issue context

The handle name exists to provide **minimal continuity**, not identity.

The protocol prioritizes **one-expression-per-person-per-issue**, not persistent personas.

---

### Step 4: Statement Text

* Maximum **80 characters**
* Plain text only
* No images, links, or emojis

The statement is visually bound to the selected avatar.

This limitation is intentional to emphasize **stance over rhetoric**.

---

## 5. Optional Attributes (Strongly Recommended as Optional)

The following attributes may be requested **optionally** and must be:

* Voluntary
* Stored anonymously
* Used only for **aggregated statistical visualization**

### Optional Attributes

* Gender: Male / Female / Non-binary
* Age group: U18 / 18–39 / 40–64 / 65+
* Region: One of 8 predefined domestic regions

These attributes **must not be required** for participation.

---

## 6. Visualization Rules

* No ranking of individual statements
* No highlighting of extreme positions
* No algorithmic promotion

All visualizations should reinforce the idea of **collective presence**, not competition.

---

## 7. Abuse Prevention & Moderation Philosophy

ODPP does not rely on punitive moderation.

Core approach:

* Structural limitations over behavioral enforcement
* Short text limits reduce harassment
* No reply or quote functionality

AI-assisted moderation may be used **only** to:

* Detect explicit threats
* Remove hate speech
* Enforce length and format rules

No ideological filtering is permitted.

---

## 8. Security & Risk Awareness

The protocol is intentionally designed to:

* Avoid geopolitical targeting
* Minimize coordinated manipulation
* Reduce incentives for mass harassment

Domestic-only scope is a **defensive design choice**, not a political stance.

---

## 9. Open Source & Licensing

ODPP is intended to be released under a **permissive open-source license** (e.g., MIT or Apache 2.0).

No central authority governs implementations.

Forking, localization, and modification are explicitly encouraged, provided that the **core principles are preserved**.

---

## 10. Final Note

ODPP is not a platform for shouting louder.

It is a protocol for **being counted without being exposed**.

The protocol exists so that participation itself becomes visible—without demanding courage, charisma, or conformity.

Contact：fishspr0038@yahoo.co.jp　URL：voice-of-japan.net

## Detailed System Vision: "The Endless March"

To realize a truly impactful digital protest, the system will focus on the following visual and technical specifications:

### 1. Visual Perspective & Scalability
* **Side-Scrolling View:** The primary view will be a side-profile of the march, creating a sense of an endless, powerful stream of people.
* **Cell-Based Architecture:** Avatars are managed in "units" (cells) of 50 to 100 individuals. By repeating and layering these units, the system can visualize a massive protest of **10,000 to 100,000+ participants** without overloading the browser.
* **Animation:** Each avatar will have 3-4 frames of walking animation to create a lifelike movement.

### 2. Avatar Diversity & Interaction
* **Diverse Categories:** We provide dozens of avatar types to represent social diversity, including:
    * Serious/Professional styles
    * Playful/Humorous characters
    * Animal personifications
    * Traditional/Ethnic costumes
    * Non-copyright-infringing "Hero" archetypes
* **Individual Voice:** Each avatar displays a Handle Name above its head. Clicking the name triggers a **speech bubble** containing the user’s specific text-based opinion.

### 3. Data & Sentiment Visualization
* **Sentiment Bar:** A visual indicator at the bottom of the screen showing the ratio of "Pros" and "Cons" based on the latest data cutoff.
* **Moderation:** Integration with AI (e.g., OpenAI API) to ensure a safe environment by filtering hate speech and defamation.

---
I am looking for developers who can help build this "Cell-based Side-Scrolling Engine" using modern web technologies like WebGL, Three.js, or advanced Canvas API.

Subject/Headline: A Safe Way to March: Virtual Protest Protocol for Myanmar and Hong Kong

To my friends in Myanmar, Hong Kong, and everywhere fighting for democracy,

I am an activist in Japan developing the "Virtual Protest Protocol." I believe that even if they take away our streets, they cannot take away our voices.

I am building a system where tens of thousands can march together safely using Avatars.

Why this is for you:

Safety First: March anonymously using avatars to protect your identity from surveillance.

Strength in Numbers: Visualize a march of 100,000+ people to show the world we are still here.

Global Solidarity: A platform where people from Japan and the world can join your march in a digital space.

GitHub: https://github.com/voice-of-japan/Virtual-Protest-Protocol

I am looking for collaborators to implement this. Once this system is ready, we will march together in the digital world. You are not alone.

#StandWithMyanmar #StandWithHongKong #MilkTeaAlliance #DigitalDemocracy

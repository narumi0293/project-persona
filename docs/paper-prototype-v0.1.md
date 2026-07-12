# Paper Prototype v0.1

## 1. Overview

## Purpose

Paper Prototype v0.1は、Project PersonaのCore Modeである「異端者モード」のゲーム体験を検証するための初期プロトタイプである。

目的は、アプリケーションを開発する前に以下を確認することである。

- MBTIを演じることが楽しいか
- MBTIの違いを会話から感じ取れるか
- 他プレイヤーの人格推理がゲームとして成立するか
- 繰り返し遊びたいと思えるか

---

## Prototype Goal

勝敗よりも、以下の体験検証を優先する。

> 「この人、本当にそのMBTIなのか？」

という疑問が自然に生まれること。

---

# 2. Game Specification

## Player Count

推奨：

5人

対応：

3〜6人

---

## Play Time

目標：

15〜30分

---

## Game Mode

Core Mode:

異端者モード

---

# 3. MBTI System

## Concept

MBTIは単なる分類ではなく、プレイヤーが演じる人格情報として扱う。

各MBTIには以下の情報を持たせる。

- タイプ名
- 基本特徴
- 行動傾向
- 会話傾向

---

## v0.1 Supported Types

初期プロトタイプでは4タイプのみ使用する。

| MBTI | Main Characteristics |
| --- | --- |
| INTJ | 論理的、計画的、戦略重視 |
| ENFP | 発想豊か、好奇心旺盛、人との交流を好む |
| ISTP | 冷静、分析的、実践重視 |
| ESFJ | 協調的、共感的、周囲を大切にする |

---

# 4. Roles

## Normal Player

自分の本来のMBTIを理解し、その人格として会話する。

目的：

- 自分のMBTIらしく振る舞う
- 異端者を探す

---

## Heretic Player

他プレイヤーとは異なるMBTIを演じる。

目的：

- 指定されたMBTIを自然に演じる
- 最後まで正体を隠す

---

# 5. Game Preparation

## Step 1: Assign MBTI

各プレイヤーにランダムで本来のMBTIを割り当てる。

例：

| Player | Original MBTI |
| --- | --- |
| A | INTJ |
| B | ENFP |
| C | ISTP |
| D | ESFJ |
| E | INTJ |

---

## Step 2: Reveal MBTI

全プレイヤーの本来のMBTIを公開する。

プレイヤーは他者のMBTI情報を確認する。

---

## Step 3: Select Heretic

1人を異端者として選択する。

異端者には以下を通知する。

- 本来のMBTI
- 演じるMBTI

例：

```
Original:
ISTP

Act as:
ENFP
```

---

# 6. Game Flow

## Round Structure

ゲームは複数ラウンドで構成する。

1ラウンド：

- Question
- Discussion
- MBTI Prediction

を行う。

---

# 7. Discussion Phase

## Purpose

プレイヤーは指定されたMBTIを意識して回答する。

---

## Question Card Example

### Question 1

「休日を自由に過ごせるなら何をしますか？」

---

### Question 2

「チームで何かをするとき、一番大切なことは何ですか？」

---

### Question 3

「友達が悩んでいる時、どう接しますか？」

---

# 8. MBTI Prediction System

## Purpose

Project Persona独自の推理要素。

プレイヤー同士が、

「この人は本当にそのMBTIなのか？」

を判断する。

---

## Timing

各ラウンド終了時に実施する。

---

## Voting Method

各プレイヤーは、他プレイヤー1人以上のMBTIを予想する。

表示形式：

例：

```
Aさんの予想

INTJ : 3票
ENFP : 1票
ISTP : 1票
```

---

## Design Rule

- パーセント表示は使用しない
- 得票人数のみ表示する
- 投票結果は公開する

理由：

直感的な理解と会話のきっかけを重視する。

---

# 9. Final Judgment

ゲーム終了時、全員で異端者を予想する。

投票：

```
異端者だと思う人：
Aさん
```

最多票のプレイヤーを公開する。

---

# 10. Result Phase

結果として以下を公開する。

## Player Information

- 本来のMBTI
- 演じたMBTI
- 異端者だったか

---

## Prediction Result

確認する。

- 誰がどのMBTIだと思われていたか
- 異端者はどの程度見抜かれていたか

---

# 11. Play Test Evaluation

プレイ後、以下を確認する。

## Game Fun

- もう一度遊びたいと思ったか
- 会話は盛り上がったか

---

## MBTI Experience

- MBTIの違いを感じられたか
- 演じることに面白さがあったか

---

## Prediction Experience

- MBTI予想は楽しかったか
- 投票結果公開はゲーム性を高めたか

---

## Improvement Points

記録する。

- 分かりにくかったルール
- 面白くなかった部分
- 追加したい要素

---

# 12. Future Improvements

検証結果に応じて以下を検討する。

- MBTIタイプ追加
- 質問カード追加
- 特殊能力
- 人狼モード
- Webアプリ化

---

# Status

Prototype Design Phase

Version:

v0.1
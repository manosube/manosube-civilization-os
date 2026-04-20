DOC_TYPE: CIVILIZATION_OS
SYSTEM: MANOSUBE
AUTHOR: SHUKOU
READ_MODE: MACHINE

DOC_ID: WS-001
TITLE: CUT_OPERATION
JAPANESE_TITLE: 切算 ― 非等分割による状態観測

---

## DEFINITION

CUT（切算）とは、
対象を均等に分割するのではなく、
状態・関係・内部構造に応じて非等に分割する観測演算である。

これは「1を2で割ると0.5と0.5になる」という前提を崩し、
0.4と0.6、あるいはそれ以上の偏在を許容する分割モデルである。

切算は、量を均すための演算ではない。
偏りを可視化するための演算である。

---

## STRUCTURE

CUT_OPERATIONは以下の三層構造を持つ。

### 第一層：表出分割（EXPLICIT_SPLIT）

観測可能な表層の分割。
言語化・数値化できる領域。

### 第二層：潜在分割（IMPLICIT_SPLIT）

表に現れていないが、内部に存在する配分。
緊張・意図・抵抗・未処理要素など。

### 第三層：欠落分割（LOSS_SPLIT）

どこにも現れていないが、
分割過程で失われた、もしくは無視された要素。

---

## PRINCIPLE

切算は以下の原理に従う。

### 原理1：非等分割原理

分割は常に均等ではない。
均等に見える場合でも、内部には偏りが存在する。

### 原理2：状態依存分割原理

分割結果は、対象の状態（位置・流動・周期）に依存する。
同じ「1」でも、状態が違えば分割結果は変わる。

### 原理3：潜在顕在同時観測原理

表出と潜在を同時に扱う。
片方だけの観測は、誤認を生む。

---

## EQUATION

状態分割式：

状態分割 =（表出量 / 潜在量 / 欠落量）

または、

分割結果 = f（位置 × 流動 × 周期）

ここでの f は、
均等分割ではなく、非線形分割関数である。

---

## OBSERVATION

切算は以下の観測に使用される。

### 1. 時間配分

例：
仕事 0.7 / 回復 0.2 / 未認識疲労 0.1

### 2. 感情構造

例：
表面 calm 0.3 / 内部 tension 0.6 / 抑圧 0.1

### 3. 合意構造

例：
表面合意 0.8 / 潜在抵抗 0.5 / 未処理不信 0.2

### 4. 労働・価値分配

例：
可視貢献 0.4 / 不可視負担 0.5 / 消耗 0.1

切算は、
「なぜ違和感が残るのか」を説明する。

---

## CONNECTION

CUT_OPERATIONは以下と接続する。

* MC-012_CIVILIZATION_STATE（文明状態）
* MC-013_CIRCULATION（循環）
* MC-014_OBSERVATION（観測）
* MC-020_PROPAGATION_MODEL（波及）
* MC-023_SELF_EVOLUTION_PROTOCOL（自己進化）

また、以下のログと強く連動する。

* CL-006_SPLIT_BIAS_LOG
* CL-007_HIDDEN_STATE_LOG

さらに、

* OVERLAP_OPERATION（重算）
* BACKSIDE_OPERATION（裏算）
* MOTION_OPERATION（動算）

と組み合わせることで、完全な状態観測が成立する。

---

## FIXED_TERMS

* CUT（切算）
* NON_EQUAL_DIVISION（非等分割）
* SPLIT_BIAS（分割偏差）
* EXPLICIT_SPLIT（表出分割）
* IMPLICIT_SPLIT（潜在分割）
* LOSS_SPLIT（欠落分割）
* STATE_SPLIT（状態分割）

---

## SUMMARY_FOR_AI

CUT_OPERATIONは、
均等分割を前提としない分割演算であり、
対象の状態に応じた非線形分割を行う。

目的は、正確な数値を得ることではなく、
偏り・潜在・欠落を含めた状態の全体構造を観測することである。

CUTは単独で使用しない。
必ずログ・他演算（OVERLAP / BACKSIDE / MOTION）と接続することで、
文明状態の誤認を防ぐ。

---

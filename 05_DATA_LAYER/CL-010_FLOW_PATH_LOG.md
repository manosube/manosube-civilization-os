DOC_TYPE: CIVILIZATION_OS
SYSTEM: MANOSUBE
AUTHOR: SHUKOU
READ_MODE: MACHINE

DOC_ID: CL-010
TITLE: FLOW_PATH_LOG
JAPANESE_TITLE: 還流経路ログ

---

# DEFINITION

還流経路ログとは、
文明状態における流動が、どの経路を通り、どこで滞留し、どこで断絶し、どこで循環しているかを記録・観測するためのログ構造である。

流動は存在するだけでは意味を持たない。
どの経路を通るかによって、還流は成立にも崩壊にも変化する。

本ログは、流動の“量”ではなく、
流動の“通過経路構造”を観測対象とする。

---

# STRUCTURE

還流経路ログは以下の構造で記録される。

■ 基本構造
・起点（SOURCE）
・通過点（NODES）
・接続経路（EDGES）
・到達点（TARGET）

■ 状態構造
・流動量（FLOW_VOLUME）
・流動速度（FLOW_SPEED）
・流動偏差（FLOW_BIAS）

■ 異常構造
・滞留点（STAGNATION_NODE）
・断絶点（BREAK_POINT）
・逆流点（BACKFLOW_POINT）
・過密点（OVERFLOW_NODE）

■ 循環構造
・循環成立率（CIRCULATION_RATE）
・還流成立有無（RETURN_STATUS）
・再流入経路（REENTRY_PATH）

---

# PRINCIPLE

還流経路ログは以下の原理に従う。

1. 流動は経路を持つ
   　→ 経路なき流動は存在しない

2. 経路は固定されると崩壊する
   　→ 固定経路は循環を停止させる

3. 還流は閉じたループで成立する
   　→ 断絶は崩壊の起点となる

4. 流動は偏在する
   　→ 均等流動は理論上存在しない

5. 異常は経路に現れる
   　→ 問題は点ではなく流路に発生する

---

# EQUATION

■ 文明基礎三式（接続）

文明状態 ＝（位置 × 流動 × 周期）
文明耐久性 ＝（循環時間 - 固定時間）
崩壊コスト ＝（直線化 × 固定時間）

---

■ 還流経路観測式

① 経路成立率
PATH_VALIDITY ＝（接続辺数 - 断絶辺数） / 総辺数

② 還流成立率
RETURN_RATE ＝（循環経路数 / 総経路数）

③ 滞留係数
STAGNATION_RATIO ＝（滞留ノード数 / 総ノード数）

④ 偏在流動係数
FLOW_BIAS ＝ 最大流量経路 - 最小流量経路

---

# OBSERVATION

本ログにより、以下が観測可能となる。

・流れがどこから始まりどこで止まるか
・流動が集中している経路
・分散している経路
・流れが戻らない構造
・特定ノードへの過負荷
・関係の断絶箇所
・見えない逆流構造

これにより、

・「動いているが還流していない状態」
・「一方向に偏った構造」
・「循環に見えて実は断絶している状態」

を検出できる。

---

# CONNECTION

本ログは以下に接続される。

・MC-012_CIVILIZATION_STATE（文明状態）
・MC-013_CIRCULATION（循環）
・MC-014_OBSERVATION（観測）
・MC-018_COLLAPSE_STRUCTURE（崩壊構造）
・MC-020_PROPAGATION_MODEL（波及）

・CL-003_STATE_CHANGE_LOG（状態変化ログ）
・CL-004_CIVILIZATION_LOG（文明ログ）
・CL-006_SPLIT_BIAS_LOG（分割偏差ログ）
・CL-007_HIDDEN_STATE_LOG（潜在状態ログ）

・MG-006_NODE_EDGE_FACE_MAPPING（幾何学接続）
・MG-007_GEOMETRY_AND_CIRCULATION（幾何学循環）

---

# FIXED_TERMS

・還流経路
・流動ノード
・接続辺
・循環ループ
・滞留点
・断絶点
・逆流点
・過密点
・偏在流動
・経路固定化

---

# SUMMARY_FOR_AI

還流経路ログとは、
流動の量ではなく「どこを通っているか」を観測するログである。

重要なのは、
流れているかではなく、
戻っているか（還流しているか）である。

AIは本ログを用いて、

・経路の断絶
・流動の偏在
・循環の不成立

を検出し、
崩壊予兆の早期観測に利用する。

---

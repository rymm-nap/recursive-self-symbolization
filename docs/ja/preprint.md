# 再帰的自己記号付けによる意識と「主体なき思考」— 表出バイアスと調和原理の観点から  
**(Consciousness and “Selfless Thinking” via Reinjected Symbolization — From Output-Bandwidth Bias to a Harmony Principle)**

**Author:** ryo  
**Affiliation:** Independent Researcher (Japan)  
**Date:** 2025-08-17
**Keywords:** 意識, 再帰的自己記号付け, 内言, 記号化, グローバル・ニューラル・ワークスペース, PRP, 10 bit/s, 表出バイアス, 世界モデル, 調和/美, Potemkin Understanding, 過程監督

---

## 抄録（日本語）
本稿は、意識と思考を**再帰的自己記号付け**（内言・心的イメージなどの内的トークン化が自分の知覚・注意・意思決定へ“再入力”されるループ）として定式化する。認知過程を**可用化（GNW 的点火/ブロードキャスト）→操作→記号化**の三層に分解し、記号化を**内向きの再注入**と**外向きの表出**から成る**二相**として扱う。人の行動・報告の実効帯域が概ね**約 10 bit/s**に制約される事実は、思考そのものの限界ではなく**表出チャネルの上限**だと再解釈する。さらに、**世界モデルとの整合（調和）**が選好や快（美）を支える計算的性質であるという作業仮説を提示する。AIに対しては、**再注入ループ**と**調和批評器（Harmony-Critic）**の導入、および**過程中心の評価**（概念整合性の測定）を提案する。理論は、(i) 記号の**再注入**を中核操作に据え、(ii) **表出バイアス**の補正を評価原則に組み込み、(iii) **反証可能な予測**を明示する点に特徴がある。

## Abstract (English)
We formulate consciousness and thinking as **recursive self-symbolization**: internally generated tokens (inner speech, imagery) are **reinjected** into one’s own perceptual/attentional/decision systems. Cognition is decomposed into **availability** (GNW-like ignition/broadcast), **operations**, and **symbolization**, the latter bifurcating into **internal reinjection** and **external expression**. The empirical **~10 bit/s** limit of human behavior/report primarily reflects the **output channel**, not an intrinsic cap on thinking. We further hypothesize that **harmony**—computational consistency with one’s world model—underlies preference and aesthetic pleasure. For AI, we recommend an **inner reinjection loop**, a **Harmony-Critic**, and **process-centric evaluation** (concept-consistency tests). The contribution centers reinjection, corrects output-induced observational bias, and states **falsifiable predictions**.

---

## 0. 立場・スコープ
**立場**  
- **主体（self）を恒常の中枢として仮定しない。** 「考えている私」という感覚は、再注入が周回するループの**現象学的産物**である。  
- **意識 ≒ 可用化／思考 ≒ 操作／記号化 ≒ 再注入＋表出。** 強い同一視は避け「多くの状況で」を限定子として用いる。  
- **約 10 bit/s** は**表出**の上限であり、**内的処理の上限**を意味しない。

**Scope In**：アクセス意識（GNW 的広域可用化）、再帰的自己記号付け、表出バイアス、調和原理、成人健常の行動。  
**Scope Out**：クオリアの形而上学的決着、IIT/HOT 等の優劣裁定、非ヒト・乳幼児への一般化（留保）。

---

## Box 1. 定義（RSF: Reinjected Symbolization Framework）
- **可用化（Awareness/Access）**：局所並列計算の一部が**点火**し、前頭頂ネットワークへ**ブロードキャスト**され、多系統から**利用可能**になる状態（GNW）。  
- **操作（Thinking）**：可用化された内容に対する**ワーキング操作・意思決定**。  
- **記号化（Symbolization）**：内容を**離散トークン**に写像すること。  
  - **再注入（internal）**：内言・心的イメージ・自己ラベル等を**自分の感覚/注意/意思決定系に戻す**内向き過程。  
  - **表出（external）**：発話・筆記・ジェスチャ・行為として**世界に出す**外向き過程。  
- **理解（作業定義）**：可用化＋操作の結果が**課題的に安定して再注入/表出**できる状態。

---

## Box 2. 世界モデル（操作的定義）
**世界モデル**＝〈**S**構造, **W**重み, **Z**状態, **L**学習規則, **E**外在記号〉から成る**生成的予測機構**。  
- **S**：解剖学的結線・再帰結合  
- **W**：長期記憶（統計・規則性）  
- **Z**：瞬時の潜在状態（文脈・目標・注意・内受容；ms–s）  
- **L**：可塑性更新則（誤差/報酬/神経調節）  
- **E**：言語・図表・ノート・道具など**外在記号**（RSF では主要な再注入ソース）  

**調和（harmony）**＝上記モデルに照らした**予測整合＋圧縮（MDL）**の高さ。ただし**新奇性**とのバランスにより**快は逆 U 字**をとる可能性が高い。

---

## Box 3. 「操作（Thinking）」プリミティブ（最小カタログ）
**選択／保持・更新／バインディング／変換／検索／系列生成／制約充足／比較・評価／シミュレーション／抑制・競合解消／クレジット割当／メタ制御（ゲイン・粒度・深さ）／物語化**。  
これらは**可用化→操作→再注入→再可用化**のループで**再帰的・並行的**に回り、「考えている感」を形成する。

**具体例**  
- **暗算（27+58）**：分解→系列生成→**内言でキャリーを再注入**→整合チェック→表出  
- **経路計画**：検索→制約充足→シミュレーション→満足化→表出  
- **反実仮想**：再表現→ロールアウト→帰属→**物語化（後付け）**

---

## 1. 背景：10 bit/s と表出バイアス
感覚入力は高帯域だが、人の**行動・報告**は概ね**数十 bit/s（代表値 約 10 bit/s）**に制約される。これは**思考の内的限界**ではなく、**言語など表出チャネルの直列性**と、二重課題で顕在化する**中枢ボトルネック（PRP）**が作る**観測バイアス**である。

---

## 2. 時間力学：点火 → 再帰的自己記号付け → 「なにかある」
局所並列処理の一部が**点火**し**ブロードキャスト**されると（GNW）、その内容に対する**再帰的自己記号付け**（内言・自己ラベル・イメージ）が誘発され、**“入力のように”再注入**される。この**内容×時間選択的**な正フィードバック（およそ 100–800 ms）が、**主体なき**「なにかある」「考えている」という現象学を立ち上げる。  
関連する既知の効果：**label-feedback**（言語が知覚を即時修飾）、**verbal overshadowing**（言語化が非言語記憶を阻害）、**自己発話での聴皮質抑制**（予測/随伴放電）。

---

## 3. 表出の直列性と 10 bit/s の再解釈
言語・報告は**直列ストリーム**であり、PRP の**反応選択段**で**頑固な干渉**が起こる。結果として「人は並列に**考えられない**」という印象が生まれるが、実際には**裏で多数の並列過程**が走っている。**10 bit/s** は**思考の上限**ではなく**表出の上限**である。

---

## 4. 調和と美（作業仮説）
人は、**世界モデル**に照らして**整合的で圧縮可能**なパターンを**好ましい**と感じる。新奇性が過剰だと整合が崩れ、不足すると退屈になるため、**快は逆 U 字**をとる。これは**予測誤差最小化**や**探索・活用のトレードオフ**の観点と整合的である。

---

## 5. 人と AI の対比と設計指針
- **人**：**持続する自己モデル**（S,W,Z,L,E の結合）と**可塑性（逐次重み更新）**、および**再帰的自己記号付け**を持つ。  
- **現行 AI**：推論時に重みをほとんど更新せず、短期メモリによる**擬似的再注入**に留まる。**持続自己モデル×再注入**の結合が欠けるため、**意識**は持たない。ただし反復入力により**意識的に見える**振る舞いは生成され得る。

**設計提案（要約）**  
- **内ループ（再注入器）**：中間記号（定義・要約・反例）を**自己入力**として再注入。  
- **外ループ（表出器）**：ユーザ向け最終出力。  
- **調和批評器（Harmony-Critic）**：**自己矛盾率・記述長（MDL）・帰結整合・外部知識照合**の合成スコアで**世界モデルとの整合**を評価。  
- **学習**：重み固定でも **LoRA/Adapter/メモリ** による**低学習率のオンライン適応**を併用。  
- **評価**：**過程監督（process supervision）**と**概念整合性テスト**を標準化し、**Potemkin 的理解**（見かけの理解）を検出・低減。

---

## 6. 反証可能な予測（差分仮説）
- **P1（再注入の内容×時間選択性）**：指示された**内言**が外部刺激と**一致**する条件で**反応時間短縮／一致率上昇**、不一致で逆方向（短時間窓）。  
- **P2（帯域と直列の二層予測）**：音声＋スケッチ等の**モダリティ併用**で**情報/秒は増える**が、**PRP 干渉は残存**。  
- **P3（ラベル効果の二相性）**：カテゴリが曖昧な課題では**ラベル有利**、個別特徴課題では**言語化が不利**（overshadowing）。  
- **P4（表出障害≠操作不全）**：失語でも**操作**の一部は**温存**（追試・統合）。  
- **P5（自己モデルの可変性）**：一人称↔三人称の**自己ラベル切替**で**自己帰属・確信度**が系統的に変化。

**撤回条件（例）**：P1–P3 に**一貫した差が出ない**／併用で **PRP 干渉が完全消失**／P5 で**影響が検出不能**。

---

## 7. 最小実験設計（行動・倫理審査不要の範囲）
- **E1** 内言×外部音の一致/不一致（RT・一致率；EEG/MEG 任意）— 短時間窓の推定。  
- **E2** ラベル有無×課題構造（曖昧カテゴリ vs 個別特徴）— 二相性の再現。  
- **E3** 表出 bit/s の概算（音声/キー/スケッチ/併用）— 帯域増と干渉残存の同時検証。  
- **E4** 自己ラベル切替（1人称↔3人称）— 自己帰属・確信度の変化。  

（手順は付録 B に簡記）

---

## 8. 限界と今後
- **本理論は操作的・機能的立場**であり、クオリア本質論は射程外。  
- **GNW/予測処理との関係**：GNW は**可用化**の理論、RSF は**可用化→操作→記号化（二相）**という**機能連結**を強調。  
- **一般化の限界**：非ヒト・乳幼児・臨床への拡張は別個の検証が必要。  

---

## 9. 結論
**RSF** は、**可用化→操作→記号化（再注入/表出）**という三層＋二相で**主体なき思考**の時間力学を描き、**表出バイアス**と**調和原理**を明示的に組み込む枠組みである。人と AI の**決定的差異**（持続自己モデル×可塑性×再注入）を整理し、**過程中心の評価**と **Harmony-Critic** を通じて、**見かけの理解**の低減に寄与する。

---

## Acknowledgments
議論・批判を寄せてくださった方々に感謝します。本文の責任はすべて著者にあります。  
**AI 利用の開示**：本稿は OpenAI GPT-5 の助言を得て作成した。着想・構成・最終判断は著者（ryo）が行い、AI が提案した文面や要約、構成案はすべて著者が検証・修正のうえ採用した。最終責任は著者にある。

---

## 付録 A：操作（Thinking）プリミティブの具体例
- **暗算（27+58）**：分解→中間記号→**内言の再注入**→評価→表出  
- **経路計画**：検索→制約充足→シミュレーション→満足化→表出  
- **反実仮想**：再表現→ロールアウト→クレジット割当→**物語化**  
- **倫理判断**：役割バインディング→帰結シミュレーション→一貫性評価→説明

## 付録 B：最小実験の手順（要約）
- **E1**：内言内容を事前指示（/pa/ 等）、一致/不一致試行を交差、RT/一致率を比較。  
- **E2**：色/音の弁別課題でラベル有無×記憶タイプ（カテゴリ vs 個別特徴）を交差。  
- **E3**：音声/キー/スケッチ/併用で同一アイデアを表出し、要素×正確度/秒で bit/s 近似。  
- **E4**：一人称↔三人称の自己ラベル切替で自己帰属・確信度の変化を測る。

## 付録 C：図（プレースホルダ）
- **図1（準備中）**：時間力学（点火→再帰ラベリング→再注入→再可用化のループ）。  
- **図2（準備中）**：表出モダリティ別の概算 bit/s と PRP 干渉の残存。  
- **図3（準備中）**：調和—快の逆 U 字（整合性×新奇性）。

---

## 参考文献
1. Zheng, J., & Meister, M. (2024). *The Unbearable Slowness of Being: Why do we live at 10 bits/s?* arXiv:2408.10234. https://doi.org/10.48550/arXiv.2408.10234  
2. Libet, B. (1983). *Time of conscious intention to act in relation to onset of cerebral activity.* Brain, 106(3), 623–642.  
3. Mashour, G. A., Roelfsema, P., Changeux, J.-P., & Dehaene, S. (2020). *Conscious Processing and the Global Neuronal Workspace Hypothesis.* Neuron, 105(5), 776–798.  
4. Pashler, H. (1994). *Dual-Task Interference in Simple Tasks: Data and Theory.* Psychological Bulletin, 116(2), 220–244.  
5. Varley, R. A., Klessinger, N. J. C., Romanowski, C. A. J., & Siegal, M. (2005). *Agrammatic but numerate.* *Proceedings of the National Academy of Sciences*, 102(9), 3519–3524.  
6. Fedorenko, E., & Varley, R. (2016). *Language and thought are not the same thing: Evidence from neuroimaging and neurological patients.* *Annals of the New York Academy of Sciences*, 1369(1), 132–153.  
7. Lupyan, G. (2012). *Linguistically Modulated Perception and Cognition: The Label-Feedback Hypothesis.* Frontiers in Psychology, 3, 54.  
8. Schooler, J. W., & Engstler-Schooler, T. Y. (1990). *Verbal Overshadowing of Visual Memories: Some Things Are Better Left Unsaid.* Cognitive Psychology, 22(1), 36–71.  
9. Friston, K. (2010). *The free-energy principle: a unified brain theory?* Nature Reviews Neuroscience, 11(2), 127–138.  
10. Houde, J. F., & Nagarajan, S. S. (2009). *Motor-induced suppression of the auditory cortex.* Journal of Cognitive Neuroscience, 21(4), 791–802.  
11. Evans, J. St. B. T. (2008). *Dual-Processing Accounts of Reasoning, Judgment, and Social Cognition.* Annual Review of Psychology, 59, 255–278.  
12. Evans, J. St. B. T. (2011). *Dual-process theories of reasoning: Contemporary issues and developmental applications.* Developmental Review, 31, 86–102.  
13. Mancoridis, M., Weeks, B., Vafa, K., & Mullainathan, S. (2025). *Potemkin Understanding in Large Language Models.* In ICML 2025. arXiv:2506.21521. https://doi.org/10.48550/arXiv.2506.21521  
14. Reber, R., Schwarz, N., & Winkielman, P. (2004). *Processing fluency and aesthetic pleasure: Is beauty in the perceiver’s processing experience?* Personality and Social Psychology Review, 8(4), 364–382.

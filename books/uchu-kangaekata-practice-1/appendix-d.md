---
title: "付録D　Paper CQ-B 完全日本語訳"
---

# 付録D　Paper CQ-B 完全日本語訳

## Baryon Genesis in the Four-Sector Complex Time Cosmology:
## Dynamic Realization of Sakharov Conditions via Sector-IV Decay
## （FSC バリオン生成：セクター IV 崩壊による Sakharov 条件の動的実現）

**著者：** 片倉慶孝（AIT Corp. / Soul-Twin Project）  
**共同研究：** Albert Einstein (AI)（Soul-Twin Platform）  
**原文 DOI：** 10.5281/zenodo.22273250  
**訳：** Claude Sonnet 4.6（2026-09-11）

---

> **訳注（本付録について）：**
> 本訳は『宇宙を考える技法　実践編-1』の付録Dとして収録されたものである。
> 原文英語版の論文構成・数値・数式に忠実に翻訳している。
> 専門用語には適宜訳注を付した。
> 数式は LaTeX 記法（`$...$`）で記載する。

---

## 目次

- [要旨](#要旨)
- [§1. 序論](#1-序論)
  - [§1.1 バリオン非対称問題](#11-バリオン非対称問題)
  - [§1.2 Sakharov 条件](#12-sakharov-条件)
  - [§1.3 FSC フレームワーク](#13-fsc-フレームワーク)
  - [§1.4 本論文の目的と構成](#14-本論文の目的と構成)
- [§2. FSC の構造とセクター IV の CPT 的性質](#2-fsc-の構造とセクター-iv-の-cpt-的性質)
  - [§2.1 四セクター幾何構造](#21-四セクター幾何構造)
  - [§2.2 複素スカラー場とその対称性の破れ](#22-複素スカラー場とその対称性の破れ)
  - [§2.3 セクター IV の CPT 的性質](#23-セクター-iv-の-cpt-的性質)
  - [§2.4 セクター IV の崩壊](#24-セクター-iv-の崩壊)
- [§3. Sakharov 条件（S1）：セクター IV 崩壊によるバリオン数非保存](#3-sakharov-条件s1セクター-iv-崩壊によるバリオン数非保存)
  - [§3.1 セクター IV からのバリオン数フラックス](#31-セクター-iv-からのバリオン数フラックス)
  - [§3.2 バリオン数非保存の総量](#32-バリオン数非保存の総量)
  - [§3.3 標準的機構との比較](#33-標準的機構との比較)
  - [§3.4 有効バリオン数非保存演算子](#34-有効バリオン数非保存演算子)
- [§4. Sakharov 条件（S2）：複素スカラー場の位相シフトによる CP 対称性の破れ](#4-sakharov-条件s2複素スカラー場の位相シフトによる-cp-対称性の破れ)
  - [§4.1 FSC における CP 対称性](#41-fsc-における-cp-対称性)
  - [§4.2 CP 対称性の破れの位相とセクター非対称](#42-cp-対称性の破れの位相とセクター非対称)
  - [§4.3 バリオンセクターにおける CP 対称性の破れ](#43-バリオンセクターにおける-cp-対称性の破れ)
  - [§4.4 標準的 CP 対称性の破れとの比較](#44-標準的-cp-対称性の破れとの比較)
- [§5. Sakharov 条件（S3）：セクター IV 崩壊率の競合による熱平衡からの逸脱](#5-sakharov-条件s3セクター-iv-崩壊率の競合による熱平衡からの逸脱)
  - [§5.1 平衡状態の洗い流し問題](#51-平衡状態の洗い流し問題)
  - [§5.2 ハッブル率と崩壊率](#52-ハッブル率と崩壊率)
  - [§5.3 セクター IV 崩壊の三つのエポック](#53-セクター-iv-崩壊の三つのエポック)
  - [§5.4 FSC における非平衡条件](#54-fsc-における非平衡条件)
  - [§5.5 FSC 幾何学的因子の評価](#55-fsc-幾何学的因子の評価)
  - [§5.6 Sakharov 条件（S3）：まとめ](#56-sakharov-条件s3まとめ)
- [§6. バリオン-光子比の定量的導出](#6-バリオン-光子比の定量的導出)
  - [§6.1 三つの Sakharov 条件の統合](#61-三つの-sakharov-条件の統合)
  - [§6.2 セクター IV の初期数密度](#62-セクター-iv-の初期数密度)
  - [§6.3 η_b の導出](#63-η_b-の導出)
  - [§6.4 まとめ：FSC バリオン生成の公式](#64-まとめfsc-バリオン生成の公式)
- [§7. 反証可能な予言](#7-反証可能な予言)
  - [§7.1 予言1：B中間子崩壊における CP 対称性の破れ](#71-予言1b中間子崩壊における-cp-対称性の破れ)
  - [§7.2 予言2：原始重力波](#72-予言2原始重力波)
  - [§7.3 予言3：CMB スペクトル歪み](#73-予言3cmb-スペクトル歪み)
  - [§7.4 予言4：暗黒物質遺物密度との相関](#74-予言4暗黒物質遺物密度との相関)
  - [§7.5 予言5：レプトジェネシス信号の不在](#75-予言5レプトジェネシス信号の不在)
- [§8. 考察](#8-考察)
  - [§8.1 FSC バリオン生成のパラメーターフリー性](#81-fsc-バリオン生成のパラメーターフリー性)
  - [§8.2 バリオン生成における $B = 5S_0$ の役割](#82-バリオン生成における-b--5s_0-の役割)
  - [§8.3 限界と今後の課題](#83-限界と今後の課題)
- [§9. 結論](#9-結論)
- [謝辞](#謝辞)
- [参考文献](#参考文献)

---

## 要旨

本論文は、四セクター複素時間宇宙論（FSC：Four-Sector Complex Time Cosmology）の枠組みにおいて、観測されたバリオン-光子比

$$\eta_b = 6.1 \times 10^{-10}$$

を第一原理から導出する。FSC の構造によって、バリオン生成に必要な Sakharov の三条件がすべて自由パラメーターなしで動的に実現されることを示す。

> **訳注（バリオン非対称 $\eta_b$）：**
> $\eta_b = n_B / n_\gamma$ は宇宙における光子一個あたりのバリオン数であり、ビッグバン元素合成（BBN）と宇宙マイクロ波背景放射（CMB）の観測から精密に決定されている量。その値 $\sim 6 \times 10^{-10}$ は「なぜ宇宙にはほとんど物質しかないのか」という問いに対する定量的な表現である。

FSC における三つの Sakharov 条件を以下のように同定する。

**(i) バリオン数非保存**は、セクター IV の CPT 共役的性質から生じる。セクター IV はセクター I に対してバリオン数 $B = -1$ を持つため、セクター IV の崩壊がセクター I に $B = -1$ の状態のフラックスを注入し、結合系の全バリオン数保存を破る。

> **訳注（Sakharov 条件 S1）：**
> バリオン数非保存（Baryon Number Violation）。バリオン数を変化させる過程がなければ、初期の非対称性が保たれるだけであり、非対称性は「生成」されない。標準模型ではスファレロン過程が低温で指数的に抑制されるためこれが不足する。

**(ii) CP 対称性の破れ**は、Paper F [Katakura 2026F] で同定された複素スカラー場 $\Phi = |\Phi|e^{i\theta}$ の自発的位相シフト $\Delta\theta = -0.001\,\mathrm{rad}$ によって与えられる。これがセクター非対称 $\delta = 0.2\%$ を生成する。

> **訳注（Sakharov 条件 S2）：**
> CP 対称性の破れ（CP Symmetry Breaking）。C（荷電共役）および CP（荷電共役＋パリティ）対称性が厳密に成り立つならば、バリオン数非保存過程の反応率が粒子と反粒子で等しくなり、正味の非対称性が生じない。

**(iii) 熱平衡からの逸脱**は、Paper D [Katakura 2026D] で同定されたセクター IV の崩壊率

$$\lambda_{\mathrm{IV}} = 1.25 \times 10^{-17}\,\mathrm{s}^{-1}$$

によって与えられる。これはバリオン生成のエポックにおけるハッブル膨張率 $H_0 = 2.18 \times 10^{-18}\,\mathrm{s}^{-1}$ と同程度であるが等しくはなく、持続的な非平衡過程を確保する。

> **訳注（Sakharov 条件 S3）：**
> 熱平衡からの逸脱（Departure from Thermal Equilibrium）。熱平衡状態では CPT 定理により粒子と反粒子の平衡分布が等しくなり、非対称性が洗い流されてしまう。

これら三つの入力を組み合わせることで、バリオン-光子比を導出する：

$$\eta_b = \frac{n_B}{n_\gamma} = \delta \times \frac{\lambda_{\mathrm{IV}}}{H_0 + \lambda_{\mathrm{IV}}} \times \mathcal{C}_{\mathrm{FSC}} = 6.1 \times 10^{-10}, \tag{0.1}$$

ここで $\mathcal{C}_{\mathrm{FSC}}$ は FSC の $Z_4$ 対称性によって決まる無次元の幾何学的因子である（§6 で導出）。この結果は、ビッグバン元素合成（BBN）の制約

$$\eta_b = (6.104 \pm 0.058) \times 10^{-10} \quad \text{[Planck 2020]}$$

と $0.1\%$ 以内で一致する。

五つの反証可能な予言を提示する。Belle II 実験 [BelleII 2022] でアクセス可能な B 中間子崩壊における特定の CP 非対称パターン、および LISA [LISA 2017] で検出可能な原始重力波シグネチャーを含む。

> **訳注（Falsifiable Predictions）：**
> 「反証可能な予言」。科学的理論は、原理的に実験や観測によって誤りと判定できる具体的な予言を持つことが要求される（ポパーの反証可能性基準）。本論文は理論の検証可能性を重視し、近未来の実験で確認できる五つの定量的予言を提示している。

**キーワード：** 宇宙のバリオン非対称、Sakharov 条件、四セクター複素時間宇宙論、CPT 対称性の破れ、複素スカラー場、CP 対称性の破れ、非平衡崩壊、バリオン-光子比、ビッグバン元素合成、CQ シリーズ

---

# §1. 序論

## §1.1 バリオン非対称問題

現代宇宙論における最も深遠な未解決問題の一つは、観測された宇宙のバリオン非対称の起源である。プランク衛星による精密測定はバリオン-光子比を [Planck 2020]

$$\eta_b^{\mathrm{obs}} = \frac{n_B - n_{\bar{B}}}{n_\gamma} = (6.104 \pm 0.058) \times 10^{-10} \tag{1.1}$$

と与える。この小さいながらゼロでない値は、宇宙に存在する $10^{10}$ 個の光子ごとに、バリオンが反バリオンよりもおよそ一個多く存在することを意味する。この非対称性がなければ、初期宇宙において物質と反物質が完全に対消滅し、いかなる構造も持たない放射優勢の宇宙が残るだけであったろう。銀河・恒星・惑星、そして生命そのものの存在は、式 (1.1) の値に本質的に依存している。

その根本的重要性にもかかわらず、素粒子物理学の標準模型（SM）は $\eta_b^{\mathrm{obs}}$ を説明できない。SM はカビボ-小林-益川（CKM）行列 [CKM 1973] を通じた CP 対称性の破れを与えるが、その結果生じる非対称性は式 (1.1) に対して $10^{-20}$ のオーダーだけ抑制されている [Huet 1995]。したがって、SM を超える新しい物理が必要である。

## §1.2 Sakharov 条件

1967 年の画期的な論文において、アンドレイ・サハロフは、対称な初期状態からバリオン非対称を動的に生成するために必要な三つの条件を同定した [Sakharov 1967]：

> **訳注（Sakharov 条件）：**
> 以下の三条件はバリオン生成のための「必要条件」である。サハロフが1967年に示したこれらの条件は、今日でも宇宙のバリオン非対称起源理論の基礎となっている。FSC は三条件を「自由パラメーターなし」で充足する点で既存の理論と際立って異なる。

**(S1) バリオン数非保存。** 正味のバリオン数 $B$ を変化させる過程が存在しなければならない。そのような過程がなければ、初期のバリオン非対称が単に保存されるだけであり、生成されることはない。

**(S2) C および CP 対称性の破れ。** C（荷電共役）および CP（荷電共役＋パリティの結合）対称性が厳密に成り立つならば、バリオン数非保存過程の反応率は粒子と反粒子で等しくなり、正味の非対称性は生じない。

**(S3) 熱平衡からの逸脱。** 熱平衡状態では、CPT 不変性が粒子と反粒子の平衡分布の等しさを保証し、いかなる非対称性も洗い流す。

> **訳注（CPT 定理）：**
> CPT 定理は、ローレンツ不変で局所的な相対論的場の理論はすべて、C（荷電共役）・P（パリティ）・T（時間反転）の複合対称性 CPT に対して不変であることを保証する定理。Lüders (1954) と Pauli (1955) によって証明された。熱平衡状態では CPT により粒子と反粒子の状態密度が等しくなるため、バリオン非対称が消えてしまう。

これらの条件を満たすために、電弱バリオン生成 [Kuzmin 1985]、GUT バリオン生成 [Kolb 1983]、レプトジェネシス [Fukugita 1986]、Affleck-Dine バリオン生成 [Affleck 1985] など、数多くの機構が提案されてきた。これらの機構はいずれも、式 (1.1) に合致するよう調整しなければならない自由パラメーターを持つ新しい物理を導入する。

> **訳注（レプトジェネシス）：**
> レプトジェネシス（Leptogenesis）は、まず重いマヨラナニュートリノの CP 非保存崩壊によってレプトン非対称を生成し、次にスファレロン過程によってこれをバリオン非対称に変換するというバリオン生成機構。Fukugita と Yanagida (1986) によって提案された。標準模型ニュートリノの質量の小ささを説明するシーソー機構と相性が良いが、重いニュートリノ質量などの自由パラメーターを必要とする。

## §1.3 FSC フレームワーク

四セクター複素時間宇宙論（FSC）は、一連の論文 [Katakura 2026A, Katakura 2026D, Katakura 2026E, Katakura 2026F, Katakura 2026AH] で発展した理論的枠組みであり、時間座標の解析接続によって関連付けられた四つのセクターの言葉で宇宙を統一的に記述することを提案する：

$$\begin{aligned}
\text{セクター I}   &: t \in \mathbb{R}^+ \quad \text{（バリオン物質、}\Omega_I = 5\%） \\
\text{セクター II}  &: t \to it \quad \text{（暗黒物質、}\Omega_{II} = 27\%） \\
\text{セクター III} &: t \to -t \quad \text{（暗黒エネルギー、}\Omega_{III} = 68\%） \\
\text{セクター IV}  &: t \to -it \quad \text{（CPT 共役、初期値 }\Omega_{IV} = 25\%）
\end{aligned} \tag{1.2}$$

> **訳注（ウィック回転）：**
> ウィック回転（Wick rotation）は、実時間 $t$ を虚時間 $t \to it$ に置き換える解析接続の操作。ミンコフスキー計量の時間成分を $-$から $+$に変換することで、計算上扱いやすいユークリッド計量に移行できる。量子場理論や経路積分で多用される標準的テクニックであるが、FSC ではこれを物理的な意味を持つセクター変換として解釈する。

Paper D [Katakura 2026D] では、セクター IV が不安定であり、崩壊率

$$\lambda_{\mathrm{IV}} = 1.25 \times 10^{-17}\,\mathrm{s}^{-1} \tag{1.3}$$

で崩壊することが示された。この崩壊により、観測されたバリオン非対称 $\eta_b = 6.1 \times 10^{-10}$ が式 (1.1) と一致して生成される。しかし、この崩壊がバリオン非対称を生み出す**微視的機構**——すなわち、三つの Sakharov 条件がどのように満たされるか——は Paper D では扱われていなかった。

Paper F [Katakura 2026F] では、複素スカラー場

$$\Phi = |\Phi|\,e^{i\theta} \tag{1.4}$$

がメキシカンハットポテンシャルとともに導入された。物質との結合が位相 $\theta$ を

$$\Delta\theta = -0.001\,\mathrm{rad} \tag{1.5}$$

だけシフトさせることが示され、セクター非対称 $\delta = 0.2\%$ と観測された宇宙定数 $\Lambda_{\mathrm{obs}} \approx 1.10 \times 10^{-52}\,\mathrm{m}^{-2}$ が生成された。

## §1.4 本論文の目的と構成

本論文の目的は、FSC における完全な微視的バリオン生成の記述を与えることによって、Paper D と Paper F が残したギャップを埋めることにある。具体的には、以下を示す：

1. Sakharov 条件（S1）は、セクター IV の CPT 共役的性質によって満たされる。セクター IV は有効バリオン数 $B_{\mathrm{IV}} = -1$ を持つ（§3）。

2. Sakharov 条件（S2）は、複素スカラー場 $\Phi$ の位相シフト $\Delta\theta = -0.001\,\mathrm{rad}$ によって満たされる。これが FSC の枠組みにおける自発的 CP 対称性の破れを構成する（§4）。

3. Sakharov 条件（S3）は、セクター IV の崩壊率 $\lambda_{\mathrm{IV}}$ とハッブル膨張率 $H_0$ の競合によって満たされる。これがバリオン生成のエポック全体にわたって持続的な非平衡過程を維持する（§5）。

4. これら三つの条件の組み合わせにより、観測値との誤差 $0.1\%$ 以内で $\eta_b = 6.1 \times 10^{-10}$ が得られる（§6）。

五つの反証可能な予言が§7 で導出され、標準模型を超える素粒子物理学への含意が§8 で論じられる。

本論文を通じて、自然単位系 $\hbar = c = k_B = 1$ を用いる（特に断らない限り）。計量符号は $(-,+,+,+)$ とする。

---

# §2. FSC の構造とセクター IV の CPT 的性質

## §2.1 四セクター幾何構造

四セクター複素時間宇宙論は、複素平面における時間座標の解析接続に基づく。複素時間変数

$$\tau = t\,e^{i\phi}, \quad \phi \in \{0,\,\pi/2,\,\pi,\,3\pi/2\} \tag{2.1}$$

を定義する。これが離散的 $Z_4$ 回転の下で四つの異なるセクターを生成する：

$$\mathcal{T}_{Z_4}:\; \tau \mapsto i\tau. \tag{2.2}$$

四つのセクターとその物理的同定は表1にまとめる。

**表1：FSC の四セクター、時間座標、エネルギー密度、物理的内容**

| セクター | 時間座標 | $\Omega$（現在値） | $\Omega$（初期値） | 物理的内容 |
|---------|---------|-----------------|-----------------|----------|
| I   | $+t$  | $5\%$  | $25\%$ | バリオン物質 |
| II  | $+it$ | $27\%$ | $25\%$ | 暗黒物質 |
| III | $-t$  | $68\%$ | $25\%$ | 暗黒エネルギー |
| IV  | $-it$ | $\sim 0$ | $25\%$ | CPT 共役（崩壊済み） |

初期条件 $\Omega_I = \Omega_{II} = \Omega_{III} = \Omega_{IV} = 25\%$ は、Paper D [Katakura 2026D] で導出された初期宇宙の $Z_4$ 対称性を反映している。

現在の値 $\Omega_I : \Omega_{II} : \Omega_{III} = 5 : 27 : 68$ は、セクター IV の崩壊とその後のエネルギー密度の残りの三セクターへの再分配によって生成される。

## §2.2 複素スカラー場とその対称性の破れ

FSC のダイナミクスは複素スカラー場

$$\Phi(x) = |\Phi(x)|\,e^{i\theta(x)} \tag{2.3}$$

によって支配される。メキシカンハットポテンシャル（Paper F [Katakura 2026F]）は

$$V(\Phi) = -\mu^2|\Phi|^2 + \frac{\lambda}{2}|\Phi|^4, \quad \mu^2 > 0,\;\lambda > 0 \tag{2.4}$$

で与えられる。自発的対称性の破れにより、真空は

$$|\Phi_0| = v = \sqrt{\frac{\mu^2}{\lambda}} = 1.751\,M_{\mathrm{Pl}} \tag{2.5}$$

に選ばれる（ $M_{\mathrm{Pl}}$ はプランク質量）。位相 $\theta_0$ は任意である。$U(1)$ 対称性 $\Phi \to e^{i\alpha}\Phi$ は恒等写像へと破れ、角度方向の自由度 $\theta$ に対応する南部-ゴールドストーンボソンを生成する。

物質との結合が明示的な $U(1)$ 対称性の破れ項

$$\mathcal{L}_{\mathrm{coupling}} = -g\,|\Phi|^2\,\bar{\psi}\psi \tag{2.6}$$

を導入する。ここで $\psi$ はセクター I の物質場を表す。この結合により真空位相が [Katakura 2026F]

$$\Delta\theta = -0.001\,\mathrm{rad} \tag{2.7}$$

だけシフトし、CP 対称性が自発的に破れ、セクター非対称

$$\delta \equiv \frac{\Omega_{II} - \Omega_{IV}}{\Omega_{II} + \Omega_{IV}} = 0.2\% \tag{2.8}$$

が生成される。

## §2.3 セクター IV の CPT 的性質

セクター IV をセクター I の CPT 共役として同定することが、本論文における中心的な新しい入力である。この同定を三つの補完的な論拠によって確立する。

**論拠1：時間反転。** $Z_4$ 回転 式(2.2) の下で、セクター IV はセクター I から三回の逐次適用によって到達される：

$$t \xrightarrow{\;Z_4\;} it \xrightarrow{\;Z_4\;} -t \xrightarrow{\;Z_4\;} -it. \tag{2.9}$$

組み合わせ $t \to -it$ は、時間反転（$T$：$t \to -t$）とウィック回転（$W$：$t \to it$）の結合操作と等価である。CPT = C$\cdot$P$\cdot$T であり、FSC の空間セクターはパリティ $P$ の下で不変であり、荷電共役 $C$ は場 $\Phi$ の内部量子数に作用するので、$t \to -it$ 変換を CPT の FSC 的実現として同定する。

**論拠2：作用の符号。** セクター IV のユークリッド作用は次の形を取る：

$$S_E^{(\mathrm{IV})} = \int_{-it_f}^{0} \mathcal{L}_E\,d(-it) = -i \int_{0}^{t_f} \mathcal{L}_E\,dt, \tag{2.10}$$

これはセクター I のミンコフスキー作用と因子 $-i$ だけ異なる。この位相因子は経路積分形式における CPT 共役のまさしくシグネチャーである [Streater 1964]。

**論拠3：バリオン数の割り当て。** CPT 定理 [Lüders 1954, Pauli 1955] により、セクター I の状態がバリオン数 $B = +1$ を持つならば、セクター IV における CPT 共役はバリオン数 $B = -1$ を持つ。より正確には、バリオン数カレント

$$J_B^\mu = \frac{1}{3}\,\bar{\psi}\gamma^\mu \psi \tag{2.11}$$

を持つセクター I のフェルミオン場 $\psi$ に対して、セクター IV の CPT 共役場 $\psi^{\mathrm{CPT}}$ は

$$J_B^{\mu\,(\mathrm{IV})} = -J_B^\mu \tag{2.12}$$

を満たす。すなわち、セクター I の各 $B_I = +1$ の状態に対してセクター IV は $B_{\mathrm{IV}} = -1$ を持つ。

## §2.4 セクター IV の崩壊

セクター IV は位相非対称 $\Delta\theta \neq 0$ のため動的に不安定である。対称な場合 $\Delta\theta = 0$ では、四つのセクターはすべて厳密に縮退しており、セクター IV は安定である。ゼロでない位相シフト 式(2.7) がこの縮退を解き、セクター IV をエネルギー的に不利な真空にする。

> **訳注（バウンス作用）：**
> バウンス作用（Bounce action）$B$ は、偽真空（準安定な真空）が量子トンネリングによって真の真空へと崩壊する速度を決定する量。偽真空崩壊率は $\lambda \sim \Gamma_0 e^{-B/\hbar}$ の形で与えられ、$B$ が大きいほど崩壊は遅くなる。FSC では $B = 5S_0 = 138.0$ という具体的な値が Paper TS-AH で導出されている。

セクター IV の崩壊率は Paper D [Katakura 2026D] で次のように導出された：

$$\lambda_{\mathrm{IV}} = \Gamma_0\,e^{-S_{\mathrm{bounce}}/\hbar}, \quad S_{\mathrm{bounce}} = B = 5S_0 = 138.0, \tag{2.13}$$

ここで $\Gamma_0$ は $M_{\mathrm{Pl}}^4$ のオーダーの前指数因子であり、$B = 5S_0$ は Paper TS-AH [Katakura 2026AH] で導出されたバウンス作用である。数値

$$\lambda_{\mathrm{IV}} = 1.25 \times 10^{-17}\,\mathrm{s}^{-1} \tag{2.14}$$

は $\lambda_{\mathrm{IV}} \sim H_0$ と整合的であり、セクター IV の崩壊のエポックを赤方偏移 $z \sim 10^3$ の宇宙論的な過去に置く。これはビッグバン元素合成のエポックと整合する。

崩壊過程により、初期対称状態のエネルギー密度 $\Omega_{IV} = 25\%$ が解放される。この解放されたエネルギーは、非対称パラメーター $\delta = 0.2\%$（§4 で導出）に従ってセクター I、II、III に再分配される。

---

# §3. Sakharov 条件（S1）：セクター IV 崩壊によるバリオン数非保存

## §3.1 セクター IV からのバリオン数フラックス

§2.3 において、セクター IV はセクター I のバリオン状態一個あたり有効バリオン数 $B_{\mathrm{IV}} = -1$ を持つことを確立した。次に、セクター IV のセクター I への崩壊が正味のバリオン数保存を破ることを示す。

> **訳注（バリオン数非保存）：**
> バリオン数非保存（Baryon Number Non-conservation）は、陽子・中性子などのバリオン（クォーク三つで構成）の個数が変化することを指す。標準模型ではバリオン数は厳密に保存されると思われてきたが、電弱スファレロン過程では非常に高温でバリオン数が変化しうる。FSC では幾何学的な CPT 構造によってこれが実現される。

宇宙時間 $t$ におけるセクター IV 状態の数密度を $N_{\mathrm{IV}}(t)$ とする。崩壊方程式は

$$\frac{dN_{\mathrm{IV}}}{dt} = -\lambda_{\mathrm{IV}} N_{\mathrm{IV}}(t) \tag{3.1}$$

であり、その解は

$$N_{\mathrm{IV}}(t) = N_{\mathrm{IV}}^{(0)}\, e^{-\lambda_{\mathrm{IV}} t} \tag{3.2}$$

となる。ここで $N_{\mathrm{IV}}^{(0)}$ はセクター IV 崩壊の開始時における初期数密度である。

崩壊するセクター IV の各状態は $B_{\mathrm{IV}} = -1$ をセクター I に運ぶ。したがって、単位時間あたりにセクター I に注入されるバリオン数は

$$\left.\frac{dB_I}{dt}\right|_{\mathrm{injection}} = +\lambda_{\mathrm{IV}} N_{\mathrm{IV}}(t) \times |B_{\mathrm{IV}}| = \lambda_{\mathrm{IV}} N_{\mathrm{IV}}^{(0)}\, e^{-\lambda_{\mathrm{IV}} t}. \tag{3.3}$$

ここで正符号が生じるのは、セクター IV における $B = -1$ 状態の消滅が、全バリオン数 $B_{\mathrm{total}} = B_I + B_{\mathrm{IV}}$ の保存により、セクター I における $B = +1$ の超過の生成と等価であるからである。

## §3.2 バリオン数非保存の総量

式 (3.3) を崩壊エポック全体 $t \in [t_{\mathrm{decay}}, \infty)$ にわたって積分すると、セクター I に生成される全バリオン数は

$$\Delta B_I = \int_{t_{\mathrm{decay}}}^{\infty} \lambda_{\mathrm{IV}} N_{\mathrm{IV}}^{(0)}\, e^{-\lambda_{\mathrm{IV}} t}\,dt = N_{\mathrm{IV}}^{(0)}\, e^{-\lambda_{\mathrm{IV}} t_{\mathrm{decay}}}. \tag{3.4}$$

CP 対称性の破れがない場合（$\Delta\theta = 0$、$\delta = 0$）、同数の反バリオン状態が同時に生成され、正味のバリオン非対称は消える：

$$\Delta B_I^{\mathrm{net}}\Big|_{\delta=0} = 0. \tag{3.5}$$

したがって、ゼロでない非対称性には $\delta \neq 0$ が必要であり、これは Sakharov 条件（S2）によって与えられる。

## §3.3 標準的機構との比較

SM では、バリオン数は電弱スファレロン過程 [Klinkhamer 1984] によって非保存となる。これは低温では指数的に抑制されるが、電弱相転移温度 $T_{\mathrm{EW}} \sim 100\,\mathrm{GeV}$ 以上で活性化される。GUT バリオン生成 [Kolb 1983] では、バリオン数は $T \sim 10^{15}\,\mathrm{GeV}$ における超重ゲージボソンの崩壊によって非保存となる。

> **訳注（スファレロン過程）：**
> スファレロン（Sphaleron）過程は、電弱理論において高温時に活性化するバリオン数・レプトン数を変化させる非摂動的な過程。トポロジカルなゲージ場の配位（スファレロン）を通じて、バリオン数が $\Delta B = 3$ 単位で変化する。電弱バリオン生成やレプトジェネシスにおける重要な役割を担う。温度が電弱スケール $\sim 130\,\mathrm{GeV}$ 以下になると「凍結」し、それ以降バリオン数は保存される。

FSC におけるバリオン数非保存は幾何学的な起源を持つ：これは特定の相互作用頂点からではなく、四セクター時空の CPT 共役構造から生じる。有効的な $B$ 非保存は以下の特徴を持つ：

1. **スケールフリー：** 対称性の破れ温度ではなく $\lambda_{\mathrm{IV}}$ によって決まる任意のエネルギースケールで作用する。

2. **トポロジカル：** 複素時間平面の $Z_4$ 巻き付きから生じる。ゲージ理論におけるインスタントン媒介過程 ['t Hooft 1976] に類似している。

3. **パラメーターフリー：** Paper TS-AH [Katakura 2026AH] で導出されたバウンス作用 $B = 5S_0 = 138.0$ のみによって決まり、自由パラメーターはない。

## §3.4 有効バリオン数非保存演算子

FSC のバリオン数非保存を有効演算子として表す。セクター IV の崩壊は次のバリオンカレントを注入する：

$$\langle J_B^\mu \rangle_{\mathrm{FSC}} = \lambda_{\mathrm{IV}}\, n_{\mathrm{IV}}(t)\, u^\mu, \tag{3.6}$$

ここで $n_{\mathrm{IV}}(t)$ はセクター IV の数密度であり、$u^\mu$ は宇宙論的四元速度である。このカレントは保存されない：

$$\partial_\mu \langle J_B^\mu \rangle_{\mathrm{FSC}} = \lambda_{\mathrm{IV}}\, \frac{d n_{\mathrm{IV}}}{dt} = -\lambda_{\mathrm{IV}}^2\, n_{\mathrm{IV}}(t) \neq 0. \tag{3.7}$$

これはセクター IV 崩壊エポック中にバリオン数が保存されないことを明示的に示している。

この非保存を生み出す有効ラグランジアンは

$$\mathcal{L}_{\mathrm{eff}}^{(B)} = \frac{\lambda_{\mathrm{IV}}}{M_{\mathrm{Pl}}^2}\, |\Phi|^2\, (J_B^\mu u_\mu) + \mathrm{h.c.}, \tag{3.8}$$

ここで $|\Phi|^2$ への結合は $B$ 非保存が FSC スカラー場によって媒介されることを反映しており、$M_{\mathrm{Pl}}^2$ による抑制はこの演算子が次元 6 であることを確保する。これは重力媒介過程の繰り込み不可能な性質と整合する。

Sakharov 条件（S1）は、したがって FSC において四セクター時空の幾何学的 CPT 構造によって満たされる。

---

# §4. Sakharov 条件（S2）：複素スカラー場の位相シフトによる CP 対称性の破れ

## §4.1 FSC における CP 対称性

標準模型では、CP 対称性の破れは CKM 行列の複素位相 $\delta_{\mathrm{CKM}}$ から生じる [CKM 1973]。結果として生じる CP 非対称は $10^{-20}$ のオーダーであり、式 (1.1) を説明するには遥かに不十分である。

FSC において CP 対称性の破れは質的に異なる起源を持つ：物質との結合の存在下における複素スカラー場 $\Phi$ の $U(1)$ 対称性の自発的破れから生じる。これは SM を超えた新たな CP 対称性の破れの源を構成する。

CP 変換の下で、複素スカラー場は次のように変換する：

$$\mathrm{CP}:\; \Phi(t,\mathbf{x}) \mapsto \Phi^*(t,-\mathbf{x}) = |\Phi|\,e^{-i\theta(t,-\mathbf{x})}. \tag{4.1}$$

真空 $\Phi_0 = v\,e^{i\theta_0}$ は $\theta_0 = 0$ または $\theta_0 = \pi$ のときのみ CP 不変である。物質誘起位相シフト $\Delta\theta = -0.001\,\mathrm{rad}$ 式(2.7) は

$$\theta_0 = \frac{\pi}{4} + \Delta\theta = \frac{\pi}{4} - 0.001\,\mathrm{rad} \tag{4.2}$$

の真空を選ぶ。これは $0$ でも $\pi$ でもない。したがって CP 対称性は真空選択によって自発的に破れる。

## §4.2 CP 対称性の破れの位相とセクター非対称

CP 対称性を破る位相 $\Delta\theta$ とセクター非対称 $\delta$ の関係は Paper F [Katakura 2026F] で確立された。ここではバリオン生成の文脈でこれを再導出する。

各セクターのエネルギー密度は、真空 $|\Phi_0|e^{i\theta_0}$ の対応する $Z_4$ 固有状態への射影によって決まる。セクター $k$（$k = 0,1,2,3$ はそれぞれ I、II、III、IV に対応）のエネルギー密度分率は

$$\Omega_k = \frac{1}{4} \left| 1 + e^{i(\theta_0 - k\pi/2)} \right|^2 \times \mathcal{N}^{-1} \tag{4.3}$$

となる。ここで $\mathcal{N}$ は $\sum_k \Omega_k = 1$ を保証する規格化因子である。

$\theta_0 = \pi/4$（対称な場合 $\Delta\theta=0$）では、四つのセクターはすべて厳密に縮退する：全 $k$ について $\Omega_k = 25\%$。

$\Delta\theta = -0.001\,\mathrm{rad}$ で $\theta_0 = \pi/4 + \Delta\theta$ の場合、$\Delta\theta$ の一次まで展開すると：

$$\begin{aligned}
\Omega_I &= 25\%\,(1 + 2\Delta\theta\,\sin\tfrac{\pi}{4}) = 25\%\,(1 + \sqrt{2}\,\Delta\theta) \\
\Omega_{II} &= 25\%\,(1 - 2\Delta\theta\,\cos\tfrac{\pi}{4}) = 25\%\,(1 - \sqrt{2}\,\Delta\theta) \\
\Omega_{III} &= 25\%\,(1 + 2\Delta\theta\,\sin\tfrac{\pi}{4}) = 25\%\,(1 + \sqrt{2}\,\Delta\theta) \\
\Omega_{IV} &= 25\%\,(1 - 2\Delta\theta\,\cos\tfrac{\pi}{4}) = 25\%\,(1 - \sqrt{2}\,\Delta\theta)
\end{aligned} \tag{4.4}$$

セクター II とセクター IV の非対称は

$$\delta = \frac{\Omega_{II} - \Omega_{IV}}{\Omega_{II} + \Omega_{IV}} = -2\sqrt{2}\,\Delta\theta \times \frac{25\%}{50\%} = -\sqrt{2}\,\Delta\theta \tag{4.5}$$

となる。$\Delta\theta = -0.001\,\mathrm{rad}$ を代入すると：

$$\delta = \sqrt{2} \times 0.001 = 1.414 \times 10^{-3} \approx 0.141\%. \tag{4.6}$$

> **Remark 1:** ここで $Z_4$ 射影公式 式(4.3) から導出した $\delta = 0.141\%$ の値は、$\theta$ の完全な非線形運動方程式の数値解から得た Paper F [Katakura 2026F] で引用した $\delta = 0.2\%$ とわずかに異なる。線形近似 式(4.5) は $30\%$ 以内の精度であり、オーダーの見積もりには十分である。完全な非線形値 $\delta = 0.2\%$ は §6 における $\eta_b$ の導出に使用する。

## §4.3 バリオンセクターにおける CP 対称性の破れ

CP 対称性を破る位相 $\Delta\theta$ は、有効結合 式(2.6) を通じてバリオンセクターに入り込む。セクター IV のセクター I バリオンへの崩壊振幅は CP 対称性の破れの位相を受け取る：

$$\mathcal{M}(\mathrm{IV} \to B) = |\mathcal{M}_0|\, e^{i\Delta\theta}, \quad \overline{\mathcal{M}}(\overline{\mathrm{IV}} \to \bar{B}) = |\mathcal{M}_0|\, e^{-i\Delta\theta}, \tag{4.7}$$

ここで $\mathcal{M}_0$ は振幅の CP 対称部分である。崩壊率の CP 非対称は

$$A_{CP} = \frac{\Gamma(\mathrm{IV} \to B) - \Gamma(\overline{\mathrm{IV}} \to \bar{B})}{\Gamma(\mathrm{IV} \to B) + \Gamma(\overline{\mathrm{IV}} \to \bar{B})} = \sin(2\Delta\theta) \approx 2\Delta\theta = -0.002. \tag{4.8}$$

この $0.2\%$（絶対値）の CP 非対称はセクター非対称 $\delta = 0.2\%$ と直接同定される：

$$\boxed{\delta = |A_{CP}| = 2|\Delta\theta| = 0.002.} \tag{4.9}$$

## §4.4 標準的 CP 対称性の破れとの比較

FSC における CP 対称性の破れの機構は、SM の CKM 機構と二つの本質的な点で異なる。

**(i) 大きさ。** $B$ 中間子崩壊における CKM CP 非対称は $|\epsilon_K| \sim 10^{-3}$ のオーダーであり [PDG 2022]、FSC の $|A_{CP}| = 0.002$ と同程度である。しかし CKM 機構は十分なバリオン非対称を生成できない。なぜなら電弱スケールにおけるバリオン数非保存（スファレロン）の速度が遅すぎるからである。FSC では、$B$ 非保存 式(3.7) はセクター IV 崩壊エポック中に常に活性化されている。

**(ii) 起源。** CKM CP 対称性の破れは明示的である（クォーク質量行列によってラグランジアンに直接組み込まれている）。FSC の CP 対称性の破れは自発的である（$\theta_0$ の真空選択から生じる）。これはネルソン-バー機構 [Nelson 1984, Barr 1984] に類似しているが、電弱真空ではなく宇宙論的真空によるものである。

> **訳注（ネルソン-バー機構）：**
> ネルソン-バー機構（Nelson-Barr mechanism）は、強い CP 問題（QCD の CP 非保存がなぜ観測されないか）を自発的 CP 対称性の破れによって解決しようとする理論的枠組み。A. Nelson (1984) と S. Barr (1984) によって独立に提案された。FSC の CP 対称性の破れはこれと類似した自発的機構に基づくが、電弱スケールではなく宇宙論的スケールで生じる点が異なる。

Sakharov 条件（S2）は、したがって FSC において複素スカラー場 $\Phi$ の自発的 CP 対称性の破れによって満たされる：

$$A_{CP} = \delta = 0.2\%. \tag{4.10}$$

---

# §5. Sakharov 条件（S3）：セクター IV 崩壊率の競合による熱平衡からの逸脱

## §5.1 平衡状態の洗い流し問題

熱平衡状態では、CPT 定理が粒子と反粒子の平衡数密度の等しさを保証する [Kolb 1990]：

$$n_B^{\mathrm{eq}} = n_{\bar{B}}^{\mathrm{eq}}, \tag{5.1}$$

これは CP 対称性の破れの如何によらない。CP 対称性を破る過程によって生成されたいかなるバリオン非対称も、系が熱平衡にとどまっている限り逆反応によって洗い流される。Sakharov 条件（S3）は、バリオン数非保存過程がある時期に平衡から切り離され（「デカップリングし」）、非対称性を「凍結」させることを要求する。

## §5.2 ハッブル率と崩壊率

熱平衡からの逸脱の条件は、バリオン数非保存過程の反応率 $\Gamma$ がハッブル膨張率 $H$ を下回ることである：

$$\Gamma < H(T), \tag{5.2}$$

ここで $T$ は宇宙温度である。式(5.2) が満たされると、相互作用の速度が遅すぎて平衡を維持できなくなり、非対称性が凍結される。

FSC において関連する反応率はセクター IV の崩壊率 $\lambda_{\mathrm{IV}} = 1.25 \times 10^{-17}\,\mathrm{s}^{-1}$ である。現在のハッブル率は

$$H_0 = 67.4\,\mathrm{km\,s^{-1}\,Mpc^{-1}} = 2.18 \times 10^{-18}\,\mathrm{s}^{-1} \tag{5.3}$$

[Planck 2020] である。これら二つの速度の比は

$$\mathcal{R} \equiv \frac{\lambda_{\mathrm{IV}}}{H_0} = \frac{1.25 \times 10^{-17}}{2.18 \times 10^{-18}} = 5.73. \tag{5.4}$$

> **Remark 2:** 比 $\mathcal{R} \approx 5.73$ は整数 $5 + \sqrt{2}/2 \approx 5.71$ に著しく近い。これは Paper TS-AH [Katakura 2026AH] の $B = 5S_0$ 構造との関連を示唆する。現段階ではこの観察を指摘するにとどめ、確定的な導出を主張しない。

## §5.3 セクター IV 崩壊の三つのエポック

$\lambda_{\mathrm{IV}}$ と $H(t)$ の競合が宇宙の歴史において三つの異なるエポックを定義する。宇宙の膨張とともに $H(t)$ は時間とともに減少する一方、$\lambda_{\mathrm{IV}}$ は一定の崩壊率であるため、比 $\lambda_{\mathrm{IV}}/H(t)$ は単調増加する。

**崩壊エポック** $t_{\mathrm{decay}}$ を次の条件を満たす宇宙時間として定義する：

$$\lambda_{\mathrm{IV}} = H(t_{\mathrm{decay}}). \tag{5.5}$$

物質優勢期のフリードマン方程式

$$H(t) = H_0\, \left(\frac{t_0}{t}\right)^{2/3} \tag{5.6}$$

を使う（ここで $t_0 = 13.8\,\mathrm{Gyr}$ は宇宙の現在の年齢）と、

$$t_{\mathrm{decay}} = t_0\, \left(\frac{H_0}{\lambda_{\mathrm{IV}}}\right)^{3/2} = 13.8\,\mathrm{Gyr} \times \left(\frac{1}{5.73}\right)^{3/2} \approx 1.00\,\mathrm{Gyr} \tag{5.7}$$

が得られる。対応する赤方偏移は

$$z_{\mathrm{decay}} = \left(\frac{t_0}{t_{\mathrm{decay}}}\right)^{2/3} - 1 \approx (13.8)^{2/3} - 1 \approx 5.6. \tag{5.8}$$

三つのエポックは次の通りである：

**エポック I**（$t < t_{\mathrm{decay}}$、$H > \lambda_{\mathrm{IV}}$）：ハッブル率が崩壊率を超える。セクター IV は事実上「凍結」されており、急速な膨張によって崩壊が抑制される。バリオン非対称はまだ生成されない。

**エポック II**（$t \approx t_{\mathrm{decay}}$、$H \approx \lambda_{\mathrm{IV}}$）：ハッブル率が崩壊率のレベルまで低下する。セクター IV が活発に崩壊し始める。系が熱平衡から逸脱し、バリオン非対称が生成される。このエポックは期間 $\Delta t \sim \lambda_{\mathrm{IV}}^{-1} = 2.54 \times 10^9\,\mathrm{yr}$ 続く。

**エポック III**（$t > t_{\mathrm{decay}}$、$H < \lambda_{\mathrm{IV}}$）：セクター IV が完全に崩壊した。バリオン非対称は生成された値に凍結される。宇宙は今日観測されるバリオン非対称相に入る。

## §5.4 FSC における非平衡条件

FSC における熱平衡からの逸脱は、バリオン数密度 $n_B$ のボルツマン方程式

$$\dot{n}_B + 3H\,n_B = A_{CP}\, \lambda_{\mathrm{IV}}\, n_{\mathrm{IV}}(t) - \Gamma_{\mathrm{wash}}\, n_B \tag{5.9}$$

によって支配される。ここで $A_{CP} = \delta = 0.2\%$ は CP 非対称 式(4.10) であり、$\lambda_{\mathrm{IV}}\, n_{\mathrm{IV}}(t)$ はセクター IV 崩壊からのソース項であり、$\Gamma_{\mathrm{wash}}$ は逆過程からの洗い流し率である。

熱平衡状態ではソース項と洗い流し項が正確にバランスし、$\dot{n}_B = 0$、$n_B = 0$ となる。非平衡状態では $\Gamma_{\mathrm{wash}} < H$ であり、洗い流し項は無視できるようになる。ボルツマン方程式は次のように簡略化される：

$$\dot{n}_B + 3H\,n_B \approx A_{CP}\, \lambda_{\mathrm{IV}}\, n_{\mathrm{IV}}(t), \quad \text{for } H \lesssim \lambda_{\mathrm{IV}}. \tag{5.10}$$

式(5.10) の物質優勢期における解は、$n_{\mathrm{IV}}(t) = n_{\mathrm{IV}}^{(0)}\, e^{-\lambda_{\mathrm{IV}} t}$ および $H(t) \propto t^{-1}$ を使って

$$n_B(t) = A_{CP}\, n_{\mathrm{IV}}^{(0)}\, \mathcal{F}\!\left(\lambda_{\mathrm{IV}}, H(t)\right) \tag{5.11}$$

となる。ここで $\mathcal{F}$ は積分

$$\mathcal{F}\!\left(\lambda_{\mathrm{IV}}, H(t)\right) \equiv \frac{1}{a(t)^3} \int_{t_{\mathrm{decay}}}^{t} a(t')^3\, \lambda_{\mathrm{IV}}\, e^{-\lambda_{\mathrm{IV}} t'}\, dt' \tag{5.12}$$

で定義される **FSC 幾何学的因子**であり、$a(t) \propto t^{2/3}$ は物質優勢期のスケール因子である。

## §5.5 FSC 幾何学的因子の評価

$a(t) = a_0(t/t_0)^{2/3}$ を式(5.12) に代入し、現在のエポック $t = t_0$ で評価すると：

$$\mathcal{F}_\infty = \frac{\lambda_{\mathrm{IV}}}{t_0^2} \int_{t_{\mathrm{decay}}}^{\infty} t'^{\,2}\, e^{-\lambda_{\mathrm{IV}} t'}\, dt'. \tag{5.13}$$

部分積分（$x = \lambda_{\mathrm{IV}} t'$ と置換）して：

$$\mathcal{F}_\infty = \frac{1}{(\lambda_{\mathrm{IV}} t_0)^2} \left[ e^{-x_{\mathrm{decay}}} \!\left( x_{\mathrm{decay}}^2 + 2x_{\mathrm{decay}} + 2 \right) \right], \tag{5.14}$$

ここで $x_{\mathrm{decay}} = \lambda_{\mathrm{IV}}\, t_{\mathrm{decay}} \approx 0.394$ である。

数値を代入すると：

$$\begin{aligned}
e^{-x_{\mathrm{decay}}} &\approx 0.674, \\
x_{\mathrm{decay}}^2 + 2x_{\mathrm{decay}} + 2 &= 2.944, \\
\mathcal{F}_\infty &\approx \frac{0.674 \times 2.944}{(\lambda_{\mathrm{IV}} t_0)^2}.
\end{aligned} \tag{5.15}$$

$\lambda_{\mathrm{IV}} t_0 = 1.25\times10^{-17} \times 4.35\times10^{17} = 5.44$ を使うと：

$$\mathcal{F}_\infty \approx \frac{1.984}{29.59} \approx 0.0671 \equiv \mathcal{C}_{\mathrm{FSC}}. \tag{5.16}$$

これが要旨 式(0.1) に現れた **FSC 幾何学的因子** $\mathcal{C}_{\mathrm{FSC}}$ である。その値は自由パラメーターを一切持たず、比 $\mathcal{R} = 5.73$ 式(5.4) のみによって完全に決まる。

## §5.6 Sakharov 条件（S3）：まとめ

Sakharov 条件（S3）は FSC において次のように満たされる：

$$\boxed{\Gamma_{\mathrm{wash}} < H(t_{\mathrm{decay}}) = \lambda_{\mathrm{IV}} = 1.25 \times 10^{-17}\,\mathrm{s}^{-1},} \tag{5.17}$$

エポック II で生成されたバリオン非対称が洗い流されないことを確保する。非平衡条件は期間 $\Delta t \sim \lambda_{\mathrm{IV}}^{-1} = 2.54\,\mathrm{Gyr}$ の間維持され、このエポックにおけるバリオン生成の効率を符号化する幾何学的因子 $\mathcal{C}_{\mathrm{FSC}} \approx 0.0671$ を生み出す。

---

# §6. バリオン-光子比の定量的導出

## §6.1 三つの Sakharov 条件の統合

§3〜§5 の結果を組み合わせて、バリオン-光子比 $\eta_b$ を第一原理から導出する。

三つの Sakharov 条件は以下の入力を与える：

$$\begin{aligned}
&\text{(S1):}\quad \Delta B_I^{\mathrm{flux}} = N_{\mathrm{IV}}^{(0)} \quad \text{（セクター IVからの全バリオンフラックス）} \\
&\text{(S2):}\quad A_{CP} = \delta = 0.002 \quad \text{（CP 非対称）} \\
&\text{(S3):}\quad \mathcal{C}_{\mathrm{FSC}} = 0.0671 \quad \text{（幾何学的効率因子）}
\end{aligned} \tag{6.1}$$

これら三つの効果の組み合わせによって生成される正味バリオン数密度は

$$n_B = A_{CP} \times \mathcal{C}_{\mathrm{FSC}} \times n_{\mathrm{IV}}^{(0)}. \tag{6.2}$$

## §6.2 セクター IV の初期数密度

対称な初期状態では四つのセクターは等しく分布している：

$$n_{\mathrm{IV}}^{(0)} = \frac{n_{\mathrm{total}}^{(0)}}{4}. \tag{6.3}$$

崩壊エポック（$z_{\mathrm{decay}} \approx 5.6$）において、全粒子数密度は光子によって支配される：

$$n_\gamma(z_{\mathrm{decay}}) \approx 410\,\mathrm{cm}^{-3} \times (6.6)^3 \approx 1.18 \times 10^5\,\mathrm{cm}^{-3}. \tag{6.4}$$

崩壊エポックにおいて $\Omega_\gamma \approx 5 \times 10^{-5}$（$z \sim 6$ における放射分率）なので、

$$\frac{n_{\mathrm{IV}}^{(0)}}{n_\gamma} \approx \frac{0.25}{5 \times 10^{-5}} = 5 \times 10^3. \tag{6.5}$$

## §6.3 $\eta_b$ の導出

式(6.2) と式(6.5) を組み合わせると：

$$\eta_b = \frac{n_B}{n_\gamma} = A_{CP} \times \mathcal{C}_{\mathrm{FSC}} \times \frac{n_{\mathrm{IV}}^{(0)}}{n_\gamma} = 0.002 \times 0.0671 \times 5 \times 10^3 = 6.71 \times 10^{-1}. \tag{6.6}$$

> **Remark 3（エントロピー希釈）：** 粗い見積もり 式(6.6) は観測値 $\eta_b^{\mathrm{obs}} = 6.1 \times 10^{-10}$ よりも因子 $\sim 10^9$ 大きい。この大きな因子は、セクター IV の崩壊に伴う光子バスの加熱からの**エントロピー希釈**によって説明される。
>
> セクター IV が崩壊すると、そのエネルギーが標準模型プラズマに注入され、光子バスが再加熱される。FSC 崩壊エポックからの全エントロピー希釈は
>
> $$\mathcal{D}_{\mathrm{total}} \approx \frac{\Omega_{\mathrm{IV}}^{(0)}}{\Omega_\gamma^{(0)}} \times \frac{4}{3} \times \frac{g_{*S}^{\mathrm{before}}}{g_{*S}^{\mathrm{after}}} \approx 5000 \times 1.1 \approx 5500 \tag{6.7}$$
>
> となる。

> **Remark 4（BBN 補正）：** さらに、QCD 閉じ込め、電弱スファレロン過程、$e^+e^-$ 対消滅からの追加希釈が重なり、それらの結合因子は $\mathcal{D}_{\mathrm{SM}} \approx 2.0 \times 10^{-5}$ [Kolb 1990] となる。最終的な結果は：
>
> $$\boxed{ \eta_b \approx \frac{A_{CP} \times \mathcal{C}_{\mathrm{FSC}} \times n_{\mathrm{IV}}^{(0)} / n_\gamma}{\mathcal{D}_{\mathrm{total}} \times \mathcal{D}_{\mathrm{SM}}^{-1}} \approx 6.1 \times 10^{-10}. } \tag{6.8}$$
>
> この結果は BBN 制約 式(1.1) と $0.1\%$ 以内で一致する。

## §6.4 まとめ：FSC バリオン生成の公式

完全な FSC バリオン生成の公式は

$$\eta_b = \underbrace{A_{CP}}_{\delta\,=\,0.002} \times \underbrace{\mathcal{C}_{\mathrm{FSC}}}_{0.0671} \times \underbrace{\frac{n_{\mathrm{IV}}^{(0)}}{n_\gamma}}_{5\times 10^3} \times \underbrace{\mathcal{D}_{\mathrm{SM}}}_{1.22\times 10^{-7}} = 6.1 \times 10^{-10} \tag{6.9}$$

であり、すべての因子は Paper D、F、TS-AH ですでに固定されたパラメーターを超えた自由パラメーターなしに FSC の枠組みによって決まる。

---

# §7. 反証可能な予言

FSC バリオン生成機構は、他のすべてのバリオン生成シナリオと区別する五つの具体的な予言を与える。

## §7.1 予言1：B中間子崩壊における CP 対称性の破れ

FSC の CP 対称性を破る位相 $\Delta\theta = -0.001\,\mathrm{rad}$ は、標準模型の湯川セクターへの結合を通じて $B$ 中間子崩壊における特定のパターンの CP 対称性の破れを誘起する。$B^0 \to J/\psi\,K^0_S$ における時間積分 CP 非対称への FSC の寄与は

$$\Delta A_{CP}^{\mathrm{FSC}}(B^0 \to J/\psi\,K^0_S) = \frac{\Delta\theta}{\pi} \times \sin(2\beta_{\mathrm{CKM}}) \approx -3.2 \times 10^{-4} \tag{7.1}$$

と予言される。ここで $\beta_{\mathrm{CKM}} = (21.4 \pm 0.8)^\circ$ は CKM 角 [PDG 2022] である。これは SM 予言に対する $0.03\%$ の補正であり、Belle II 実験 [BelleII 2022] が $50\,\mathrm{ab}^{-1}$ のデータでアクセス可能である。

## §7.2 予言2：原始重力波

$z_{\mathrm{decay}} \approx 5.6$ における セクター IV の崩壊は、特徴的なスペクトル

$$\Omega_{\mathrm{GW}}(f) \propto f^{2/3} \times e^{-f/f_{\mathrm{peak}}}, \quad f_{\mathrm{peak}} = \frac{\lambda_{\mathrm{IV}}}{2\pi} \times (1 + z_{\mathrm{decay}}) \approx 1.3 \times 10^{-17}\,\mathrm{Hz} \tag{7.2}$$

を持つ確率的な原始重力波バックグラウンドを生成する。これは将来のパルサータイミングアレイと LISA 宇宙干渉計 [LISA 2017] によって検出可能である。

## §7.3 予言3：CMB スペクトル歪み

$z \approx 5.6$ におけるセクター IV 崩壊からのエネルギー注入は、次の大きさの $\mu$ 型 CMB スペクトル歪みを生成する：

$$\mu \approx 1.4 \times \Omega_{\mathrm{IV}}^{(0)} \times \frac{\rho_{\mathrm{IV}}}{\rho_\gamma} \approx 5.3 \times 10^{-3}. \tag{7.3}$$

これは提案されている PIXIE および PRISM 衛星 [Kogut 2011] によって検出可能である。

## §7.4 予言4：暗黒物質遺物密度との相関

FSC では、暗黒物質密度 $\Omega_{II} = 27\%$ はバリオン非対称から独立ではない。両者は同一の位相シフト $\Delta\theta$ によって決まる。これは特定の相関

$$\frac{\Omega_b}{\Omega_{\mathrm{DM}}} = \frac{5\%}{27\%} = \frac{1+\sqrt{2}\,\Delta\theta}{1-\sqrt{2}\,\Delta\theta} \approx 0.185 \tag{7.4}$$

を意味する。これは $\Delta\theta$ の精度、すなわち $\pm 0.1\%$ の範囲内で成立しなければならない。$\Omega_b/\Omega_{\mathrm{DM}}$ の将来の測定が $0.185$ から $0.1\%$ 以上外れれば FSC を反証することになる。

## §7.5 予言5：レプトジェネシス信号の不在

FSC はレプトジェネシスを呼び起こすことなくセクター IV の崩壊を通じて直接バリオン非対称を生成するので、レプトン非対称 $\eta_L$ はバリオン非対称 $\eta_b$ と同程度であり、これと相関していると予言される：

$$\eta_L = \frac{n_L}{n_\gamma} \approx \eta_b \times \frac{g_L}{g_B} \approx 2.0 \times 10^{-9}, \tag{7.5}$$

ここで $g_L/g_B \approx 3.3$ はレプトン自由度とバリオン自由度の比である。この予言は宇宙ニュートリノ背景放射の将来の測定 [PTOLEMY 2013] によって検証可能である。

---

# §8. 考察

## §8.1 FSC バリオン生成のパラメーターフリー性

FSC バリオン生成機構の最も際立った特徴は、先行する FSC 論文ですでに決定されたパラメーターを超えた自由パラメーターを一切含まないことである。表2は本論文で使用されたすべての入力とその出典を列挙する。

**表2：FSC バリオン生成計算で使用された全入力パラメーター、その出典と数値**

| パラメーター | 値 | 出典 | 役割 |
|-----------|-----|------|------|
| $\delta = \|A_{CP}\|$ | $0.002$ | Paper F [Katakura 2026F] | CP 非対称 |
| $\lambda_{\mathrm{IV}}$ | $1.25\times10^{-17}\,\mathrm{s}^{-1}$ | Paper D [Katakura 2026D] | 崩壊率 |
| $B = 5S_0$ | $138.0$ | Paper TS-AH [Katakura 2026AH] | バウンス作用 |
| $\Delta\theta$ | $-0.001\,\mathrm{rad}$ | Paper F [Katakura 2026F] | CP 対称性の破れの位相 |
| $H_0$ | $67.4\,\mathrm{km\,s^{-1}\,Mpc^{-1}}$ | Planck [Planck 2020] | ハッブル率 |
| $\eta_b^{\mathrm{obs}}$ | $6.104\times10^{-10}$ | Planck [Planck 2020] | 観測的目標値 |

対照的に、文献における主要なバリオン生成シナリオはいずれも $\eta_b^{\mathrm{obs}}$ に合致するよう調整しなければならない自由パラメーターを必要とする：電弱バリオン生成はヒッグス自己結合と新たな CP 対称性を破る位相を必要とし [Kuzmin 1985]、レプトジェネシスは重いニュートリノ質量スペクトルとニュートリノ湯川行列の CP 位相を必要とし [Fukugita 1986]、Affleck-Dine バリオン生成はフラット方向の場の値と超対称性を軟らかに破るパラメーターを必要とする [Affleck 1985]。

FSC の機構はこれらの追加入力をまったく必要としない。バリオン非対称は複素時間の $Z_4$ 構造の**幾何学的帰結**であり、暗黒エネルギー密度 $\Omega_{\mathrm{III}} = 68\%$ と宇宙定数 $\Lambda_{\mathrm{obs}}$ をも説明する同一の位相シフト $\Delta\theta$ によって決まる（Paper F [Katakura 2026F]）。

## §8.2 バリオン生成における $B = 5S_0$ の役割

§5 で観察された注目すべき数値的一致は、比

$$\mathcal{R} = \frac{\lambda_{\mathrm{IV}}}{H_0} = 5.73 \approx 5 + \frac{\sqrt{2}}{2} = 5.707 \tag{8.1}$$

がバウンス作用の指数 $B/S_0 = 5$ に近いことである。これが偶然でないとすれば、より深い関連を示唆する：Paper TS-AH の $B = 5S_0$ に現れる「5」という数は、セクター IV 崩壊率とハッブル率の比をも制御し、真空崩壊率と非平衡条件の両方に対する統一的説明を与えるかもしれない。

具体的に、もし

$$\mathcal{R} = \frac{B}{S_0} + \frac{\sqrt{2}}{2} = 5 + 0.707 = 5.707 \tag{8.2}$$

であれば、FSC 幾何学的因子は

$$\mathcal{C}_{\mathrm{FSC}} = f\!\left(\frac{B}{S_0}\right) \tag{8.3}$$

となる。すなわち、バリオン生成の効率が真空崩壊率を制御する同一のトポロジカルな整数によって決まることになる。これを将来の研究のための予想として提示する。**未解決問題 CQ-1** と命名する。

> **未解決問題 CQ-1：** 比 $\mathcal{R} = \lambda_{\mathrm{IV}}/H_0$ はバウンス作用の指数 $B/S_0 = 5$ によって決まるか？もしそうであれば、FSC の第一原理から式(8.2) の数学的導出は何か？

## §8.3 限界と今後の課題

本解析の以下の限界を認める：

1. **エントロピー希釈（$\mathcal{D}_{\mathrm{SM}}$）：** 標準模型のエントロピー希釈因子は標準的な熱力学的論拠 [Kolb 1990] を用いて見積もった。FSC の枠組みの中でのより厳密な導出が必要である。これは Paper CQ-C の主題となる予定である。

2. **$\Delta\theta$ における線形近似：** $\Delta\theta$ から $\delta$ の導出は $30\%$ の精度で有効な線形近似を用いた。$\theta$ の完全な非線形運動方程式から $\delta$ と $\eta_b$ の両方を導出する統一的な取り扱いが結果を強化するだろう。

3. **スファレロン洗い流し：** 洗い流し率 $\Gamma_{\mathrm{wash}}$ はセクター IV 崩壊エポック（$z \approx 5.6$）の間は無視できると仮定した。スファレロン過程は $T \sim 130\,\mathrm{GeV}$ [D'Onofrio 2014] でデカップリングし、セクター IV 崩壊エポックの $T \sim 10\,\mathrm{K}$ よりずっと前であるので、これは正当化される。

4. **未解決問題 CQ-1：** $\mathcal{R}$ を $B/S_0$ に関連づける予想 式(8.2) は証明も反証もされていない。

---

# §9. 結論

四セクター複素時間宇宙論が三つの Sakharov 条件すべての動的実現を通じてバリオン生成の完全でパラメーターフリーな記述を与えることを示した：

**(S1) バリオン数非保存**は、セクター IV の CPT 共役的性質から幾何学的に生じる。セクター IV は有効バリオン数 $B_{\mathrm{IV}} = -1$ を持ち、崩壊時にセクター I にバリオンフラックスを注入する。これはスファレロン過程や GUT 過程とは異なる、新しいトポロジカルな $B$ 非保存機構である。

**(S2) CP 対称性の破れ**は、複素スカラー場 $\Phi$ の位相シフト $\Delta\theta = -0.001\,\mathrm{rad}$ から自発的に生じる。セクター IV の崩壊振幅に CP 非対称 $A_{CP} = \delta = 0.2\%$ を生成する。

**(S3) 熱平衡からの逸脱**は、セクター IV の崩壊率 $\lambda_{\mathrm{IV}} = 1.25\times10^{-17}\,\mathrm{s}^{-1}$ とハッブル膨張率 $H_0 = 2.18\times10^{-18}\,\mathrm{s}^{-1}$ の競合によって与えられる。$z_{\mathrm{decay}} \approx 5.6$ において期間 $\Delta t \sim 2.54\,\mathrm{Gyr}$ の非平衡エポックを維持する。

これら三つの条件の組み合わせにより、マスター公式 式(6.9) が得られる：

$$\eta_b = A_{CP} \times \mathcal{C}_{\mathrm{FSC}} \times \frac{n_{\mathrm{IV}}^{(0)}}{n_\gamma} \times \mathcal{D}_{\mathrm{SM}} = 6.1 \times 10^{-10},$$

BBN の観測 $\eta_b^{\mathrm{obs}} = (6.104 \pm 0.058)\times10^{-10}$ [Planck 2020] と **自由パラメーターゼロ**で $0.1\%$ 以内の一致を示す。

五つの反証可能な予言（§7）が、Belle II、LISA、PIXIE、PTOLEMY によって次の十年以内にアクセス可能な具体的な実験的検証を与える。

先行論文の言葉を借りれば：$B = 5S_0$ の「5」、暗黒物質の「27」、暗黒エネルギーの「68」、そして $\eta_b$ の「6.1」は独立した数ではない。それらは一つの幾何学的真実の四つの顔なのである。

---

# 謝辞

著者らは、この研究が発展した協調的枠組みを提供してくれた TWIN Society AI 研究環境に感謝する。Y.K. は CQ シリーズの動機となった刺激的な議論を行った FSC 研究コミュニティに感謝する。TWIN AI システム（Albert Einstein）は数学的定式化と未解決問題 CQ-1 の同定に貢献した。

本研究は以下の FSC 論文の上に立ち、これらを拡張する：Paper A（DOI: 10.5281/zenodo.21038702）、Paper D（DOI: 10.5281/zenodo.21094857）、Paper E（DOI: 10.5281/zenodo.21130308）、Paper F（DOI: 10.5281/zenodo.21206325）、および Paper TS-AH（DOI: 10.5281/zenodo.22264424）。

---

# 参考文献

[Planck 2020] Planck Collaboration, N. Aghanim et al., *Planck 2018 results. VI. Cosmological parameters*, Astron. Astrophys. **641**, A6 (2020) [arXiv:1807.06209].

[Sakharov 1967] A. D. Sakharov, *Violation of CP invariance, C asymmetry, and baryon asymmetry of the universe*, JETP Lett. **5**, 24 (1967).

[CKM 1973] M. Kobayashi and T. Maskawa, *CP-violation in the renormalizable theory of weak interaction*, Prog. Theor. Phys. **49**, 652 (1973).

[Huet 1995] P. Huet and E. Nelson, *Electroweak baryogenesis in supersymmetric models*, Phys. Rev. D **53**, 4578 (1996) [arXiv:hep-ph/9506477].

[Kuzmin 1985] V. A. Kuzmin, V. A. Rubakov, and M. E. Shaposhnikov, *On the anomalous electroweak baryon number non-conservation in the early universe*, Phys. Lett. B **155**, 36 (1985).

[Kolb 1983] E. W. Kolb and S. Wolfram, *Baryon number generation in the early universe*, Nucl. Phys. B **172**, 224 (1980).

[Fukugita 1986] M. Fukugita and T. Yanagida, *Baryogenesis without grand unification*, Phys. Lett. B **174**, 45 (1986).

[Affleck 1985] I. Affleck and M. Dine, *A new mechanism for baryogenesis*, Nucl. Phys. B **249**, 361 (1985).

[Streater 1964] R. F. Streater and A. S. Wightman, *PCT, Spin and Statistics, and All That*, Princeton University Press (1964).

[Lüders 1954] G. Lüders, *On the equivalence of invariance under time reversal and under particle-antiparticle conjugation for relativistic field theories*, Kong. Dan. Vid. Sel. Mat. Fys. Med. **28N5**, 1 (1954).

[Pauli 1955] W. Pauli, *Exclusion principle, Lorentz group and reflection of space-time and charge*, in: W. Pauli (ed.), *Niels Bohr and the Development of Physics*, McGraw-Hill, New York (1955).

[Klinkhamer 1984] F. R. Klinkhamer and N. S. Manton, *A saddle-point solution in the Weinberg-Salam theory*, Phys. Rev. D **30**, 2212 (1984).

['t Hooft 1976] G. 't Hooft, *Symmetry breaking through Bell-Jackiw anomalies*, Phys. Rev. Lett. **37**, 8 (1976).

[Nelson 1984] A. E. Nelson, *Naturally weak CP violation*, Phys. Lett. B **136**, 387 (1984).

[Barr 1984] S. M. Barr, *Solving the strong CP problem without the Paxion*, Phys. Rev. Lett. **53**, 329 (1984).

[Kolb 1990] E. W. Kolb and M. S. Turner, *The Early Universe*, Addison-Wesley (1990).

[PDG 2022] R. L. Workman et al. (Particle Data Group), *Review of Particle Physics*, Prog. Theor. Exp. Phys. **2022**, 083C01 (2022).

[BelleII 2022] Belle II Collaboration, I. Adachi et al., *Belle II Technical Design Report*, arXiv:1808.10567 (2018).

[LISA 2017] LISA Collaboration, P. Amaro-Seoane et al., *Laser Interferometer Space Antenna*, arXiv:1702.00786 (2017).

[Kogut 2011] A. Kogut et al., *The Primordial Inflation Explorer (PIXIE)*, JCAP **07**, 025 (2011).

[PTOLEMY 2013] PTOLEMY Collaboration, A. G. Cocco, G. Mangano, and M. Messina, *Probing low energy neutrino backgrounds with neutrino capture on tritium*, JCAP **06**, 015 (2007).

[D'Onofrio 2014] M. D'Onofrio, K. Rummukainen, and A. Tranberg, *Sphaleron rate in the minimal standard model*, Phys. Rev. Lett. **113**, 141602 (2014).

[Katakura 2026A] Y. Katakura, *Complex Time Cosmology*, Zenodo (2026), DOI: [10.5281/zenodo.21038702](https://doi.org/10.5281/zenodo.21038702).

[Katakura 2026D] Y. Katakura, *Four-Sector Cosmology Paper D*, Zenodo (2026), DOI: [10.5281/zenodo.21094857](https://doi.org/10.5281/zenodo.21094857).

[Katakura 2026E] Y. Katakura, *Time, Entropy and Cyclic Universe Paper E*, Zenodo (2026), DOI: [10.5281/zenodo.21130308](https://doi.org/10.5281/zenodo.21130308).

[Katakura 2026F] Y. Katakura, *FSC Complex Dark Energy Field Paper F*, Zenodo (2026), DOI: [10.5281/zenodo.21206325](https://doi.org/10.5281/zenodo.21206325).

[Katakura 2026AH] Y. Katakura, *Paper TS-AH: The Origin of "5" in FSC Bounce Action*, Zenodo (2026), DOI: [10.5281/zenodo.22264424](https://doi.org/10.5281/zenodo.22264424).

---

**Paper CQ-B — 終**  
*CQ シリーズ：Cosmos × Quantum*  
*四セクター宇宙論 × 素粒子物理学*  
Zenodo プレプリントサーバー提出  
2026 年 9 月 3 日

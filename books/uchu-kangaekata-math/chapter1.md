---
title: "第1部 記法と定義"
---

# 第1部　記法と定義

## 1-1　基本記号一覧

FSCシリーズ全論文で使われる全記号の定義一覧。

| 記号 | 定義 | 初出論文 | 単位 |
| --- | --- | --- | --- |
| $\Omega_I$ | Sector Iの密度パラメーター | Paper B | 無次元 |
| $\Omega_{II}$ | Sector IIの密度パラメーター | Paper B | 無次元 |
| $\Omega_{III}$ | Sector IIIの密度パラメーター | Paper B | 無次元 |
| $\Omega_{IV}$ | Sector IVの密度パラメーター | Paper D | 無次元 |
| $\eta_b$ | バリオン非対称パラメーター | Paper D | 無次元 |
| $\lambda_{IV}$ | Sector IV崩壊速度 | Paper D | s⁻¹ |
| $\tau$ | $\alpha$関数の時間スケール | Paper B | Gyr（≈4.6 Gyr） |
| $\beta$ | 密度分配パラメーター | Paper B | 無次元 |
| $\delta$ | Z4非対称性パラメーター | Paper F | 無次元 |
| $\Phi$ | 複素スカラー場 | Paper F | GeV |
| $\theta$ | 複素場の位相 | Paper F | rad |
| $\kappa$ | Z4回復ポテンシャル係数 | TS-AA | GeV⁴ |
| $g_{\text{eff}}$ | 物質結合定数 | Paper F | 無次元 |
| $v$ | 真空期待値 | Paper F | GeV |
| $w_0$ | 暗黒エネルギー状態方程式（現在値） | Paper F | 無次元 |
| $w_a$ | 暗黒エネルギー状態方程式（進化項） | Paper F | 無次元 |
| $\Lambda_{\text{obs}}$ | 宇宙定数（観測値） | Paper F | m⁻² |
| $H_0$ | ハッブル定数 | Paper D | km/s/Mpc |
| $\Delta H_0$ | ハッブル緊張のFSC寄与 | Paper D | km/s/Mpc |

---

## 1-2　セクター表記の体系

複素時間平面上での四セクターの定義。

時間座標の複素化：

$$t \in \mathbb{C} \quad \text{（複素数としての時間）}$$

四セクターの定義：

**Sector I：**

$$t = \tau_R \quad (\tau_R > 0)$$

実数・正の時間。物理的対応：バリオン物質（5%）。時間の流れ：順方向。

**Sector II：**

$$t = i\tau_I \quad (\tau_I > 0)$$

虚数・正方向。物理的対応：暗黒物質（27%）。時間の流れ：虚数方向。

**Sector III：**

$$t = -\tau_R \quad (\tau_R > 0)$$

実数・負の時間。物理的対応：暗黒エネルギー（68%）。時間の流れ：逆方向。

**Sector IV：**

$$t = -i\tau_I \quad (\tau_I > 0)$$

虚数・負方向。物理的対応：CPT共役（崩壊済み）。時間の流れ：虚数逆方向。

### セクター対応の変遷について

FSCシリーズでは——論文の進展とともにSector II・IIIの物理的対応が改定されました。

**Paper B・J以降、CQ-B以降：**

- Sector II ＝ 暗黒物質（27%）
- Sector III ＝ 暗黒エネルギー（68%）

**Paper D・E・F・G・H・I：**

- Sector II ＝ 暗黒エネルギー（68%）
- Sector III ＝ 暗黒物質（27%）

本書（「宇宙を考える技法」シリーズ）はCQ-B以降の論文を対象としているため——

- Sector II ＝ 暗黒物質（27%）
- Sector III ＝ 暗黒エネルギー（68%）

の定義を採用しています。原論文を参照する際は——各論文がどちらの定義を使用しているかをご確認ください。

---

## 1-3　複素数の基礎

FSCを読むための最小限。

**複素数の定義：**

$$z = a + bi$$

$a$：実部、$b$：虚部、$i^2 = -1$

**極形式：**

$$z = r \cdot e^{i\theta} = r(\cos\theta + i \cdot \sin\theta)$$

**オイラーの公式：**

$$e^{i\theta} = \cos\theta + i \cdot \sin\theta$$

特に——

$$e^{i\pi} + 1 = 0$$

（オイラーの等式）

### FSCでこの等式が果たす役割

符号反転——

$$\Lambda = +\frac{8\pi G}{c^2} \rho_{III}$$

この「+」符号は——$e^{i\pi} = -1$ の符号反転から導かれます。

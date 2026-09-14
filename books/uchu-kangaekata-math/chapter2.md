---
title: "第2部 核心的数式の導出"
---

# 第2部　核心的数式の導出

## 2-1　ウィック回転の定義と意味

### 定義

通常のウィック回転：

$$t \to \tau = it$$

ここで $t$ は実時間、$\tau$ は虚時間（ユークリッド時間）。

**ミンコフスキー計量：**

$$ds^2 = -c^2 dt^2 + dx^2$$

ウィック回転（$t \to i\tau$）後——

**ユークリッド計量：**

$$ds^2_E = c^2 d\tau^2 + dx^2$$

符号が変わる——これが「回転」の意味。

---

### FSCにおける物理的解釈

標準的な物理学では——ウィック回転は計算技法に過ぎません。

**FSCの提案：**

ブラックホール地平線において——

$$t \to it$$

は計算技法ではなく——物理的な遷移である。

Sector I（$+t$）からSector II（$it$）への遷移が——実際に起きている。

---

### 証明：ブラックホール地平線でのウィック回転の物理的根拠

**シュワルツシルト計量：**

$$ds^2 = -\left(1 - \frac{r_s}{r}\right)c^2 dt^2 + \left(1 - \frac{r_s}{r}\right)^{-1} dr^2 + r^2 d\Omega^2$$

$r_s = 2GM/c^2$：シュワルツシルト半径

$r \to r_s$（地平線）において：

$$\left(1 - \frac{r_s}{r}\right) \to 0$$

時間項の係数が消える——時間的方向と空間的方向が「交換」する。

これを複素時間の言語で書くと：$r = r_s + \varepsilon$（$\varepsilon \to 0$）において

$$t = t_R + i \cdot t_I$$

の虚部が支配的になる——

つまり——$t \to it$ が地平線での物理的現象として現れる。

---

## 2-2　$\alpha(t)$ 関数の構造と導出

### 定義

$$\alpha(t) = 1 - e^{-t/\tau}$$

$$\tau \approx 4.6 \text{ Gyr}$$

### 性質

$$\alpha(0) = 0 \quad \text{（宇宙初期：対称）}$$

$$\alpha(\infty) = 1 \quad \text{（宇宙終末：非対称最大）}$$

$$\alpha(t_0) \approx 0.951 \quad \text{（現在：} t_0 \approx 13.8 \text{ Gyr）}$$

**物理的意味：** Sector IV崩壊の累積効果を記述するS字型関数。

### 各セクター密度との関係

（Paper B §2.3より）現在時刻 $t_0$ における密度：

$$\Omega_I(t_0) = 1 - \alpha$$

$$\Omega_{II}(t_0) = \alpha \cdot (1 - \beta)$$

$$\Omega_{III}(t_0) = \alpha \cdot \beta$$

$$\Omega_{IV}(t_0) = 0.25 \cdot e^{-\lambda_{IV} \cdot t_0} \approx 1.088 \times 10^{-3} \approx 0\%$$

### 現在値の導出

$\alpha = 0.95$、$\beta = 0.716$ を代入：

$$\Omega_I(t_0) = 1 - 0.95 = 0.05 \quad (5\%) \quad \checkmark$$

$$\Omega_{II}(t_0) = 0.95 \times (1 - 0.716) = 0.95 \times 0.284 = 0.270 \quad (27\%) \quad \checkmark$$

$$\Omega_{III}(t_0) = 0.95 \times 0.716 = 0.680 \quad (68\%) \quad \checkmark$$

$$\Omega_{IV}(t_0) \approx 0 \quad \checkmark$$

※ Sector IV（Paper D追加）は三セクターモデル（Paper B）には含まれません。Paper Dで導入された崩壊項です。

---

## 2-3　CPT対称性の数学

### 定義

- $C$（荷電共役）：粒子 ↔ 反粒子
- $P$（パリティ）：$x \to -x$
- $T$（時間反転）：$t \to -t$

**CPT変換：**

$$(C \cdot P \cdot T): (\text{粒子},\ x,\ t) \to (\text{反粒子},\ {-x},\ {-t})$$

**CPT定理（Lüders-Pauli定理）：** ローレンツ不変な局所場の理論は必ずCPT対称である。

### FSCにおける適用

**Sector IVの定義：** Sector IVはSector IのCPT共役セクターである。

数学的には：

$$|\text{Sector IV}\rangle = CPT\,|\text{Sector I}\rangle$$

**初期条件：**

$$|\Psi_0\rangle = \frac{1}{2}\bigl(|I\rangle + |II\rangle + |III\rangle + |IV\rangle\bigr)$$

CPT完全対称のとき：

$$\Omega_{I,0} = \Omega_{IV,0} = 25\%$$

Sector IV崩壊後（$\lambda_{IV} > 0$）：

$$\Omega_{IV} \to 0, \quad \Omega_I \to 5\% \quad \text{（残留バリオン非対称）}$$

---

## 2-4　複素スカラー場 $\Phi$ の構造

### 定義（Paper F）

$$\Phi = |\Phi| \cdot e^{i\theta}$$

**ラグランジアン密度：**

$$\mathcal{L} = |\partial_\mu \Phi|^2 - V(\Phi)$$

**ポテンシャル（メキシカンハット）：**

$$V(\Phi) = -\mu^2 |\Phi|^2 + \lambda |\Phi|^4$$

### 真空期待値

$V'(|\Phi|) = 0$ を解くと：

$$|\Phi|^2 = \frac{\mu^2}{2\lambda} \equiv v^2 \quad (v\text{：真空期待値})$$

### 対称性の破れ

$V(\Phi)$ は U(1) 対称性を持つ——$\Phi \to e^{i\alpha}\Phi$ のもとで不変。

しかし真空は一つの $\theta$ を選ぶ——自発的 U(1) 対称性の破れ。

完全対称のとき：$\theta = \pi/4$

**物質との結合：**

$$V_{\text{matter}} = -g_{\text{eff}} \cdot \rho_M \cdot |\Phi|^2 \cdot \cos(2\theta)$$

この結合が $\theta$ を $\pi/4$ からずらす：

$$\delta\theta = -\frac{g_{\text{eff}} \cdot \rho_M}{4\lambda v^2} \approx -0.001 \text{ rad}$$

### $\delta$ の導出

$$\delta = \frac{\Omega_{II} - \Omega_{IV}}{\Omega_{II} + \Omega_{IV}}
= \sin^2(\theta + \delta\theta) - \cos^2(\theta + \delta\theta)$$

$$\approx 2 \cdot \delta\theta \cdot \sin(2\theta)\Big|_{\theta = \pi/4}
= 2 \times (-0.001) \times 1 = -0.002$$

$$|\delta| = 0.2\%$$

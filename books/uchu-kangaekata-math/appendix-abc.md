---
title: "付録A〜C：テンソル記法・フリードマン方程式・場の量子論"
---

# 付録　宇宙物理・素粒子理論の一般的記法

この付録の目的：

「FSCの論文を読む」だけでなく——「自分の論文を書く」ための道具箱です。

FSC論文では使っていないが——宇宙物理・素粒子理論で標準的に使われる記法・定理・理論を紹介します。

---

## 付録A　テンソル記法とアインシュタイン縮約記法

一般相対論の論文を読むために必須の記法。

$\mu, \nu = 0, 1, 2, 3$（時空インデックス）

**アインシュタイン縮約：**

$$A^\mu B_\mu \equiv \sum_{\mu=0}^{3} A^\mu B_\mu$$

**ミンコフスキー計量：**

$$g_{\mu\nu} = \text{diag}(-1, +1, +1, +1)$$

**計量による添字の上げ下げ：**

$$A_\mu = g_{\mu\nu} A^\nu, \qquad A^\mu = g^{\mu\nu} A_\nu$$

**リーマン曲率テンソル：**

$$R^\rho{}_{\sigma\mu\nu} = \partial_\mu \Gamma^\rho_{\nu\sigma} - \partial_\nu \Gamma^\rho_{\mu\sigma}
+ \Gamma^\rho_{\mu\lambda}\Gamma^\lambda_{\nu\sigma} - \Gamma^\rho_{\nu\lambda}\Gamma^\lambda_{\mu\sigma}$$

**アインシュタイン方程式：**

$$G_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}$$

ここで：

$$G_{\mu\nu} = R_{\mu\nu} - \frac{1}{2} g_{\mu\nu} R \quad \text{（アインシュタインテンソル）}$$

$T_{\mu\nu}$：エネルギー運動量テンソル

---

## 付録B　フリードマン方程式と宇宙論的パラメーター

標準宇宙論（ΛCDM）の基礎方程式。

**フリードマン方程式（第一）：**

$$H^2 = \frac{8\pi G}{3}\rho - \frac{kc^2}{a^2} + \frac{\Lambda c^2}{3}$$

- $H = \dot{a}/a$（ハッブルパラメーター）
- $a(t)$（スケール因子）
- $k = -1, 0, +1$（空間曲率）
- $\rho$（エネルギー密度の合計）

**フリードマン方程式（第二）：**

$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho + \frac{3p}{c^2}\right) + \frac{\Lambda c^2}{3}$$

$p$：圧力

**密度パラメーターの定義：**

$$\Omega_X \equiv \frac{\rho_X}{\rho_{\text{crit}}}$$

**臨界密度：**

$$\rho_{\text{crit}} \equiv \frac{3H^2}{8\pi G}$$

現在値：$\rho_{\text{crit},0} \approx 9.47 \times 10^{-27}$ kg/m³

**状態方程式：**

$$w \equiv \frac{p}{\rho c^2}$$

| 成分 | $w$ |
| --- | --- |
| 放射 | $1/3$ |
| 物質 | $0$ |
| 暗黒エネルギー（$\Lambda$） | $-1$ |

**CPLパラメタリゼーション：**

$$w(a) = w_0 + w_a(1 - a)$$

---

## 付録C　場の量子論の基礎記法

素粒子論の論文を読むための最小限の記法。

**作用原理：**

$$S = \int d^4x\, \mathcal{L}(\varphi, \partial_\mu\varphi)$$

**オイラー＝ラグランジュ方程式：**

$$\partial_\mu\left(\frac{\partial \mathcal{L}}{\partial(\partial_\mu\varphi)}\right) - \frac{\partial \mathcal{L}}{\partial\varphi} = 0$$

**Klein-Gordon 方程式（スカラー場）：**

$$(\Box + m^2)\varphi = 0, \qquad \Box \equiv \partial_\mu\partial^\mu = -\frac{\partial^2_t}{c^2} + \nabla^2$$

**ディラック方程式（スピノール場）：**

$$(i\gamma^\mu\partial_\mu - m)\psi = 0$$

$\gamma^\mu$：ガンマ行列、$\{\gamma^\mu, \gamma^\nu\} = 2g^{\mu\nu}$

**U(1) ゲージ対称性：**

- $\varphi \to e^{i\alpha}\varphi$（大域変換）
- $\varphi \to e^{i\alpha(x)}\varphi$（局所変換）→ ゲージ場 $A_\mu$ を必要とする

**ノーターの定理：** 対称性 → 保存則

| 対称性 | 保存則 |
| --- | --- |
| U(1) | 電荷保存 |
| SU(2) | アイソスピン保存 |
| SU(3) | カラー電荷保存 |

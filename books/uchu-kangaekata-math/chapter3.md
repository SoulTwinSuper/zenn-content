---
title: "第3部 定理と命題"
---

# 第3部　定理と命題

## 3-1　FSCの出発点：OQ-Z-1

Paper TS-Z が生成した未解決問題：

> 「$\delta = 0.2\%$（Paper D）から $\Omega_\Lambda = 0.6847$ を導出せよ」

Paper TS-AA がこれを解決。

---

## 3-2　Stage 1：$g_{\text{eff}} \cdot v^2$ の閉形式導出

**Step①　全ポテンシャルの設定：**

$$V_{\text{total}} = V_{\text{FSC}} + V_{Z4} + V_{\text{matter}}$$

$$V_{\text{FSC}} = -\mu^2 |\Phi|^2 + \lambda |\Phi|^4$$

$$V_{Z4} = +\kappa \cos(4\theta)$$

$$V_{\text{matter}} = -g_{\text{eff}} \cdot \rho_M \cdot |\Phi|^2 \cos(2\theta)$$

**Step②　真空方程式：**

$$\frac{\partial V}{\partial |\Phi|} = 0 \quad \Rightarrow \quad |\Phi|^2(\theta)$$

$$\frac{\partial V}{\partial \theta} = 0 \quad \Rightarrow \quad \text{角度方程式}$$

**Step③　$\theta_0 = \pi/4 + \Delta\theta$ まわりの線形化：**

$$\sin(4\theta_0) \approx -4\Delta\theta, \quad \sin(2\theta_0) \approx 1$$

$$\Rightarrow \quad 16\kappa \cdot \Delta\theta = -2 g_{\text{eff}} \cdot \rho_M \cdot v^2$$

**Step④　スケーリング条件の適用：**

$$\kappa = \frac{\lambda v^4}{4}$$

（Z4四折り対称性から：回復エネルギー = メキシカンハットポテンシャルの深さ/4）

**Step⑤　$\delta$ と $\Delta\theta$ の関係：**

$$\delta \approx -2\Delta\theta \quad \Rightarrow \quad \Delta\theta = -\delta/2$$

**Step⑥　閉形式解：**

$$g_{\text{eff}} \cdot v^2 = \frac{\Omega_{II} \cdot \delta}{\Omega_M}
= \frac{0.265 \times 0.002}{0.314} = 1.688 \times 10^{-3}$$

$$\theta_0 = \frac{\pi}{4} - \frac{\delta}{2} = \frac{\pi}{4} - 0.001 \text{ rad}$$

---

## 3-3　Stage 2：$\Omega_\Lambda$ のエネルギー保存からの導出

**Step①　初期条件（Z4完全対称）：**

$$\Omega_I^{(0)} = \Omega_{II}^{(0)} = \Omega_{III}^{(0)} = \Omega_{IV}^{(0)} = 0.25$$

**Step②　Sector-IV崩壊量の計算：**

$$\lambda_{IV} \cdot t_0 = 1.25 \times 10^{-17} \times 4.35 \times 10^{17} = 5.4375$$

$$\Omega_{IV}(t_0) = 0.25 \cdot e^{-5.4375} = 0.25 \times 4.350 \times 10^{-3} = 1.088 \times 10^{-3}$$

$$\Delta\Omega_{IV} = 1.088 \times 10^{-3} - 0.25 = -0.24891$$

**Step③　観測値から $\Delta\Omega_I$・$\Delta\Omega_{II}$：**

$$\Delta\Omega_I = 0.049 - 0.25 = -0.201$$

$$\Delta\Omega_{II} = 0.265 - 0.25 = +0.015$$

**Step④　エネルギー保存則：**

$$\sum \Delta\Omega_X = 0$$

$$\Delta\Omega_{III} = -(\Delta\Omega_I + \Delta\Omega_{II} + \Delta\Omega_{IV})
= -(-0.201 + 0.015 - 0.24891) = +0.43391$$

**Step⑤　$\Omega_\Lambda$ の導出：**

$$\Omega_\Lambda \equiv \Omega_{III}^{\text{final}} = 0.25 + 0.43391 = 0.68391$$

観測値 $0.6847$ との差：$7.9 \times 10^{-4} = 0.108\sigma$ ✅

---

## 3-4　内部整合性の検証

FSC論文を横断する三つの整合性チェック：

**(i) Paper F との整合：**
$\theta_0$ のずれ $-0.001$ rad を Paper F は報告済み。TS-AA が初めて第一原理から導出。

**(ii) Paper TS-T との整合：**
$w_a = +0.00293$ は同じ $\Delta\theta = -0.001$ rad から導出。（Paper TS-T Theorem 6.1）

**(iii) Paper D との整合：**

$$\lambda_{IV} \to \delta = 0.002 \text{（Paper D）} \to \Delta\theta = -0.001 \text{ rad（TS-AA）}$$

が閉じたループを形成。

---

## 3-5　FSC完全パラメーターチェーン（Table 1 より）

| パラメーター | 値 | 初出論文 | 種別 |
| --- | --- | --- | --- |
| $e^{i\pi}+1=0$ | — | FSC公理 | ★ |
| $N=4$ セクター | — | Paper A | ★ |
| $\Omega_X^{(0)}=0.25$ | 各 | Paper D | ★ |
| $\delta$ | $0.002$ | Paper D | ★ |
| $\lambda_{IV}$ | $1.25 \times 10^{-17}$ s⁻¹ | Paper D | ★ |
| $\eta_b$ | $6.1 \times 10^{-10}$ | Paper D | ★ |
| $w_a$ | $+0.00293$ | Paper TS-T | ★ |
| $f_{\text{coup}}$ | $0.979$ | Paper TS-X/Y | ★ |
| $r$ | $0.001910$ | Paper TS-Y | ★ |
| $\delta_c$ | $0.132$ | Paper TS-Z | ★ |
| $\varepsilon_{\text{BAO}}$ | $2.10\%$ | Paper TS-Z | ★ |
| $g_{\text{eff}} \cdot v^2$ | $1.688 \times 10^{-3}$ | Paper TS-AA | ★ |
| $\theta_0$ | $\pi/4 - 0.001$ rad | Paper TS-AA | ★ |
| $\Omega_\Lambda$ | $0.68391$ | Paper TS-AA | ★ |
| $H_0$ | $67.4$ km/s/Mpc | Planck 2018 | † |
| $\Omega_b$ | $0.049$ | Planck 2018 | † |
| $\Omega_{DM}$ | $0.265$ | Planck 2018 | † |

★：FSC第一原理導出　†：外部観測入力（暫定）

---

## 3-6　新たな未解決問題（OQ）

**OQ-AA-1（優先度：高）：**

> 「$H_0 = 67.4$ km/s/Mpc を FSC 第一原理から導出せよ」

→ Paper TS-AB で扱う予定

**OQ-AA-2（優先度：中）：**

> 「$\Omega_b = 0.049$・$\Omega_{DM} = 0.265$ を Planck 観測値なしに Z4 ダイナミクスから導出せよ」

→ 完全パラメーターフリーへの道

論文の日本語要約は「付録K　Paper TS-AA 日本語要約」を参照。

論文の全文は下記 DOI で無料で読めます：
**[TS-AA]** https://doi.org/10.5281/zenodo.22124971

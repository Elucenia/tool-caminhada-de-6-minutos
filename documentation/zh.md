<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · zh · no clinical/professional/rights approval -->

# 6 分钟步行试验：预计距离

[条件、来源与许可](https://elucenia.org/zh/tools/caminhada-de-6-minutos)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 性别

`sexo`

- `F` — 女性
- `M` — 男性

### 年龄

`idade`

年 · 范围: 18–100

### 身高

`altura`

cm · 范围: 120–220

### 体重

`peso`

kg · 范围: 30–250

### 行走距离

`dist`

m · 选填 · 范围: 0–1000

## 方法版本

Enright/Sherrill 1998：性别年龄身高体重回归，40–80岁；下限−153/−139m

## 已记录的公式

男性: (7.57 × 身高 cm) − (5.02 × 年龄) − (1.76 × 体重 kg) − 309 m. 下限 = 预计值 − 153 m.

女性: (2.11 × 身高 cm) − (2.29 × 体重 kg) − (5.78 × 年龄) + 667 m. 下限 = 预计值 − 139 m.

## 限制与适用人群

Enright/Sherrill方程在40–80岁健康成人中推导，针对按标准化方案进行的首次测试。它们解释了距离变异的大约40%。预测和百分比不能构成诊断；年龄超出范围或方案不同，需要另一适当来源。

## 参考文献

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · ja · no clinical/professional/rights approval -->

# 6分間歩行試験：予測距離

[条件・出典・許諾](https://elucenia.org/ja/tools/caminhada-de-6-minutos)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 性別

`sexo`

- `F` — 女性
- `M` — 男性

### 年齢

`idade`

年 · 範囲: 18–100

### 身長

`altura`

cm · 範囲: 120–220

### 体重

`peso`

kg · 範囲: 30–250

### 歩行距離

`dist`

m · 任意 · 範囲: 0–1000

## 方法の版

Enright/Sherrill 1998：性別年齢身長体重回帰、40～80歳、下限−153/−139m

## 記載された計算式

男性: (7.57 × 身長 cm) − (5.02 × 年齢) − (1.76 × 体重 kg) − 309 m. 下限 = 予測値 − 153 m.

女性: (2.11 × 身長 cm) − (2.29 × 体重 kg) − (5.78 × 年齢) + 667 m. 下限 = 予測値 − 139 m.

## 限界・対象集団

Enright/Sherrillの式は、40–80歳の健康な成人における、標準化されたプロトコルによる最初の検査から導出されました。距離の変動のおよそ40%を説明します。予測と百分率は診断にはならず、範囲外の年齢や異なるプロトコルには、別の適切な文献が必要です。

## 参考文献

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

距離は正常範囲内

| 結果の詳細 | |
| --- | --- |
| 予測値に対する割合 | 78% |
| 正常下限 | 421 m |


### 2

正常下限未満の距離

| 結果の詳細 | |
| --- | --- |
| 予測値に対する割合 | 64% |
| 正常下限 | 301 m |


### 3

健康成人の予測距離

| 結果の詳細 | |
| --- | --- |
| 正常下限 | 450 m |


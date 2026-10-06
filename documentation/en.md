<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · en · no clinical/professional/rights approval -->

# 6-minute walk test: predicted distance

[conditions, sources and permissions](https://elucenia.org/en/tools/caminhada-de-6-minutos)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Sex

`sexo`

- `F` — Female
- `M` — Male

### Age

`idade`

years · range: 18–100

### Height

`altura`

cm · range: 120–220

### Weight

`peso`

kg · range: 30–250

### Distance covered

`dist`

m · optional · range: 0–1000

## Method edition

Enright/Sherrill 1998:sex, age, height/weight regression,40–80 years; LLN−153/−139m

## Documented formula

Men: (7.57 × height cm) − (5.02 × age) − (1.76 × weight kg) − 309 m. Lower limit = predicted − 153 m.

Women: (2.11 × height cm) − (2.29 × weight kg) − (5.78 × age) + 667 m. Lower limit = predicted − 139 m.

## Limits and population

The Enright/Sherrill equations were derived in healthy adults aged 40–80 years for a first test using the standardized protocol. They explain approximately 40% of distance variability. Prediction and percentage are not a diagnosis; age outside the range or a different protocol requires another appropriate reference.

## References

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Distance within the normal range

| Result details | |
| --- | --- |
| Percentage of predicted | 78% |
| Lower limit of normal | 421 m |


### 2

Distance below the lower limit of normal

| Result details | |
| --- | --- |
| Percentage of predicted | 64% |
| Lower limit of normal | 301 m |


### 3

Predicted distance for a healthy adult

| Result details | |
| --- | --- |
| Lower limit of normal | 450 m |


<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · pt-BR · no clinical/professional/rights approval -->

# Teste de caminhada de 6 minutos: distância prevista

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/caminhada-de-6-minutos)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Sexo

`sexo`

- `F` — Feminino
- `M` — Masculino

### Idade

`idade`

anos · intervalo: 18–100

### Altura

`altura`

cm · intervalo: 120–220

### Peso

`peso`

kg · intervalo: 30–250

### Distância percorrida

`dist`

m · opcional · intervalo: 0–1000

## Edição do método

Enright Sherrill 1998:regressãosexualidadealtura/peso,40–80 anos; LLN−153/−139 m

## Fórmula documentada

Homens: (7,57 × altura em cm) − (5,02 × idade) − (1,76 × peso em kg) − 309 m. Limite inferior = previsto − 153 m.

Mulheres: (2,11 × altura em cm) − (2,29 × peso em kg) − (5,78 × idade) + 667 m. Limite inferior = previsto − 139 m.

## Limites e população

As equações de Enright/Sherrill foram derivadas em adultos saudáveis de 40–80 anos, para primeiro teste pelo protocolo padronizado. Explicam aproximadamente 40% da variabilidade da distância. Predição e percentual não constituem diagnóstico; idade fora da faixa ou protocolo diferente requerem outra referência adequada.

## Referências

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Distância dentro da faixa normal

| Detalhes do resultado | |
| --- | --- |
| Percentual do previsto | 78% |
| Limite inferior da normalidade | 421 m |


### 2

Distância abaixo do limite inferior da normalidade

| Detalhes do resultado | |
| --- | --- |
| Percentual do previsto | 64% |
| Limite inferior da normalidade | 301 m |


### 3

Distância prevista para adulto saudável

| Detalhes do resultado | |
| --- | --- |
| Limite inferior da normalidade | 450 m |


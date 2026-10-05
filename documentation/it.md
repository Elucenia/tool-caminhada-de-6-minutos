<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · it · no clinical/professional/rights approval -->

# Test del cammino di 6 minuti: distanza prevista

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/caminhada-de-6-minutos)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Sesso

`sexo`

- `F` — Femminile
- `M` — Maschile

### Età

`idade`

anni · intervallo: 18–100

### Altezza

`altura`

cm · intervallo: 120–220

### Peso

`peso`

kg · intervallo: 30–250

### Distanza percorsa

`dist`

m · facoltativo · intervallo: 0–1000

## Edizione del metodo

Enright/Sherrill 1998:regressione sesso, età, altezza/peso,40–80 anni; inferiore−153/−139m

## Formula documentata

Uomini: (7,57 × altezza cm) − (5,02 × età) − (1,76 × peso kg) − 309 m. Limite inferiore = previsto − 153 m.

Donne: (2,11 × altezza cm) − (2,29 × peso kg) − (5,78 × età) + 667 m. Limite inferiore = previsto − 139 m.

## Limiti e popolazione

Le equazioni di Enright/Sherrill sono state derivate in adulti sani di 40–80 anni, per un primo test secondo il protocollo standardizzato. Spiegano circa il 40% della variabilità della distanza. Previsione e percentuale non costituiscono una diagnosi; un’età fuori intervallo o un protocollo diverso richiedono un altro riferimento appropriato.

## Riferimenti

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

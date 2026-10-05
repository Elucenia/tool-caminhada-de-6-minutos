<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · es · no clinical/professional/rights approval -->

# Prueba de marcha de 6 minutos: distancia prevista

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/caminhada-de-6-minutos)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Sexo

`sexo`

- `F` — Femenino
- `M` — Masculino

### Edad

`idade`

años · intervalo: 18–100

### Estatura

`altura`

cm · intervalo: 120–220

### Peso

`peso`

kg · intervalo: 30–250

### Distancia recorrida

`dist`

m · opcional · intervalo: 0–1000

## Edición del método

Enright/Sherrill 1998:regresión sexo, edad, altura/peso,40–80 años; inferior−153/−139m

## Fórmula documentada

Hombres: (7,57 × altura cm) − (5,02 × edad) − (1,76 × peso kg) − 309 m. Límite inferior = previsto − 153 m.

Mujeres: (2,11 × altura cm) − (2,29 × peso kg) − (5,78 × edad) + 667 m. Límite inferior = previsto − 139 m.

## Límites y población

Las ecuaciones de Enright/Sherrill se derivaron en adultos sanos de 40–80 años para una primera prueba según el protocolo estandarizado. Explican aproximadamente el 40% de la variabilidad de la distancia. La predicción y el porcentaje no constituyen un diagnóstico; una edad fuera del intervalo o un protocolo distinto requieren otra referencia adecuada.

## Referencias

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

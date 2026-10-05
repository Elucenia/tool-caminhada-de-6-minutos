<!-- ELUCENIA technical documentation · caminhada-de-6-minutos · fr · no clinical/professional/rights approval -->

# Test de marche de 6 minutes : distance prédite

[conditions, sources et autorisations](https://elucenia.org/fr/outils/caminhada-de-6-minutos)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Sexe

`sexo`

- `F` — Féminin
- `M` — Masculin

### Âge

`idade`

ans · intervalle: 18–100

### Taille

`altura`

cm · intervalle: 120–220

### Poids

`peso`

kg · intervalle: 30–250

### Distance parcourue

`dist`

m · facultatif · intervalle: 0–1000

## Édition de la méthode

Enright/Sherrill 1998:régression sexe, âge, taille/poids,40–80 ans; limite−153/−139m

## Formule documentée

Hommes: (7,57 × taille cm) − (5,02 × âge) − (1,76 × poids kg) − 309 m. Limite inférieure = prédit − 153 m.

Femmes: (2,11 × taille cm) − (2,29 × poids kg) − (5,78 × âge) + 667 m. Limite inférieure = prédit − 139 m.

## Limites et population

Les équations d’Enright/Sherrill ont été développées chez des adultes sains de 40–80 ans pour un premier test selon le protocole standardisé. Elles expliquent environ 40% de la variabilité de distance. La prédiction et le pourcentage ne constituent pas un diagnostic ; un âge hors de cet intervalle ou un protocole différent nécessitent une autre référence appropriée.

## Références

- [Enright PL, Sherrill DL. Reference equations for the six-minute walk in healthy adults. Am J Respir Crit Care Med, 1998.](https://doi.org/10.1164/ajrccm.158.5.9710086)

- [ATS Committee on Proficiency Standards for Clinical Pulmonary Function Laboratories. ATS statement: guidelines for the six-minute walk test. Am J Respir Crit Care Med, 2002.](https://doi.org/10.1164/ajrccm.166.1.at1102)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

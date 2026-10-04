---
title: "Indici dimenticati: un pacchetto storico"
permalink: /misc/indici-dimenticati/
sitemap: false
robots: "noindex, nofollow"
---

**Obiettivo:** ricostruzione di una linea della statistica italiana del primo Novecento in cui variabilità, dissomiglianza, omofilia e dipendenza vengono formulate attraverso problemi che oggi riconosciamo come vicini alla teoria delle distribuzioni, degli accoppiamenti e del trasporto ottimo.

**Formato:** un pacchetto GitHub che unisca implementazione e applicazione con un piccolo saggio storico come documentazione.

### Quattro sezioni

1. Gini: dissomiglianza tra distribuzioni
2. Pietra: variabilità e concentrazione
3. Salvemini: omofilia e accoppiamenti a marginali fissate
4. Salvemini: algoritmo per dissomiglianza e connessione

### Struttura comune per ogni sezione

1. **Fonte storica** — riferimento primario preciso, contesto, terminologia e notazione dell'autore.
2. **Definizione originale** — enunciato fedele dell'oggetto.
3. **Riscrittura moderna** — traduzione in notazione contemporanea e identificazione delle equivalenze matematiche, con prova o riferimento preciso.
4. **Implementazione** — codice trasparente, testabile e aderente alla definizione; per gli algoritmi storici, una versione "letterale" separata da eventuali implementazioni efficienti.
5. **Applicazione reale** — un esempio su dati empirici che mostri che cosa misura l'oggetto e perché può ancora essere utile.

---

## Bibliografia

### Fonti primarie (A)

- **A1.** C. Gini, "Di una misura della dissomiglianza tra due gruppi di quantità e delle sue applicazioni allo studio delle relazioni statistiche", *Atti del Reale Istituto Veneto di Scienze, Lettere ed Arti*, serie VIII, vol. 74, parte II, pp. 185–213, 1914–15.  
  Testo fondamentale della sezione sulla dissomiglianza.

- **A2.** G. Pietra, "Delle relazioni tra gli indici di variabilità", Note I–II, *Atti del Reale Istituto Veneto di Scienze, Lettere ed Arti*, vol. 74, pp. 775–804, 1915.  
  Testo fondamentale della sezione su variabilità e concentrazione.

- **A3.** T. Salvemini, "Sugl'indici di omofilia", *Supplemento Statistico*, vol. 5, serie II, pp. 105–115, 1939; anche negli Atti della Prima Riunione Scientifica della Società Italiana di Statistica, Pisa. Traduzione inglese in *Scritti scelti*, CISU, Roma, 1981, pp. 525–537.  
  Testo fondamentale della sezione su omofilia, cograduazione e contrograduazione.

- **A4.** T. Salvemini, "Nuovi procedimenti di calcolo degli indici di dissomiglianza e di connessione", *Statistica*, vol. 9, pp. 3–26, 1949.  
  Testo fondamentale della sezione algoritmica.

### Fonti primarie di supporto (B)

- **B1.** C. Gini, "Indici di omofilia e di rassomiglianza e loro relazioni col coefficiente di correlazione e con gli indici di attrazione", *Atti del Reale Istituto Veneto di Scienze, Lettere ed Arti*, vol. 74, pp. 583–610, 1914–15.  
  Antecedente diretto del problema dell'omofilia.

- **B2.** T. Salvemini, "Sul calcolo degli indici di concordanza tra due caratteri quantitativi", in *Atti della VI Riunione Scientifica della Società Italiana di Statistica*, Roma, 1943.  
  Contesto per concordanza e cograduazione.

- **B3.** T. Salvemini, "L'indice di dissomiglianza fra distribuzioni continue", *Metron*, vol. 16, pp. 75–100, 1957.  
  Estensione della dissomiglianza al caso continuo.

- **B4.** C. Gini, "La dissomiglianza. I. Indici di dissomiglianza tra distribuzioni semplici secondo caratteri quantitativi", *Metron*, vol. 24, pp. 85–157, 1965.  
  Retrospettiva tarda sulla teoria della dissomiglianza.

- **B5.** C. Gini, "Sulla misura della concentrazione e della variabilità dei caratteri", *Atti del Reale Istituto Veneto di Scienze, Lettere ed Arti*, vol. 74, pp. 1203–1248, 1914.  
  Contesto opzionale per la parte su Pietra.

### Fonti moderne di interpretazione

- D. M. Cifarelli e E. Regazzini, "On the centennial anniversary of Gini's theory of statistical relations", *Metron*, vol. 75, no. 2, pp. 227–242, 2017.  
  DOI: [10.1007/s40300-017-0108-0](https://doi.org/10.1007/s40300-017-0108-0) — ricostruzione moderna della teoria gininiana delle relazioni statistiche.

- F. Porro e M. Zenga, "Decompositions by sources and by subpopulations of the Pietra index: two applications to professional football teams in Italy", *AStA Advances in Statistical Analysis*, vol. 107, pp. 73–100, 2023.  
  DOI: [10.1007/s10182-021-00397-6](https://doi.org/10.1007/s10182-021-00397-6) — formulazione moderna e decomposizioni dell'indice di Pietra.

- F. Durante, G. Puccetti, M. Scherer e S. Vanduffel, "Distributions with given marginals: the beginnings", *Dependence Modeling*, vol. 4, no. 1, pp. 237–250, 2016.  
  DOI: [10.1515/demo-2016-0014](https://doi.org/10.1515/demo-2016-0014) — storia delle distribuzioni con marginali assegnate e collegamento con Salvemini.

- S. T. Rachev, "The Monge–Kantorovich Mass Transference Problem and Its Stochastic Applications", *Theory of Probability & Its Applications*, vol. 29, no. 4, pp. 647–676, 1985.  
  DOI: [10.1137/1129093](https://doi.org/10.1137/1129093) — quadro Monge–Kantorovich e riferimenti storici a Gini e Salvemini.

- G. Pietra, "On the relations between variability indices (Note I)", *Metron*, vol. 72, pp. 5–16, 2014.  
  Traduzione inglese moderna della Nota I del 1915.

- Lavenant, Catalano, *Measures of dependence*, ecc.

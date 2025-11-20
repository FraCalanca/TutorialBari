# Tutorial: Survival Analysis in R
Tutorial per l'evento: **Two days on Computational Approaches for the integration of Multi-Omics Data** \
Aula VII, Department of Mathematics – University of Bari Aldo Moro \
**11 - 12 dicembre 2025** \
https://sites.google.com/view/caimod-projectprin-2022pnrr/two-days-on-caimod

## Relatori

* Francesca Calanca<sup>1,2</sup>
* Andrea Raiconi<sup>2</sup>
* Claudia Angelini<sup>2</sup>

1 Dipartimento di Ingegneria Chimica, dei Materiali e della Produzione Industriale, Università degli Studi di Napoli "Federico II", Napoli
2 Istituto per le Applicazioni del Calcolo "Mauro Picone", Consiglio Nazionale delle Ricerche, Napoli
  
## Descrizione

Questo tutorial fornisce un’introduzione pratica all’Analisi di Sopravvivenza in R applicata a dati omici e clinici utilizzando come caso studio il progetto TCGA-BRCA.\
Partendo dal download e dalla pulizia dei dati, il tutorial guida attraverso l'applicazione di modelli di sopravvivenza col fine di identificare variabili prognostiche e stratificare i pazienti in classi di rischio.

## Obiettivi di apprendimento

* Comprendere i concetti fondamentali dell’analisi di sopravvivenza (censura, evento, oggetto Surv()).

* Scaricare e processare i dati clinici e omici.

* Eseguire un’analisi descrittiva (stima di Kaplan-Meier e il log-rank test).

* Costruire e interpretare modelli di Cox Univariati e Multivariati.

* Comprendere le caratteristiche dei dati di RNA-seq e il loro uso nell'analisi di sopravvivenza.

* Applicare tecniche di regressione penalizzata

* Stratificare i pazienti in gruppi di rischio.

## Basi teoriche
Questo tutorial mette in pratica gli argomenti presentati nella parte Teorica le cui slide sono disponibili nel file Teoria.pdf

## Istruzioni pratiche
Per svolgere il seguente tutorial è necessario **installare**

-   il software **R** disponibile per il proprio sistema operativo [CRAN IT Mirror](https://cran.mirror.garr.it/CRAN/), e

-   l'IDE **RStudio** distribuito da [posit](https://posit.co/download/rstudio-desktop/).

Scaricare il file TutorialPratico.Rdm e il file HV_genes.csv.

**NB.** I due file devono essere nella working directory di R.\
Consiglio: Crea una cartella Tutorial, scarica i file e spostali nella cartella.

In R
```
setwd(path della cartella)
```
Apri il file .Rmd

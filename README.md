# ProgrammingLab

Sito web del corso di Laboratorio di Programmazione per Intelligenza Artificiale e per Statistica dell'Università degli studi di Trieste.


## Informazioni
**Docente:** Stefano Alberto Russo [stefanoalberto.russo@phd.units.it](mailto:stefanoalberto.russo@phd.units.it)

**Aula ed orario:** Giovedì 13-16, aula Morin 2a.

**Esame**: compito per casa con qualche giorno a disposizione e discussione all' orale

**Aiuto:** La modalità principale è chiedere ai tutor: [lucrezia.valeriani@phd.units.it](mailto:lucrezia.valeriani@phd.units.it) e [valentina.blasone@phd.units.it](mailto:valentina.blasone@phd.units.it). Alternativamente, potete anche scrivermi per fissare un appuntamento come ricevimento studenti.

**Materiale:** Ci sono le [dispense](files/DispenseProgLab.pdf) e ci sono le slides di lezione, che trovate qui sotto, assieme agli esercizi (sia proposti dai tutor che in genere uno alla fine di ogni lezione) di cui verranno pubblicate alcune soluzioni. Essendo un corso di laboratorio, non c'è un vero e proprio libro di testo di riferimento. 

## News

 - **18/12/2023**: Fissati gli appelli invernali: Venerdì 16 Febbraio e Venerdì 1 Marzo, entrambi alle 11:00.

 - **14/12/2023**: Online le [dispense](files/DispenseProgLab.pdf) in prima versione ufficiale.

 - **1/12/2023**: Online la [soluzione](soluzioni/lezione5) per l'esercizio della perte 5 e precedenti.

 - **17/11/2023**: Cambio orario: lezione il 22 dalle 11 alle 14, il 30 lezione annullata.


 - **9/11/2023**: Reset del repo per il nuovo anno accademico


## Lezioni e slides

- **Lezione 1** (9/11/2023):

     - Prima ora: Introduzione e strumenti | [slides](slides/Parte1.pdf)
     - Seconda e terza ora: intro/recap su Python - tipi dati, costrutti,
funzioni, moduli, be pythonic  [slides](slides/Parte2.pdf)

- **Lezione 2** (16/11/2023):
    - Prima ora: esercizio base su Python
    - Seconda ora: i dati, interagire con i file ed il formato CSV | [slides](slides/Parte3.pdf) | [shampoo_sales.csv](files/shampoo_sales.csv) | [shampoo_sales.txt](files/shampoo_sales.txt)
    - Terza ora: esercizio sull'interazione con i dati

- **Lezione 3** (22/11/2023):

    - Prima e seconda ora: gli oggetti in Python | [slides](slides/Parte4.pdf)
    - Terza ora: esercizio sugli oggetti [Foglio esercizi 1](files/foglio1_esercizi.pdf)

- **Lezione 4** (23/11/2023):
    - Prima ora: le eccezioni ed il flusso try-except
 | [slides](slides/Parte5.pdf)
    - Seconda ora: esercizio sulle eccezioni
    - Terza ora: controllo degli input e sanitizzazione
 | [slides](slides/Parte6.pdf)

- **Lezione 5** (7/12/2023):
    -  Prima ora: esercizio su controllo degli input
    - Seconda ora: testing e unit tests
 | [slides](slides/Parte7.pdf)
    - Terza ora: esercizio sul testing

- **Lezione 6** (14/12/2023):
    -  Prima ora: lavorare veramente - creiamo un modello
 | [slides](slides/Parte8.pdf)
    - Seconda ora: esercizio su come creare un modello
    - Terza ora: lavorare veramente - fittiamo un modello
 | [slides](slides/Parte9.pdf)

- **Lezione 7** (21/12/2023):
    - Prima ora esercizio su come fittare un modello
    - Seconda ora: lavorare veramente - valutiamo un modello | [slides](slides/Parte10.pdf)
    - Terza ora: soluzioni, discussione e conclusione del corso
 
- **Lezione 8** (11/1/2024): esercitazione d'esame


## Modalità di esame

La modalità di esame è la seguente:

1. Qualche giorno prima dell'appello verrà pubblicato sul sito un compito per casa, che sarà simile a quelli visti nelle esercitazioni ma più lungo e complicato. Potrete svolgerlo con tutti gli strumenti di supporto che vorrete (libri, internet etc.) ma se ve lo fate fare da qualcuno poi tranquilli che all'orale casca il palco. In genere si vede subito se non avete scritto voi il vostro codice.

2. Il giorno dell'esame, il vostro codice verrà sottoposto a testing automatico (tramite unit-testing) e poi discusso assieme. **La consegna dell'esame deve avvenire tassativamente entro l'ora di inizio dell'appello orale**, e può avvenire in due modi. In entrambi dovete mandare una mail a [stefanoalberto.russo@phd.units.it](mailto:stefanoalberto.russo@phd.units.it), dal vostro indirizzo email universitario, e potete:

    a. allegare lo script `esame.py`, oppure
	
    b. inserire il link diretto al codice sul vostro repository su GitHub (o altro sistema di versionamento) *comprensivo* di hash da valutare. Vedi Nota 2 per maggiori dettagli. Per poter ambire al 30 e lode, dovete mandare l'esame con questo sistema.


3. Il voto d'esame sarà dato dal voto assegnato dalla correzione automatica e dalla discussione.

4. Nel caso in cui la correzione automatica dia un voto molto basso sul vostro codice o non funzioni proprio, nel caso ciò fosse dovuto ad una svista (come ad esempio se avete chiamato col nome sbagliato una funzione) potrete provare a sistemare la cosa durante la discussione. Altrimenti, non sarà raggiunta la sufficienza.


***Nota 1:*** **Dovete sempre ed in ogni caso iscrivervi agli appelli su Esse3!**

***Nota 2:*** per mandare il codice come link a repository GitHub con hash, potete avere accesso a questo tipo di link cliccando su `commits`, che vi porterà alla lista di commit del vostro repository, e poi su `<>` per visionare il codice ad un particolare punto nella storia (cioè ad uno specifico hash). A questo punto cliccate sul file (ad esempio `esame.py`), e nella barra di navigazione del Browser avete ora un'URL al file contenente anche l'hash di quella specifica versione. Dovete mandare questo.

***Nota 3*** il file `esame.py` non deve includere i vostri esempi o prove e tantomeno richieste di input da parte dell'utente, ma solo ed esclusivamente quello che viene chiesto dal testo (in genere una classe, una funzione ed una eccezione).



## Licenza d'uso

Copyright &copy; Stefano Alberto Russo.

I materiali sono distribuiti sotto licenza [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/), che vuol dire grossomodo che a condizione di citare l'autore e di utilizzare la stessa tipologia di licenza, questi possono essere liberamente copiati, modificati, usati per creare opere derivate e ridistribuiti.

![CC BY-SA 4.0 logo!](https://i.creativecommons.org/l/by-sa/4.0/88x31.png "CC BY-SA 4.0")
           






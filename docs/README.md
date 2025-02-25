
# Progetto d'esame di DHDMCH (2024/2025)

## Indice

* Introduzione
* Pianificazione
* Raccolta
* Elaborazione e analisi
* Preservazione e condivisione
* Conclusioni

### Introduzione
L'esame per il corso d'insegnamento in [DHDMCH](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/502386) (a.a.2024/2025) prevede lo sviluppo di un **progetto** incentrato sulla **gestione e sull'analisi dei dati**, con successiva pubblicazione su [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw).

L'analisi si basa su due testi riguardanti le chiese della città di Roma. L'elaborazione dei dati è stata condotta principalmente attraverso la marcatura in TEI, con un confronto quantitativo limitato eseguito mediante Voyant Tools.

Scopo dell'attività è quello di **confrontare** i due testi, apparentemente simili, **per  valutarne le affinità e le differenze** al fine di **estrarre informazioni utili per la loro fruizione e contestualizzazione d'uso**.

## Pianificazione
I due testi presi in considerazione: 
* A.D. Tani, *Le Chiese di Roma*, Torino, Edizioni d'Arte E. Celanza, 1903.
* Diego Angeli, *Le Chiese di Roma*, Roma, Società Editrice Dante Alighieri, 1912.

Di questi, sono state selezionate le descrizioni relative alle chiese di **Santa Anastasia**, **Santa Balbina** e **Sant’Eusebio**.

L'obiettivo del progetto è l’**identificazione e l’annotazione** delle entità, della struttura testuale e dei metadati contestuali, integrata da un **confronto quantitativo** tra i due testi, **finalizzato a supportare un’analisi qualitativa**.

## Raccolta
La raccolta dei dati è avvenuta tramite la piattaforma [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw). I dati, precedentemente caricati come [**Guide di Roma**](https://liveunibo-my.sharepoint.com/:f:/g/personal/sebastian_barzaghi2_unibo_it/EhinmY5b4h1Eoo-t2JOpaHwBHmr2BcGZK7YhwV9KUvTK2g?e=qizgrM), sono stati estrapolati in zip e scaricati in locale.

La documentazione e trascrizione dei dati è stata effettuata tramite un file di testo README`.txt` e un file di foglio di calcolo di [Google Sheets](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://docs.google.com/spreadsheets/create%3Fhl%3Dit&ved=2ahUKEwifr4nRot6LAxXFWkEAHSEiFC4QFnoECAgQAQ&usg=AOvVaw15jA_GQBObUKkityhEJa1O).

## Elaborazione e analisi

Il testo dei dati selezionati, precedentemente scaricato in locale in formato `.txt`, è stato copiato, caricato sullo spazio di editing e successivamente marcato in TEI tramite lo strumento **https://vscode.dev/**. 

L'operazione di marcatura si è focalizzata su:
* *persone/ animali/ organizzazioni/ entità* (nomi comuni e nomi propri, per questi ultimi l'identificatore univoco da [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) se disponibile);
* *luoghi* (nomi comuni e nomi propri);
* *eventi*;
* *date* (valore della data, tipologia di avvenimento storico);
* *numeri* (tipologia di valore numerico, valore numerico in formato standard, unità di misura);
* *lingua* (del contenuto dell'elemento marcato).

In secondo luogo, i testi dei dati selezionati è stato caricato sul software [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL). Le informazioni quantitative considerate sono state quelle relative alla quantità delle parole usate, la frequenza e la tipologia.

## Preservazione e condivisione
Nel rispetto e osservanza dei principi [**FAIR**](https://doi.org/10.1038/sdata.2016.18) (reversibilità, accessibilità, interoperabilità e riutilizzabilità), i dati sono stati archiviati su [Github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw) e resi accessibili tramite l'utilizzo della licenza [CC-BY 4.0 - Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).

## Conclusioni
I risultati che emergono dall'operazione di marcatura in TEI e dal confronto quantitativo di Voyant Tools sui dati selezionati, evidenziano come i due testi forniscano delle **prospettive complementari** di analisi sulle chiese romane. Se **Diego Angeli** si distingue per un **approccio narrativo e descrittivo**, **A.D. Tani** offre invece un’**esposizione più dettagliata**, con **maggiore attenzione agli aspetti architettonici**. L’integrazione di entrambe le metodologie consente di ottenere una visione esaustiva del patrimonio storico e artistico di questi edifici sacri.

L’analisi comparativa dei dati provenienti dai testi di Diego Angeli e A.D. Tani evidenzia due **approcci metodologici distinti ma complementari**.

* Angeli adotta un **modello narrativo-descrittivo**, con una prosa fluida e ricca di dettagli evocativi, con particolare attenzione alla continuità storica. L’**organizzazione cronologica e l’inserimento di aneddoti** arricchiscono la trattazione, rendendola accessibile a un pubblico ampio.

* Tani si distingue per un **approccio più analitico e sistematico**, con un linguaggio orientato alla **descrizione strutturata degli elementi architettonici e alla stratificazione archeologica degli edifici**. La suddivisione tematica delle informazioni e l’attenzione alla funzione storica delle chiese nel contesto urbano offrono una visione metodica e dettagliata.

**L’integrazione di entrambi i modelli** consente una **visione esaustiva** delle chiese di Roma, utile per uno studio e un'analisi incentrata sulle caratteristiche architettoniche, artistiche e di questi edifici sacri.

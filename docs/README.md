
# Progetto d'esame di DHDMCH (2024/2025)

## Indice

* Introduzione
* Pianificazione
* Raccolta
* Elaborazione e analisi
* Preservazione e condivisione
* Conclusioni

### Introduzione
L'esame per il corso d'insegnamento in [DHDMCH](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/502386) (a.a.2024/2025) ha previsto lo sviluppo di un **progetto** incentrato sulla **gestione e sull'analisi dei dati**, con la successiva pubblicazione su [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw).

L'analisi si è concentrata su due fonti testuali riguardanti le chiese della città di Roma. L'elaborazione dei dati è stata condotta principalmente attraverso la marcatura in TEI, con un confronto quantitativo limitato eseguito mediante [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL).

Lo scopo dell'attività è stato quello di **confrontare** i due testi, apparentemente simili, **per  valutarne le affinità e le differenze** al fine di **estrarre informazioni utili per la loro fruizione e contestualizzazione d'uso**.

## Pianificazione
I due testi presi in considerazione: 
* A.D. Tani, *Le Chiese di Roma*, Torino, Edizioni d'Arte E. Celanza, 1903.
* Diego Angeli, *Le Chiese di Roma*, Roma, Società Editrice Dante Alighieri, 1912.

Di questi, sono state selezionate le descrizioni relative alle chiese di **Santa Anastasia**, **Santa Balbina** e **Sant’Eusebio**.

L'obiettivo del progetto è stato l’**identificazione e l’annotazione** delle entità, della struttura testuale e dei metadati contestuali, integrate da un **confronto quantitativo** tra i due testi **finalizzato a supportare un’analisi qualitativa**.

## Raccolta
I dati presi in esame sono relativi alla descrizione delle chiese della città di Roma nei primi anni del '900. Sono stati raccolti da [**Guide di Roma**](https://liveunibo-my.sharepoint.com/:f:/g/personal/sebastian_barzaghi2_unibo_it/EhinmY5b4h1Eoo-t2JOpaHwBHmr2BcGZK7YhwV9KUvTK2g?e=qizgrM) su [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw) e successivamenti estrapolati in zip e **scaricati in locale** in formato `.txt` e `.pdf`.

I dati scelti, riguardanti le **chiese di Santa Anastasia, Santa Balbina e Sant'Eusebio**, sono stati **salvati in locale** in formato `.xml` e `.csv` solo dopo le operazioni di:
* marcatura in TEI (su **https://vscode.dev/**);
* analisi tramite [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL);
* trascrizione e organizzazione dei dati analizzati da Voyant Tools su [Google Sheets](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://docs.google.com/spreadsheets/create%3Fhl%3Dit&ved=2ahUKEwifr4nRot6LAxXFWkEAHSEiFC4QFnoECAgQAQ&usg=AOvVaw15jA_GQBObUKkityhEJa1O).

La procedura di **creazione e strutturazione delle cartelle** si è basata sulla suddivisione in base alla tipologia di formato e tipologia di operazione sui dati.

> Durante tutta la fase di raccolta sono state effettuate delle copie di backup dei file e archiviate su [Google Drive](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://drive.google.com/drive/my-drive%3Fhl%3Dit&ved=2ahUKEwjhmdyo2OGLAxV2wAIHHYiKMP0QFnoECAgQAQ&usg=AOvVaw2GMTqVupizsilv2uqasqIg) e su un'unità flash. 

## Elaborazione e analisi

Il testo dei dati selezionati, precedentemente scaricato in locale in formato `.txt`, è stato caricato su **https://vscode.dev/** e marcato in TEI. 

L'operazione di marcatura si è focalizzata su:
* *persone/ animali/ organizzazioni/ entità* (nomi comuni e nomi propri, per questi ultimi l'identificatore univoco da [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) se disponibile);
* *luoghi* (nomi comuni e nomi propri);
* *eventi*;
* *date* (valore della data, tipologia di avvenimento storico);
* *numeri* (tipologia di valore numerico, valore numerico in formato standard, unità di misura);
* *lingua* (del contenuto dell'elemento marcato).

L'operazione di analisi testuale, supportata da [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL), si è concentrata invece sulle informazioni quantitative relative alla *quantità delle parole usate*, la *tipologia*, la *frequenza* e la *distribuzione nel testo*. La trascrizione, organizzazione e analisi dei dati quantitativi ottenuti è stata effettuata tramite un file di foglio di calcolo su [Google Sheets](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://docs.google.com/spreadsheets/create%3Fhl%3Dit&ved=2ahUKEwifr4nRot6LAxXFWkEAHSEiFC4QFnoECAgQAQ&usg=AOvVaw15jA_GQBObUKkityhEJa1O).

## Preservazione e condivisione
Nel rispetto e osservanza dei principi [**FAIR**](https://doi.org/10.1038/sdata.2016.18) (reversibilità, accessibilità, interoperabilità e riutilizzabilità), i dati sono stati archiviati:
* su [Github](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw), con la licenza [CC-BY 4.0 - Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/);
* su [Zotero](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.zotero.org/&ved=2ahUKEwiOkN-h2d-LAxUV-AIHHZHsGxoQFnoECAkQAQ&usg=AOvVaw3WB2zTrYFysjM4IeX43tLS), con il DOI (mettere DOI) .

## Conclusioni
I risultati che emergono in seguito alla marcatura in TEI e dal confronto quantitativo di Voyant Tools dei dati selezionati, evidenziano come i due testi forniscano delle **differenti prospettive** di analisi sulle chiese romane. Se **Diego Angeli** si distingue per un **approccio narrativo e descrittivo**, **A.D. Tani** offre invece un’**esposizione più dettagliata**, con **maggiore attenzione agli aspetti architettonici**.

L’analisi comparativa dei dati provenienti dai testi di Diego Angeli e A.D. Tani evidenzia due **approcci metodologici distinti ma complementari**.

* Angeli adotta un **modello narrativo e descrittivo**, con una scrittura lineare ed una particolare attenzione alla continuità storica. L’**organizzazione cronologica e l’inserimento di aneddoti** arricchiscono la trattazione, rendendola un riferimento pratico per una consultazione immediata e adatta ad un pubblico ampio;

* Tani dimostra un **approccio più analitico e sistematico**, con un linguaggio orientato alla **suddivisione tematica**, alla **descrizione strutturata degli elementi architettonici**, alle **fasi storico-costruttive** degli edifici e alla **citazione** delle più importanti **figure cardinalizie**.

L’**integrazione di entrambe le metodologie** consente di avere una **visione complessiva** del contesto storico e artistico degli edifici ecclesiastici romani, utile per uno studio e un'analisi incentrata sulla storia e sulle caratteristiche architettoniche/ artistiche di questi edifici sacri.

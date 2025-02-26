# CDR-TMLCA, progetto d'esame di DHDMCH (2024/2025) - Data Management Plan

## Autrice

* Alba d'Elia, https://orcid.org/my-orcid?orcid=0009-0009-3626-6779, Università di Bologna.

## Sommario esecutivo
* Raccolta dei dati da [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw): [**Guide di Roma**](https://liveunibo-my.sharepoint.com/:f:/g/personal/sebastian_barzaghi2_unibo_it/EhinmY5b4h1Eoo-t2JOpaHwBHmr2BcGZK7YhwV9KUvTK2g?e=qizgrM);
* Dati selezionati scaricati in locale in formato `.txt` e `.pdf`;
* Dati marcati in TEI tramite **https://vscode.dev/**;
* Salvataggio di una copia del documento in locale in formato `.xml`;
* Dati `.txt` caricati su [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL);
* Dati estrapolati ed organizzati in tabella in formato `.csv` .

## Introduzione
Progetto d'esame per il corso d'insegnamento in [DHDMCH](https://www.unibo.it/it/studiare/dottorati-master-specializzazioni-e-altra-formazione/insegnamenti/insegnamento/2024/502386) (a.a.2024/2025) incentrato sulla realizzazione  di un **progetto** sulla **gestione e analisi dei dati**, con la successiva pubblicazione su [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw).

## Descrizione dei dati
Dati provenienti dalla raccolta di [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw) in [**Guide di Roma**](https://liveunibo-my.sharepoint.com/:f:/g/personal/sebastian_barzaghi2_unibo_it/EhinmY5b4h1Eoo-t2JOpaHwBHmr2BcGZK7YhwV9KUvTK2g?e=qizgrM). Sono dunque stati scaricati in zip ed estrapolati in locale in formato `.txt` ed in `.pdf`.

Di questi sono stati selezionati i dati relativi alle descrizioni delle chiese di **Santa Anastasia**, **Santa Balbina** e **Sant’Eusebio**.

Si è dunque proceduto all'operazione di marcatura in TEI dei dati (tramite **https://vscode.dev/**) e al loro confronto quantitativo con [**Voyant Tools**](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://voyant-tools.org/&ved=2ahUKEwiuuJ_AmN6LAxVSRUEAHcN0KUoQFnoECAkQAQ&usg=AOvVaw0HuDnxSRVwxziirQgSd0xL). Produzione finale di dati in formato `.xml` e `.csv`.
> I dati prodotti da Voyant Tools sono stati selezionati, raccolti, trascritti, organizzati e analizzati in tabella tramite l'utilizzo dei foglio di calcolo di [Google Sheets](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://docs.google.com/spreadsheets/create%3Fhl%3Dit&ved=2ahUKEwifr4nRot6LAxXFWkEAHSEiFC4QFnoECAgQAQ&usg=AOvVaw15jA_GQBObUKkityhEJa1O), e quindi salvati locale in formato `.csv`.

* L'operazione di **marcatura** in TEI si è focalizzata su elementi quali:
  * *persone/ animali/ organizzazioni/ entità* (nomi comuni e nomi propri, per questi ultimi l'identificatore univoco da [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) se disponibile);
  * *luoghi* (nomi comuni e nomi propri);
  * *eventi*;
  * *date* (valore della data, tipologia di avvenimento storico);
  * *numeri* (tipologia di valore numerico, valore numerico in formato standard, unità di misura);
  * *lingua* (del contenuto dell'elemento marcato).

* L'operazione di **analisi testuale** con Voyant Tools si è focalizzata su **informazioni quantitative** relative alla **quantità delle parole usate, la frequenza e la tipologia**.

L'obiettivo dei dati prodotti è stato quello di **identificare e annotare** le entità, la struttura testuale e i metadati contestuali, integrando un **confronto quantitativo** tra i due testi a supporto di un’**analisi qualitativa**.
I dati prodotti possono rappresentare uno **strumento utile per studi e ricerche basati su un’analisi comparativa**, finalizzata all'**individuazione di somiglianze e differenze** tra i testi, insieme all'**estrazione di metadati rilevanti per la loro fruizione e contestualizzazione semantica**.

## Documentazione, qualità e condivisione dei dati:
Dati archiviati e resi accessibili su:
* [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw);
* [Zenodo](https://zenodo.org).

Il dataset pubblicato su Github e Zotero in è composto da 2 cartelle:
* `data`, contenente 2 sotto cartelle:
  *`tei`, contenente i due file presi ad esempio per la marcatura in TEI, in formato `.xml`;
  *`.txt`, contenente la scansione digitale delle due fonti delle [Guide di Roma](https://liveunibo-my.sharepoint.com/:f:/g/personal/sebastian_barzaghi2_unibo_it/EhinmY5b4h1Eoo-t2JOpaHwBHmr2BcGZK7YhwV9KUvTK2g?e=qizgrM), in formato `.txt`;
* `docs`, contenente il  `data-management-plan.md` e 2 sotto cartelle:
  *`tei`, con il progetto d'esame (marcato in TEI) in formato `.xml`;
  *`csv`,con la tabella dei dati comparativi e quantitativi in formato `.csv`.

## Requisiti legali ed etici
Dataset pubblicato su [GitHub](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://github.com/&ved=2ahUKEwinicGop96LAxXj0gIHHecADyoQFnoECAoQAQ&usg=AOvVaw38IHvcyBra8HGhmSxvlCGw), tramite la licenza [CC-BY 4.0 - Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/), e su [Zenodo](https://zenodo.org), con la conseguente associazione del DOI al momento della pubblicazione.

---
title: Crea e aggiorna i file di Microsoft Excel usando Python 
url: /it/python-java/create/
description: Crea report di fogli di lavoro Microsoft Excel senza installare Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crea report Excel usando Python" h2="Crea e aggiorna i fogli di calcolo di Microsoft Excel XLS, documenti XLSX all'interno di applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) è un'API Python per la creazione, la lettura e la scrittura di documenti nei formati Microsoft Excel, inclusi XLS e XLSX. Questa API fa parte del pacchetto [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/). Inoltre, Develpors può facilmente scrivere codice per inserire dati, immagini, grafici, tabelle pivot all'interno di fogli di lavoro e molte altre funzionalità. L'API Python supporta anche funzionalità come impostare varie [Formule](https://docs.aspose.com/cells/python-java/supported-formula-functions/), convertire il testo in colonne, marcatore intelligente e opzioni di formule dinamiche. Di seguito sono riportati alcuni codici di esempio per creare e modificare fogli di calcolo.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Come creare file Excel usando Python" %}}

L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) fornisce la classe Workbook che gestisce la creazione di file. Il processo è semplice. Crea l'oggetto classe Workbook e accedi al foglio di lavoro pertinente fornendo il suo indice. Utilizzare il metodo putValue per aggiungere il contenuto nella cella a cui si accede e infine chiamare il metodo save() per salvare il documento con un nome specifico.

{{% blocks/products/pf/feature-page-code h3="Codice 1: crea un file Excel semplice" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Codice 2 - Inserisci immagini all'interno di documenti Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Come aggiornare i file di Microsoft Excel usando Python" %}}

Il processo di creazione e aggiornamento del file Excel è quasi lo stesso tranne l'unica differenza. La differenza è che, durante il processo di creazione, viene creato l'oggetto cartella di lavoro vuota mentre durante il processo di aggiornamento è necessario un file Excel esistente. Quindi passa il file esistente come parametro alla classe Workbook. Riposa la procedura è la stessa

{{% blocks/products/pf/feature-page-code h3="Codice 3 - Aggiorna documenti Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
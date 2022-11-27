---
title: Aggiorna i file Excel usando Python 

description: Modifica documenti Microsoft Excel XLSX, XLS, CSV senza installare Microsoft Office all'interno delle applicazioni Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna documenti Excel tramite Python" h2="Modifica i file Microsoft Excel XLSX, XLS all'interno delle applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
È comune per le organizzazioni aggiornare i propri dati, archiviati in file excel come i dati degli studenti, i registri dei pazienti e l'elenco degli articoli di magazzino ecc. Tramite il software aziendale. L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) fornisce la funzionalità di modifica dei fogli di calcolo tramite il software. I programmatori possono migliorare il software con le capacità di modifica integrando l'API e scrivendo poche righe di codice. L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) che fa parte del pacchetto [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) semplifica questo processo di modifica. Di seguito è riportato il processo di aggiornamento del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiorna documenti Excel usando Python" %}}

L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) fornisce la classe Workbook che gestisce il caricamento dei fogli di calcolo Excel. Il processo è semplice. Creare l'oggetto classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) fornendo il file sorgente come parametro. Utilizzare il metodo [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) per accedere al foglio di lavoro pertinente fornendo il suo indice. chiama il metodo [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) per modificare il contenuto nella cella a cui si accede e infine invoca il metodo save() per salvare il documento.

{{% blocks/products/pf/feature-page-code h3="Python - Aggiorna documenti Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aggiornare">}}
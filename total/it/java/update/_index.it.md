---
title: Aggiorna i file Excel utilizzando Java 

description: Modifica documenti Microsoft Excel XLSX, XLS, CSV senza installare Microsoft Office all'interno di applicazioni basate su Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna documenti Excel tramite Java" h2="Modifica i file Microsoft Excel XLSX, XLS all'interno di applicazioni basate su Java senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
È comune per le organizzazioni aggiornare i propri dati, archiviati in file excel come i dati degli studenti, i registri dei pazienti e l'elenco degli articoli di magazzino ecc. Tramite il software aziendale. L'API [Aspose.Total for Java](https://products.aspose.com/total/java/) fornisce la funzionalità di modifica dei fogli di calcolo utilizzando il proprio software. I programmatori possono migliorare il software con le capacità di modifica semplicemente scrivendo poche righe di codice API. L'API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) che fa parte del pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/) semplifica questo processo di modifica. Di seguito è riportato il processo di aggiornamento del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiorna documenti Excel utilizzando Java" %}}

L'API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) fornisce la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) che gestisce il caricamento dei fogli di calcolo Excel. Il processo è semplice. Crea l'oggetto classe Workbook fornendo il file di origine come parametro. Accedi al foglio di lavoro pertinente e alla cella pertinente utilizzando il metodo [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Utilizzare il metodo [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) per modificare il contenuto nella cella a cui si accede e infine chiamare il metodo save() per salvare il documento.

{{% blocks/products/pf/feature-page-code h3="Codice Java - Aggiorna documenti Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aggiornare">}}
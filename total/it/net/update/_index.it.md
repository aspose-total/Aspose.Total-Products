---
title: Aggiorna i file Excel utilizzando .NET 

description: Modifica documenti Microsoft Excel XLSX, XLS, CSV senza installare Microsoft Office con applicazioni basate su C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna documenti Excel tramite .NET" h2="Modifica i file Microsoft Excel XLSX, XLS all'interno di applicazioni basate su .NET senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
È comune per le organizzazioni aggiornare i propri dati, archiviati in file excel come i dati degli studenti, i registri dei pazienti e l'elenco degli articoli di magazzino ecc. Tramite il software aziendale. L'API [Aspose.Total for .NET](https://products.aspose.com/total/net/) fornisce la funzionalità di modifica dei fogli di calcolo utilizzando il software. I programmatori possono migliorare il software con le capacità di modifica semplicemente scrivendo poche righe di codice API. L'API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) che fa parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net/) semplifica questo processo di modifica. Di seguito è riportato il processo di aggiornamento del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiorna documenti Excel utilizzando .NET" %}}

L'API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) fornisce la classe Workbook che gestisce il caricamento dei fogli di calcolo Excel. Il processo è semplice. Creare l'oggetto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) fornendo il file sorgente come parametro. Accedi al foglio di lavoro pertinente fornendo il suo indice utilizzando il metodo [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Utilizzare il metodo [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) per modificare il contenuto nella cella a cui si accede e infine chiamare il metodo save() per salvare il documento.

{{% blocks/products/pf/feature-page-code h3="Codice .NET - Aggiorna documenti Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aggiornare">}}
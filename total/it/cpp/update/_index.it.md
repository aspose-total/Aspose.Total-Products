---
title: Aggiorna i file Excel usando C++ 

description: Modifica documenti Microsoft Excel XLSX, XLS, CSV senza installare Microsoft Office con applicazioni basate su C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna documenti Excel tramite C++" h2="Modifica i file Microsoft Excel XLSX, XLS all'interno di applicazioni basate su C++ senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
È comune per le organizzazioni aggiornare i propri dati, archiviati in file excel come i dati degli studenti, i registri dei pazienti e l'elenco degli articoli di magazzino ecc. Tramite il software aziendale. L'API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fornisce la funzionalità di modifica dei fogli di calcolo utilizzando il software. I programmatori possono migliorare il software con le capacità di modifica semplicemente scrivendo poche righe di codice API. L'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) che fa parte del pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/) semplifica questo processo di modifica. Di seguito è riportato il processo di aggiornamento del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiorna documenti Excel usando C++" %}}

Utilizzando l'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), carica il documento di origine utilizzando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Accedi a [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) utilizzando GetIWorksheets()->GetObjectByIndex(0) e alla cella richiesta utilizzando GetICells()->GetObjectByIndex. Utilizzando il metodo PutValue, modificare il contenuto nella cella a cui si accede. Infine invocare il metodo save() per salvare il documento.

{{% blocks/products/pf/feature-page-code h3="Codice C++ - Aggiorna documenti Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aggiornare">}}
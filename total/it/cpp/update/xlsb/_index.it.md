---
title: Aggiorna il file XLSB usando C++
description: Modifica il documento XLSB nelle applicazioni C++ senza utilizzare Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna il file XLSB tramite C++" h2="Modifica i fogli di calcolo XLSB tramite le tue applicazioni basate su C++ senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per un programmatore, che sta tentando di aggiornare i file XLSB all'interno dell'applicazione C++, L'API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) può aiutare ad automatizzare il processo di aggiornamento. È un pacchetto completo di diverse librerie C++ che gestiscono più formati, inclusi i documenti di Microsoft Excel. L'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) che fa parte del pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/) semplifica questo processo di modifica. Il processo di aggiornamento del documento XLSB è semplice accedendo prima al foglio e quindi aggiornando il valore della cella in Excel utilizzando C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come aggiornare il file XLSB in C++" %}}

- Carica il file XLSB usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Accesso al [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) pertinente utilizzando GetIWorksheets()->GetObjectByIndex(0) e alla cella pertinente utilizzando GetICells()->GetObjectByIndex
- Inserisci nuovi dati nella cella a cui si accede utilizzando il metodo PutValue
- Salvare il file come file .xlsb utilizzando il metodo Save passando il file con il percorso come parametro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di modifica" %}}

- Per la modifica XLSB, seguendo [requisiti di sistema](https://docs.aspose.com/cells/cpp/system-requirements/) per sistemi Windows e Linux 
- Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp```
- Oppure tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```
- In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [Download](https://downloads.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice - Aggiorna il file XLSB in C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di modifica" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xls/" name="Aggiornare XLS File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xlsx/" name="Aggiornare XLSX File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/csv/" name="Aggiornare CSV File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xlsb/" name="Aggiornare XLSB File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xlsm/" name="Modificare XLSM File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xlt/" name="Aggiornare XLT File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xltx/" name="Aggiornare XLTX File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/xltm/" name="Aggiornare XLTM File" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/update/tsv/" name="Aggiornare TSV File" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
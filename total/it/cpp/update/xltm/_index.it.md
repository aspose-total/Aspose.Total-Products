---
title: Aggiorna il file XLTM usando C++
description: Modifica il documento XLTM nelle applicazioni C++ senza utilizzare Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna il file XLTM tramite C++" h2="Modifica i fogli di calcolo XLTM tramite le tue applicazioni basate su C++ senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per un programmatore, che sta tentando di aggiornare i file XLTM all'interno dell'applicazione C++, L'API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) può aiutare ad automatizzare il processo di aggiornamento. È un pacchetto completo di diverse librerie C++ che gestiscono più formati, inclusi i documenti di Microsoft Excel. L'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) che fa parte del pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/) semplifica questo processo di modifica. Il processo di aggiornamento del documento XLTM è semplice accedendo prima al foglio e quindi aggiornando il valore della cella in Excel utilizzando C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come aggiornare il file XLTM in C++" %}}

- Carica il file XLTM usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Accesso al [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) pertinente utilizzando GetIWorksheets()->GetObjectByIndex(0) e alla cella pertinente utilizzando GetICells()->GetObjectByIndex
- Inserisci nuovi dati nella cella a cui si accede utilizzando il metodo PutValue
- Salvare il file come file .xltm utilizzando il metodo Save passando il file con il percorso come parametro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di modifica" %}}

- Per la modifica XLTM, seguendo [requisiti di sistema](https://docs.aspose.com/cells/cpp/system-requirements/) per sistemi Windows e Linux 
- Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp```
- Oppure tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```
- In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [Download](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice - Aggiorna il file XLTM in C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
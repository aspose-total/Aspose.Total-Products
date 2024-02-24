---
title: Converti il formato DOCM in JSON tramite .NET
description: Converti DOCM in JSON in C# senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/net/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: ODS XLTM XLAM FODS DIF XLS XLSM TSV XLTX EXCEL XLSB SXC CSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOCM in formato JSON tramite C#" h2="Analizza DOCM in JSON tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire il formato DOCM in JSON all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi esportare DOCM in HTML. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti DOCM in formato JSON tramite C#" %}}
1. Aprire il file DOCM utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document
2. Converti DOCM in HTML utilizzando il metodo [Save](https://apiference.aspose.com/words/net/aspose.words.documentsave/methods/4)
3. Caricare il document HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salva il document in formato JSON utilizzando il metodo [Save](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti DOCM protetto in formato JSON tramite C#" %}}
Utilizzando l'API, puoi anche aprire il document protetto da password. Se il ddocumentDOCM di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il dodocumentrittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come provare ad aprire un docdocumentittografato con una password:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti DOCM in JSON nell'intervallo tramite C#" %}}
Durante la conversione di DOCM in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, ottenere CellsCollection del foglio di lavoro contenente i dati, creare un intervallo da CellsCollection specificando indici di riga e colonna e chiamare il metodo ExportRangeToJson con riferimenti agli oggetti Range & ExportRangeToJsonOptions. Infine, puoi salvare i dati JSON su file tramite il metodo File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Converti il formato DOTM in JSON tramite .NET
description: Converti DOTM in JSON in C# senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/net/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM SXC XLTM TSV DIF FODS XLSM XLSX ODS XLTX XLS EXCEL XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti DOTM in formato JSON tramite C#" h2="Analizza DOTM in JSON tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire il formato DOTM in JSON all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi esportare DOTM in HTML. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti DOTM in formato JSON tramite C#" %}}
1. Aprire il file DOTM utilizzando la classe [Dotmument](https://apiference.aspose.com/words/net/aspose.words/dotmument)
2. Converti DOTM in HTML utilizzando il metodo [Save](https://apiference.aspose.com/words/net/aspose.words.dotmument/save/methods/4)
3. Caricare il dotmumento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salva il dotmumento in formato JSON utilizzando il metodo [Save](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti DOTM protetto in formato JSON tramite C#" %}}
Utilizzando l'API, puoi anche aprire il dotmumento protetto da password. Se il dotmumento DOTM di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il dotmumento crittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come provare ad aprire un dotmumento crittografato con una password:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti DOTM in JSON nell'intervallo tramite C#" %}}
Durante la conversione di DOTM in JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, ottenere CellsCollection del foglio di lavoro contenente i dati, creare un intervallo da CellsCollection specificando indici di riga e colonna e chiamare il metodo ExportRangeToJson con riferimenti agli oggetti Range & ExportRangeToJsonOptions. Infine, puoi salvare i dati JSON su file tramite il metodo File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
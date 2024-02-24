---
title: Converti il formato POT in JSON tramite .NET
description: Converti POT in JSON in C# senza utilizzare Microsoft Excel o Powerpoint
url_ignore: /it/net/conversion/pot-to-json/
family: total
platformtag: net
feature: conversion
informat: POT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti POT in formato JSON tramite C#" h2="Esporta POT in JSON tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Excel o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire il formato POT in JSON all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi esportare POT in HTML. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi convertire HTML in JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti POT in formato JSON tramite C#" %}}
1. Aprire il file POT utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
2. Converti POT in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Caricare il documento HTML utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salva il documento in formato JSON utilizzando il metodo [Save](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti POT protetto in formato JSON tramite C#" %}}
Utilizzando l'API, puoi anche aprire il documento protetto da password. Se il documento POT di input è protetto da password, non è possibile convertirlo in formato JSON senza utilizzare la password. L'API consente di aprire il documento crittografato passando la password corretta in un oggetto LoadOptions. L'esempio di codice seguente mostra come aprire un documento crittografato con una password.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti POT in JSON nell'intervallo tramite C#" %}}
Durante la conversione da POT a JSON, puoi anche impostare l'intervallo sul formato JSON di output. Per impostare l'intervallo, è possibile aprire l'HTML convertito utilizzando la classe Workbook, ottenere CellsCollection del foglio di lavoro contenente i dati, creare un intervallo da CellsCollection specificando indici di riga e colonna e chiamare il metodo ExportRangeToJson con riferimenti agli oggetti Range & ExportRangeToJsonOptions. Infine, puoi salvare i dati JSON su file tramite il metodo File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
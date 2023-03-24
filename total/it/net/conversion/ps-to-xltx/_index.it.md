---
title: Converti PS in XLTX tramite API C#
description: API C# per convertire file PS in XLTX senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/net/conversion/ps-to-xltx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XLTX
otherformats: ODS XLAM TXT XLSM XLT MD XLTM XLSB EXCEL DIF SXC FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# per il rendering di PS in XLTX" h2="Esporta file PS in XLTX tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire facilmente file PS in XLTX all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare PS in XLSX. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), è possibile convertire XLSX in XLTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire PS in XLTX" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti PS in XLSX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salvare il documento in formato XLTX utilizzando il metodo [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) e impostare `Xltx` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti PS protetto in XLTX tramite C#" %}}
Se il tuo documento PS è protetto da password, non puoi convertirlo in XLTX senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza della classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e passare il nome file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti file PS in XLTX con filigrana tramite C#" %}}
Durante la conversione del file PS in XLTX, puoi anche aggiungere una filigrana al formato del file XLTX di output. Per aggiungere una filigrana, puoi creare un nuovo oggetto Cartella di lavoro e aprire il documento XLSX convertito, selezionare Foglio di lavoro tramite il suo indice, creare una forma e utilizzare la sua funzione AddTextEffect. Successivamente puoi salvare il tuo documento XLSX come XLTX con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
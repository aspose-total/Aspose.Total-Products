---
title: Converti XSLFO in FODS tramite API C#
description: API C# per convertire file XSLFO in FODS senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/net/conversion/xslfo-to-fods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: FODS
otherformats: XLAM XLTM DIF XLT ODS SXC EXCEL MD XLTX TXT TSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# per il rendering di XSLFO in FODS" h2="Esporta file XSLFO in FODS tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire facilmente file XSLFO in FODS all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare XSLFO in XLSX. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), è possibile convertire XLSX in FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire XSLFO in FODS" %}}
1. Aprire il file XSLFO utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti XSLFO in XLSX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salvare il documento in formato FODS utilizzando il metodo [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) e impostare `Fods` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti XSLFO protetto in FODS tramite C#" %}}
Se il tuo documento XSLFO è protetto da password, non puoi convertirlo in FODS senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza della classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e passare il nome file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti file XSLFO in FODS con filigrana tramite C#" %}}
Durante la conversione del file XSLFO in FODS, puoi anche aggiungere una filigrana al formato del file FODS di output. Per aggiungere una filigrana, puoi creare un nuovo oggetto Cartella di lavoro e aprire il documento XLSX convertito, selezionare Foglio di lavoro tramite il suo indice, creare una forma e utilizzare la sua funzione AddTextEffect. Successivamente puoi salvare il tuo documento XLSX come FODS con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-sxc/" name="XSLFO A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xltx/" name="XSLFO A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-md/" name="XSLFO A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-tsv/" name="XSLFO A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-txt/" name="XSLFO A TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-ods/" name="XSLFO A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xlt/" name="XSLFO A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xlsm/" name="XSLFO A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xlam/" name="XSLFO A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xltm/" name="XSLFO A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-dif/" name="XSLFO A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/xslfo-to-xlsb/" name="XSLFO A XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
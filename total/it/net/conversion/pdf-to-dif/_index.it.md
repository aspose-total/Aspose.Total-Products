---
title: Converti PDF in DIF tramite API C#
description: API C# per convertire file PDF in DIF senza utilizzare Microsoft Excel o Adobe Reader
url: /it/net/conversion/pdf-to-dif/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: DIF
otherformats: MD SXC ODS XLAM EXCEL TSV DIF TXT XLSB XLSM XLTM XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# per il rendering di PDF in DIF" h2="Esporta file PDF in DIF tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire facilmente file PDF in DIF all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare PDF in XLSX. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), è possibile convertire XLSX in DIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire PDF in DIF" %}}
1. Aprire il file PDF utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti PDF in XLSX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salvare il documento in formato DIF utilizzando il metodo [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) e impostare `Dif` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti PDF protetto in DIF tramite C#" %}}
Se il tuo documento PDF è protetto da password, non puoi convertirlo in DIF senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza della classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e passare il nome file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti file PDF in DIF con filigrana tramite C#" %}}
Durante la conversione del file PDF in DIF, puoi anche aggiungere una filigrana al formato del file DIF di output. Per aggiungere una filigrana, puoi creare un nuovo oggetto Cartella di lavoro e aprire il documento XLSX convertito, selezionare Foglio di lavoro tramite il suo indice, creare una forma e utilizzare la sua funzione AddTextEffect. Successivamente puoi salvare il tuo documento XLSX come DIF con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-sxc/" name="PDF A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xltx/" name="PDF A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-md/" name="PDF A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-tsv/" name="PDF A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-txt/" name="PDF A TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-ods/" name="PDF A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xlt/" name="PDF A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xlsm/" name="PDF A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xlam/" name="PDF A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xltm/" name="PDF A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-dif/" name="PDF A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-xlsb/" name="PDF A XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
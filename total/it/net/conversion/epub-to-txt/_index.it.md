---
title: Converti EPUB in TXT tramite API C#
description: API C# per convertire file EPUB in TXT senza utilizzare Microsoft Excel o Adobe Reader
url_ignore: /it/net/conversion/epub-to-txt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: TXT
otherformats: TSV XLSB FODS XLTM SXC XLAM DIF ODS TXT XLTX MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# per il rendering di EPUB in TXT" h2="Esporta file EPUB in TXT tramite C# senza utilizzare Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi convertire facilmente file EPUB in TXT all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare EPUB in XLSX. Successivamente, utilizzando l'API di programmazione per fogli di calcolo [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), è possibile convertire XLSX in TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire EPUB in TXT" %}}
1. Aprire il file EPUB utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti EPUB in XLSX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il documento XLSX utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
4. Salvare il documento in formato TXT utilizzando il metodo [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) e impostare `Txt` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti EPUB protetto in TXT tramite C#" %}}
Se il tuo documento EPUB è protetto da password, non puoi convertirlo in TXT senza la password. Usando l'API, puoi prima aprire il documento protetto usando una password valida e poi convertirlo. Per aprire il file crittografato, è possibile inizializzare una nuova istanza della classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e passare il nome file e la password come argomenti.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti file EPUB in TXT con filigrana tramite C#" %}}
Durante la conversione del file EPUB in TXT, puoi anche aggiungere una filigrana al formato del file TXT di output. Per aggiungere una filigrana, puoi creare un nuovo oggetto Cartella di lavoro e aprire il documento XLSX convertito, selezionare Foglio di lavoro tramite il suo indice, creare una forma e utilizzare la sua funzione AddTextEffect. Successivamente puoi salvare il tuo documento XLSX come TXT con Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
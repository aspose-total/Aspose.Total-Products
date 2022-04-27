---
title: API C# per esportare SVG in PCL
description: Converti SVG in PCL senza utilizzare Microsoft Word
url: /it/net/conversion/svg-to-pcl/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PCL
otherformats: DOTM OTT MHTML DOTX PCL MARKDOWN DOT FLATOPC WORDML ODT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da SVG a PCL tramite .NET" h2="API .NET per esportare SVG in PCL su Windows, macOS e Linux senza utilizzare Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) è una potente API per aggiungere funzionalità di conversione e manipolazione dei documenti all'interno dell'applicazione .NET. Utilizzando l'API di elaborazione PDF avanzata [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi convertire il formato file SVG in DOC. Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di DOC in PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire SVG in PCL" %}}
1. Aprire il file SVG utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti SVG in Doc utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file Doc utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document) di Aspose.Words
4. Salvare il documento in formato PCL utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Pcl come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrittografare il file SVG utilizzando la password del proprietario tramite .NET" %}}
Prima di convertire SVG in PCL, se vuoi decifrare il tuo documento puoi farlo usando l'API. Per decrittografare il file PDF, devi prima creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il SVG utilizzando la password del proprietario. Successivamente, è necessario chiamare il metodo [Decrypt](https://apiference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dell'oggetto Document. Infine, salva il file aggiornato utilizzando il metodo Save dell'oggetto Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file PCL di sola lettura tramite .NET" %}}
Per proteggere il tuo PCL dalla modifica e per impedire ad altre persone di modificare informazioni sensibili e riservate nel tuo documento, puoi anche impostare la protezione del documento utilizzando l'API. Puoi limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Questo può essere fatto utilizzando l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://apiference.aspose.com/words/net/aspose.words/protectiontype). È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-ott/" name="SVG A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-mhtml/" name="SVG A MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-wordml/" name="SVG A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-dot/" name="SVG A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-odt/" name="SVG A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-rtf/" name="SVG A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-ps/" name="SVG A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-flatopc/" name="SVG A FLAAPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-pcl/" name="SVG A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-markdown/" name="SVG A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-xamlflow/" name="SVG A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/svg-to-dotx/" name="SVG A DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
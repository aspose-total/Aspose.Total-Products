---
title: API C# per esportare MD in FLATOPC
description: Converti MD in FLATOPC senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/md-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: FLATOPC
otherformats: PS OTT WORDML MHTML PCL FLATOPC MARKDOWN DOT ODT DOTM RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da MD a FLATOPC tramite .NET" h2="API .NET per esportare MD in FLATOPC su Windows, macOS e Linux senza utilizzare Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) √® una potente API per aggiungere funzionalit√† di conversione e manipolazione dei documenti all'interno dell'applicazione .NET. Utilizzando l'API di elaborazione PDF avanzata [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi convertire il formato file MD in DOC. Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di DOC in FLATOPC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire MD in FLATOPC" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti MD in Doc utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file Doc utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document) di Aspose.Words
4. Salvare il documento in formato FLATOPC utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Flatopc come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.flatopc", SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrittografare il file MD utilizzando la password del proprietario tramite .NET" %}}
Prima di convertire MD in FLATOPC, se vuoi decifrare il tuo documento puoi farlo usando l'API. Per decrittografare il file PDF, devi prima creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il MD utilizzando la password del proprietario. Successivamente, √® necessario chiamare il metodo [Decrypt](https://apiference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dell'oggetto Document. Infine, salva il file aggiornato utilizzando il metodo Save dell'oggetto Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file FLATOPC di sola lettura tramite .NET" %}}
Per proteggere il tuo FLATOPC dalla modifica e per impedire ad altre persone di modificare informazioni sensibili e riservate nel tuo documento, puoi anche impostare la protezione del documento utilizzando l'API. Puoi limitare la possibilit√† di modificare un documento e consentire solo determinate azioni con esso. Questo pu√≤ essere fatto utilizzando l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://apiference.aspose.com/words/net/aspose.words/protectiontype). √ą possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.FlatOpc
document.Save("output.flatopc", SaveFormat.FlatOpc);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-ott/" name="MD A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-mhtml/" name="MD A MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-wordml/" name="MD A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-dot/" name="MD A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-odt/" name="MD A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-rtf/" name="MD A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-ps/" name="MD A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-flatopc/" name="MD A FLAAPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-pcl/" name="MD A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-markdown/" name="MD A MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-xamlflow/" name="MD A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-dotx/" name="MD A DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
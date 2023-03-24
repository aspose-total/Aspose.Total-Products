---
title: API C# per esportare TEX in RTF
description: Converti TEX in RTF senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/tex-to-rtf/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: RTF
otherformats: DOTM OTT MHTML ODT RTF PCL DOT FLATOPC DOTX PS WORDML MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da TEX a RTF tramite .NET" h2="API .NET per esportare TEX in RTF su Windows, macOS e Linux senza utilizzare Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) è una potente API per aggiungere funzionalità di conversione e manipolazione dei documenti all'interno dell'applicazione .NET. Utilizzando l'API di elaborazione PDF avanzata [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi convertire il formato file TEX in DOC. Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di DOC in RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire TEX in RTF" %}}
1. Aprire il file TEX utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti TEX in Doc utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file Doc utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document) di Aspose.Words
4. Salvare il documento in formato RTF utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Rtf come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.rtf", SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrittografare il file TEX utilizzando la password del proprietario tramite .NET" %}}
Prima di convertire TEX in RTF, se vuoi decifrare il tuo documento puoi farlo usando l'API. Per decrittografare il file PDF, devi prima creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il TEX utilizzando la password del proprietario. Successivamente, è necessario chiamare il metodo [Decrypt](https://apiference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dell'oggetto Document. Infine, salva il file aggiornato utilizzando il metodo Save dell'oggetto Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file RTF di sola lettura tramite .NET" %}}
Per proteggere il tuo RTF dalla modifica e per impedire ad altre persone di modificare informazioni sensibili e riservate nel tuo documento, puoi anche impostare la protezione del documento utilizzando l'API. Puoi limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Questo può essere fatto utilizzando l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://apiference.aspose.com/words/net/aspose.words/protectiontype). È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
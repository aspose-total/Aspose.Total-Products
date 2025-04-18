---
title: API C# per esportare CGM in DOTX
description: Converti CGM in DOTX senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/cgm-to-dotx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTX
otherformats: ODT RTF MHTML MARKDOWN DOTX PS WORDML DOTM XAMLFLOW OTT FLATOPC PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da CGM a DOTX tramite .NET" h2="API .NET per esportare CGM in DOTX su Windows, macOS e Linux senza utilizzare Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) è una potente API per aggiungere funzionalità di conversione e manipolazione dei documenti all'interno dell'applicazione .NET. Utilizzando l'API di elaborazione PDF avanzata [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi convertire il formato file CGM in DOC. Successivamente, utilizzando la potente API di elaborazione dei documenti [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di DOC in DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire CGM in DOTX" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti CGM in Doc utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file Doc utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document) di Aspose.Words
4. Salvare il documento in formato DOTX utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Dotx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrittografare il file CGM utilizzando la password del proprietario tramite .NET" %}}
Prima di convertire CGM in DOTX, se vuoi decifrare il tuo documento puoi farlo usando l'API. Per decrittografare il file PDF, devi prima creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il CGM utilizzando la password del proprietario. Successivamente, è necessario chiamare il metodo [Decrypt](https://apiference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) dell'oggetto Document. Infine, salva il file aggiornato utilizzando il metodo Save dell'oggetto Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file DOTX di sola lettura tramite .NET" %}}
Per proteggere il tuo DOTX dalla modifica e per impedire ad altre persone di modificare informazioni sensibili e riservate nel tuo documento, puoi anche impostare la protezione del documento utilizzando l'API. Puoi limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Questo può essere fatto utilizzando l'API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Consente di controllare il modo in cui si limita il contenuto utilizzando il parametro di enumerazione [ProtectionType](https://apiference.aspose.com/words/net/aspose.words/protectiontype). È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a DOTX mediante programación: casos de uso" %}}
Il file di metafile grafiche computer (CGM) può essere convertito in un formato DOTX (modello di documento macro-attivato della Microsoft Word) per ottimizzare la tua capacità di creazione e modifica dei documenti.

La conversione consente:

*   **Uso delle Case di studio:**
    *   **Rapporti aziendali e presentazioni**: Converte i file di metafile grafiche computer (CGM) per creare report aziendali interattivi, presentazioni e visualizzazioni visive per gli stakeholders, consentendo una migliore decision-making.
    *   **Materiali pubblicitari progettazione:** Utilizza DOTX per disegnare e configurare i materiali pubblicitari, come biglietti, volantini e fogli di vendita, con facilità.
    *   **Documentazione tecnica creazione**: Converte i file CGM per generare documentazione tecnica, inclusa le istruzioni per l'uso dei prodotti, manuali degli utenti e specifiche produttive.
    *   **Pubblicazioni scientifiche e ricerca:** Utilizza DOTX per creare e modificare documenti di ricerca scientifici, articoli e relazioni di ricerca, promuovendo la circolazione del sapere.
    *   **Materiali didattici sviluppo**: Converte i file CGM per disegnare materiali didattici interattivi, come tutorial, workbook e valutazione.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
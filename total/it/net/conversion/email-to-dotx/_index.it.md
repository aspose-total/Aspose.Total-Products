---
title: API C# per esportare EMAIL in DOTX
description: Converti EMAIL in DOTX senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/email-to-dotx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTX
otherformats: PDF DOCX GIF DOTX PCL PNG OTT SVG DOTM EMF RTF TIFF DOCM ODT EPUB PS FLATOPC XPS MD WORDML DOC JPEG TEXT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EMAIL in DOTX tramite .NET" h2="API .NET per il rendering di EMAIL su DOTX su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EMAIL a DOTX all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EMAIL in DOTX" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://apiference.aspose.com/email/net/aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato DOTX utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Dotx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EMAIL tramite .NET" %}}
Prima di convertire EMAIL in DOTX, se vuoi assicurarti di convertire l'email corretta, puoi caricare il documento EMAIL, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'email del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti DOTX tramite .NET" %}}
Durante il salvataggio del documento da EMAIL a DOTX, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a DOTX mediante programación: casos de uso" %}}
Utilizzare la codice di lingua Google per tradurre il testo in italiano:

Converting Emails to Microsoft Office Word Document (.docx) Files is Necessary to Unlock the Full Potential of Your Communication Capabilities. Questa conversione ti consente di:

**Casi d'uso:**

*   **Documentazione professionale**: Convertire email per creare documenti formalmente, rapporti e presentazioni per incontri aziendali, proposte o negoziazioni.
*   **Revisione e revisione dei contratti**: Utilizzare file Microsoft Office Word Document (.docx) per revisionare, modificare e firmare contratti, accordi e altri documenti vincolanti legalmente.
*   **Minuti delle riunioni e note**: Convertire email per creare minuti precisi e concisi delle riunioni, agenda e azioni da svolgere per la collaborazione del team.
*   **Scrittura di research paper e essay writing**: Utilizzare file Microsoft Office Word Document (.docx) per scrivere e impostare documenti di ricerca, saggio e articoli accademici con facilità.
*   **Letterhead aziendale e template di newsletter**: Convertire email per creare template letterari professionali, newsletter e altri materiali di marketing.

Utilizzare i file Microsoft Office Word Document (.docx) in conversione degli email offre numerosi vantaggi, tra cui:
*   Maggiore leggibilità e formattazione
*   Capacità di collaborazione e revisione migliorata
*   Miglioramento dell'organizzazione dei documenti e della ricerca
*   Maggiore professionalità e credibilità nella comunicazione
*   Condivisione facile e distribuzione dei documenti.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
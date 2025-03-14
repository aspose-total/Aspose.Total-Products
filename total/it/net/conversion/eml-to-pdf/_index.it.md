---
title: API C# per esportare EML in PDF
description: Converti EML in PDF senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOCX DOC SVG FLATOPC WORDML MD PNG TIFF DOTM DOT XPS TEXT EPUB DOCM JPEG GIF PS DOTX RTF PDF OTT EMF ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EML in PDF tramite .NET" h2="API .NET per il rendering di EML su PDF su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EML a PDF all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EML in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EML in PDF" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato PDF utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Pdf come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EML tramite .NET" %}}
Prima di convertire EML in PDF, se vuoi assicurarti di convertire l'eml corretta, puoi caricare il documento EML, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'eml del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti PDF tramite .NET" %}}
Durante il salvataggio del documento da EML a PDF, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a PDF mediante programación: casos de uso" %}}
Eml (Corrispondenza elettronica) sono utilizzati per archiviare messaggi testuali, rendendoli ideali per l'invio e la ricezione di e-mail. Tuttavia, quando si tratta di presentare documenti professionali con un aspetto accattivante, i pdf diventano essenziali per le richieste in stampa a richiesta, le firme digitali e l'archiviazione digitale.

La conversione degli eml in formati pdf è necessaria per sfruttare appieno il potenziale dei tuoi materiali stampati e delle capacità di accessibilità dei documenti. Questa conversione consente di:

**Casi d'uso:**

*   **Documenti professionali**: Convertire gli eml in pdf per creare documenti professionali che presentano un aspetto accattivante, utili per proposte, contratti e presentazioni.
*   **Firme digitali e archiviazione digitale**: Utilizzare il pdf per garantire le firme digitali e l'archiviazione di documenti sensibili, assicurando la conformità alle normative. Regolamentari ed aziendali
*   **Stampa a richiesta**: Convertire gli eml per produrre materiali stampati di alta qualità come brochure, volantini e cartelle di business, utilizzabili per campagne di marketing e eventi.
*   **Accessibilità e inclusione**: Utilizzare il pdf per rendere i documenti più accessibili alle persone con disabilita, convertendoli in formati testuali o scansionati.
*   **Distribuzione digitale e collaborazione**: Convertire gli eml per condividere documenti in modo sicuro attraverso posta elettronica o piattaforme di collaborazione online, migliorando le productività e riducendo i tempi di elaborazione.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
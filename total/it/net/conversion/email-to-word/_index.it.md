---
title: API C# per esportare EMAIL in WORD
description: Converti EMAIL in WORD senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/email-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: DOCM ODT TEXT PCL OTT DOCX PS FLATOPC EPUB XPS GIF WORD DOTX DOC DOTM MD WORDML PDF DOT JPEG PNG RTF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EMAIL in WORD tramite .NET" h2="API .NET per il rendering di EMAIL su WORD su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EMAIL a WORD all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EMAIL in WORD" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://apiference.aspose.com/email/net/aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato WORD utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Word come SaveFormat
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
Prima di convertire EMAIL in WORD, se vuoi assicurarti di convertire l'email corretta, puoi caricare il documento EMAIL, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'email del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti WORD tramite .NET" %}}
Durante il salvataggio del documento da EMAIL a WORD, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a WORD mediante programación: casos de uso" %}}
Utilizzando il codice linguistico di Google es:, la traduzione dell'articolo è la seguente:

Converting Emails in Word Documents: Unlocking the Full Potential of Your Communication Capabilità

Gli email sono ideali per archiviare messaggi brevi, rendendoli adatti alla corrispondenza quotidiana e all' comunicazione informale. Tuttavia, quando si tratta di creare documenti formalizzati e presentazioni, i documenti del Word diventano fondamentali per condividere informazioni complesse e idee.

La conversione del contenuto degli email nel formato di Word è necessaria per sbloccare al meglio le tue capacità di comunicazione. Questa conversione ti consente:

**Casi di utilizzo:**

*   **Rapporti aziendali**: Convertire gli email per creare rapporti professionali aziendali, mostrando aggiornamenti della società, dati finanziari e tendenze del mercato.
*   **Breve analisi politica e progetti**: Usare Word per sviluppare brevi analisi politiche, progetti e presentazioni formali per gli stakeholder e i clienti di decisione.
*   **Papers accademici e relazioni di ricerca**: Convertire gli email per produrre articoli accademici di alta qualità, relazioni di ricerca e recensioni della letteratura, garantendo accurate citazioni e riferimenti.
*   **Minuti dei congressi e degli ordini del giorno**: Usare Word per creare minuti formali del convegno, degli ordini del giorno e delle sintesi, favorendo una comunicazione efficace e un archivio fedele.
*   **Saggezze personali e articoli di blog**: Convertire gli email per costruire saggezze personali di qualità, articoli di blog e post, mettendo in mostra le tue abilità di scrittura e creatività.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
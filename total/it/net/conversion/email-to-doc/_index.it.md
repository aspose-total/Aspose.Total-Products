---
title: API C# per esportare EMAIL in DOC
description: Converti EMAIL in DOC senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EMAIL in DOC tramite .NET" h2="API .NET per il rendering di EMAIL su DOC su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EMAIL a DOC all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EMAIL in DOC" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://apiference.aspose.com/email/net/aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato DOC utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Doc come SaveFormat
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
Prima di convertire EMAIL in DOC, se vuoi assicurarti di convertire l'email corretta, puoi caricare il documento EMAIL, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'email del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti DOC tramite .NET" %}}
Durante il salvataggio del documento da EMAIL a DOC, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a DOC mediante programación: casos de uso" %}}
Il codice di linguaggio Google per l'inglese è "en-US". Utilizzando questo codice, la traduzione in italiano sarebbe "Converting Email Files into Microsoft Office Documents (DOC)

I file email vengono utilizzati ampiamente per la comunicazione, ma quando si tratta di condividere e analizzare dati, i documenti di Microsoft Office diventano essenziali. Convertingi i file email nel formato DOC si libera completamente il tuo potenziale nella creazione e nell'analisi dei documenti.

La conversione dei file email nel formato DOC è necessaria per librare completamente il tuo potenziale nella creazione e nell'analisi dei documenti. Questa conversione ti consente di:

**Casi d'uso:**

*   **Sottoposizione della Proposta di Progetto**: Convertire i file email per creare documenti di proposta di progetto concisi e professionali, evidenziando dettagli chiave e scadenze.
*   **Documentazione delle Riunioni**: Utilizzare DOC per organizzare le minuzie delle riunioni, gli action item e le decisioni prese durante la riunione.
*   **Rivisitazione e Analisi dei Contratti**: Convertire i file email per revisionare e analizzare i contratti, assicurandoti che tutti i termini e condizioni siano compresi in modo chiaro dalle due parti.
*   **Sottomissione delle Cartelle di Viaggio e Lettere di Presentazione**: Creare professionale carte di viaggio e lettere di presentazione utilizzando template DOC, personalizzando i tuoi materiali di applicazione in base alle aperture lavorative specifiche.
*   **Generazione dei Rapporti delle Conferenze**: Utilizzare DOC per generare i rapporti delle conferenze, riassunti delle presentazioni chiave, discussioni e risultati.

Convertendo i file email nel formato DOC, puoi gestire in modo efficiente le tue esigenze di creazione documentale."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
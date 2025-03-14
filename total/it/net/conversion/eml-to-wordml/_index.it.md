---
title: API C# per esportare EML in WORDML
description: Converti EML in WORDML senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORDML
otherformats: FLATOPC ODT RTF DOT WORDML DOTX PCL TIFF XPS SVG JPEG MD DOCM OTT DOC DOTM PNG DOCX EPUB EMF TEXT PS PDF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EML in WORDML tramite .NET" h2="API .NET per il rendering di EML su WORDML su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EML a WORDML all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EML in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EML in WORDML" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato WORDML utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Wordml come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EML tramite .NET" %}}
Prima di convertire EML in WORDML, se vuoi assicurarti di convertire l'eml corretta, puoi caricare il documento EML, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'eml del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti WORDML tramite .NET" %}}
Durante il salvataggio del documento da EML a WORDML, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a WORDML mediante programación: casos de uso" %}}
I'll translate the text into Italian using Google Translate:

Gli file di posta elettronica (EML) vengono utilizzati per archiviare messaggi di testo piani, rendendoli ideali per la comunicazione email semplice. Tuttavia, quando si lavora con dati basati su documenti, il WordML (Lingua di marcatura del Word) diventa essenziale per l'allestimento e lo stile.

La conversione dei file EML in formati WordML è necessaria per attivare le potenzialità complete della tua capacità di edizione e pubblicazione dei documenti. Questa conversione consente di:

**Case di utilizzo:**

*   **Edizione e pubblicazione dei documenti**: Convertire i file EML per editare e pubblicare i documenti, garantendo una costante formattazione e uno stile coerenti.
*   **Modelli email e curriculum**: Utilizzare WordML per creare modelli professionali di email e curriculum, evidenziando le tue abilità e l'esperienza.
*   **Generazione di report e pubblicazione**: Convertire i file EML per generare report e pubblicazioni, inclusi articoli, whitepaper e altri contenuti.
*   **Materiali di marketing e campagne**: Utilizzare WordML per creare materiali di marketing, come brochure, volantini e contenuti social media.
*   **Scrittore accademici e ricerche**: Convertire i file EML per formatare i lavori accademici e ricercativi, tesi e dissertazioni, garantendo una corretta citazione e riferimento.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
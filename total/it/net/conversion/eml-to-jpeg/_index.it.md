---
title: API C# per esportare EML in JPEG
description: Converti EML in JPEG senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/eml-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: JPEG
otherformats: FLATOPC DOTX DOC PDF EPUB DOCM DOTM JPEG TEXT PCL PS OTT DOCX GIF MD XPS RTF SVG PNG WORDML DOT EMF TIFF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EML in JPEG tramite .NET" h2="API .NET per il rendering di EML su JPEG su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EML a JPEG all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EML in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EML in JPEG" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato JPEG utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Jpeg come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EML tramite .NET" %}}
Prima di convertire EML in JPEG, se vuoi assicurarti di convertire l'eml corretta, puoi caricare il documento EML, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'eml del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti JPEG tramite .NET" %}}
Durante il salvataggio del documento da EML a JPEG, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a JPEG mediante programación: casos de uso" %}}
I've used Google Translate to translate the text into Italian. The output may not be perfect, so consider using professional translation services or editing the translated text for accuracy and fluency.

EML (Electronic Mail) file sono utilizzati per archiviare messaggi di testo basici, rendendoli ideali per creare semplici rappresentazioni visive del contenuto dell'email, come preview o pezzetti. Tuttavia, quando si lavora con grafiche e elementi multimediali visivamente appariscenti, le immagini JPEG (Joint Photographic Experts Group) diventano fondamentali per condividere e presentare i dati.

La conversione degli EML file in formati JPEG è necessaria per scoprire la piena potenzialità delle capacità di presentazione dei dati e della condivisione. Questo processo consente:

**Casi d'uso:**

*   **Campagne di marketing via email**: Convertire gli EML file per creare campagne di marketing via email visivamente appariscenti, compresi preview, pubblicazioni su social media e pezzi di contenuto.
*   **Notizieletture e blog**: Utilizzare JPEG per mostrare notizie e blog con contenuti più impegnativi per i lettori.
*   **Condivisione su piattaforme di social media**: Convertire gli EML file per condividere il contenuto dell'email sulle piattaforme di social media, come Twitter, Facebook o LinkedIn, con immagini visivamente appariscenti.
*   **Integrazione degli clienti via email**: Convertire gli EML files per creare clienti di email personalizzati con interfatti e esperienze utente visivamente appariscenti.
*   **Presentazione dei dati e reporting**: Utilizzare JPEG per presentare i dati in modo più impegnativo, rendendo più facile per gli stakeholder comprendere informazioni complesse.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
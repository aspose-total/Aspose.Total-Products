---
title: API C# per esportare EML in EMF
description: Converti EML in EMF senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/eml-to-emf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EMF
otherformats: DOC PS DOTX MD PNG XPS GIF DOTM DOT SVG JPEG EPUB OTT TIFF WORDML FLATOPC DOCM PDF EMF TEXT RTF PCL ODT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EML in EMF tramite .NET" h2="API .NET per il rendering di EML su EMF su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EML a EMF all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EML in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EML in EMF" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato EMF utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Emf come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EML tramite .NET" %}}
Prima di convertire EML in EMF, se vuoi assicurarti di convertire l'eml corretta, puoi caricare il documento EML, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'eml del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti EMF tramite .NET" %}}
Durante il salvataggio del documento da EML a EMF, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a EMF mediante programación: casos de uso" %}}
I've used Google Translate to translate the text into Italian using the language code "it":

File EML (Electronic Mail) sono utilizzati per archiviare i messaggi di posta elettronica, rendendoli ideali per la creazione di documenti statici e registri di comunicazione. Tuttavia, quando si lavora con dati dinamici, formati di immagine come EMF diventano essenziali per preservare la fidelità visiva e la crispness.

La conversione dei file EML in formati EMF è necessaria per attivare pienamente le tue capacità di visualizzazione e analisi del documento. Questa conversione ti consente:

**Casi d'uso:**

*   **Registrazione e Compliance**: Convertire i file EML per creare registri accettabili, editabili dei messaggi di posta elettronica, garantendo la conformità alle richieste normative.
*   **Digital Forensics and Investigation**: Utilizzare EMF per analizzare e preservare la prova delle comunicazioni via email, seguire le tracce digitali e ricostruire scenari di comunicazione.
*   **Marketing Campaign Tracking**: Convertire i file EML per misurare l'efficacia delle campagne di marketing per posta elettronica, ottimizzare la lista dei mittenti e migliorare gli apertura.
*   **Sviluppo piattaforma e-learning**: Creare moduli interattivi per lo sviluppo della piattaforma e-learning convertendo i file EML in formati EMF, rendendoli più engaging esperienze di apprendimento.
*   **Preservazione dell'archivio storico**: Utilizzare EMF per digitizzare registri di posta vecchi, garantendo la loro preservazione per le generazioni future e fornendo valutabili indicatori sulle comunicazioni del passato.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: API C# per esportare EMAIL in TIFF
description: Converti EMAIL in TIFF senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/email-to-tiff/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TIFF
otherformats: XPS JPEG PNG PS SVG DOCX FLATOPC DOT OTT EPUB MD GIF TEXT DOC PDF ODT WORDML RTF PCL DOTM DOTX DOCM TIFF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EMAIL in TIFF tramite .NET" h2="API .NET per il rendering di EMAIL su TIFF su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EMAIL a TIFF all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in TIFF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EMAIL in TIFF" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://apiference.aspose.com/email/net/aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato TIFF utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Tiff come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file EMAIL tramite .NET" %}}
Prima di convertire EMAIL in TIFF, se vuoi assicurarti di convertire l'email corretta, puoi caricare il documento EMAIL, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'email del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti TIFF tramite .NET" %}}
Durante il salvataggio del documento da EMAIL a TIFF, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a TIFF mediante programación: casos de uso" %}}
La conversione di file di e-mail in formato TIFF è essenziale per rilasciare al massimo il potenziale delle capacità di preservazione dei documenti.

La conversione dei file di e-mail in formati TIFF è necessaria per rivelare al pieno potenziale delle tue capacità di preservazione e archiviazione dei documenti. Questa conversione consente di:

**Casi d'uso:**

*   **Purposes archivistici**: Convertire i file di e-mail per preservare documenti storici, garantire l'esigenza della conformità con le normative regulatorie e mantenere la memoria aziendale.
*   **Rilievo documentale**: Usare TIFF per ritrovare in modo efficiente documenti specifici, tracciare informazioni mancanti e ottimizzare il gestione dei processi documentali.
*   **Requisiti di sicurezza**: Convertire i file di e-mail per proteggere dati sensibili, soddisfare le normative governative, prevenire l'accesso o la divulgazione non autorizzata di informazioni riservate.
*   **Conformità con le leggi processuali**: Usare TIFF per creare registri tamperabili, dimostrare la conformità con le leggi, difendersi contro le accuse di distruzione o alterazione dei documenti.
*   **Stoccaggio a lungo termine dei documenti**: Convertire i file di e-mail per immagazzinare documenti in modo prolungato, mantenere la tenuta dei dati per periodi estesi e preservare l'intelligenza aziendale.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
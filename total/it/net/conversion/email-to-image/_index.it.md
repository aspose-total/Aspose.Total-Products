---
title: API C# per esportare EMAIL in IMAGE
description: Converti EMAIL in IMAGE senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EMAIL in IMAGE tramite .NET" h2="API .NET per il rendering di EMAIL su IMAGE su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EMAIL a IMAGE all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EMAIL in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EMAIL in IMAGE" %}}
1. Aprire il file EMAIL utilizzando la classe [MailMessage](https://apiference.aspose.com/email/net/aspose.email/mailmessage)
2. Converti EMAIL in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato IMAGE utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Image come SaveFormat
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
Prima di convertire EMAIL in IMAGE, se vuoi assicurarti di convertire l'email corretta, puoi caricare il documento EMAIL, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'email del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti IMAGE tramite .NET" %}}
Durante il salvataggio del documento da EMAIL a IMAGE, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a IMAGE mediante programación: casos de uso" %}}
**Traduzione dell'articolo con codice di linguaggio Google**

E-mail sono un modo efficace per comunicare informazioni, ma presentano una carenza di attrazione visiva rispetto ad altri formati come le immagini. La conversione di e-mail in immagini è necessaria per sfruttare al massimo la potenzialità della narrazione visiva e preservare il contenuto per riferimenti futuri.

La conversione dei file di e-mail in formati di immagine è fondamentale:

**Casi d'uso:**

*   **Preservazione del contenuto**: Convertire le e-mail in immagini per catturare il contenuto, come ad esempio i note delle riunioni, gli accordi commerciali o i piani dei progetti, e renderli disponibili per eventuali riferimenti futuri.
*   **Protezione del marchio**: Utilizzare la conversione in immagini per preservare i elementi visivi del marchio aziendale, loghi e altri elementi visuali delle e-mail, garantendo la consistenza nei canali di comunicazione.
*   **Archiviazione digitale**: Convertire le e-mail in immagini per creare un archivio digitale dell' storia aziendale, compresi eventi importanti, traguardi e processi decisionali.
*   **Accessibilità e inclusione**: Convertire le e-mail in immagini per rendere il contenuto più accessibile agli utenti con disabilità visive o di altro tipo, utilizzando descrizioni alternative di testo per fornire contesto.
*   ** Sicurezza e conformità**: Utilizzare la conversione per proteggere informazioni sensibili dal rischio di accesso non autorizzato, soddisfacendo i requisiti normativi della protezione dei dati e della confidentiality.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
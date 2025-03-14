---
title: API C# per esportare EML in ODT
description: Converti EML in ODT senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/eml-to-odt/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: ODT
otherformats: DOCX TEXT PNG WORDML DOC ODT FLATOPC EMF DOCM DOTM PDF XPS RTF PCL MD JPEG DOT TIFF SVG OTT GIF DOTX PS EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta EML in ODT tramite .NET" h2="API .NET per il rendering di EML su ODT su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da EML a ODT all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file EML in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire EML in ODT" %}}
1. Aprire il file EML utilizzando la classe [MailMessage](https://apiference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converti EML in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato ODT utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Odt come SaveFormat
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
Prima di convertire EML in ODT, se vuoi assicurarti di convertire l'eml corretta, puoi caricare il documento EML, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'eml del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti ODT tramite .NET" %}}
Durante il salvataggio del documento da EML a ODT, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a ODT mediante programación: casos de uso" %}}
Iscrivere "EML (Electronic Mail) file" in italiano con codice di linguaggio di Google: "file EML (Corrispondenza elettronica)".

Gli file EML vengono utilizzati per archiviare il contenuto di testo della posta elettronica, rendendoli ideali per la creazione di email semplici e testuale. Tuttavia, quando si lavora con caratteristiche più avanzate del documentazione, i formati OpenDocument Text (.odt) diventano essenziali per l'editing e il formattaggio.

La conversione dei file EML in ODT è necessaria per riscoprire la piena potenzialità delle tue capacità di editing e formattazione del documento. Questa conversione consente di:

**Casi d'uso:**

*   **Editing del contenuto**: Converti i file EML per editare il contenuto, formatare testo e aggiungere elementi multimediali.
*   **Collaborazione su documenti**: Utilizza ODT per collaborare con gli altri in tempo reale, condividere documenti e tenere traccia delle modifiche.
*   **Creazione di template**: Converti i file EML per creare modelli personalizzabili per una branding costante e un messaggio coerente.
*   **Aumento della flessibilità**: Utilizza ODT per migliorare l'accessibilità dei documenti, aggiungendo elementi come la regolazione del font e i modi di contrasto elevati.
*   **Integrazione con altri strumenti**: Converti i file EML per integrarli con altri software ufficiali, come Google Docs o Microsoft Word, per un workflow senza sosta.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
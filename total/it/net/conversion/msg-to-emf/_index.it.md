---
title: API C# per esportare MSG in EMF
description: Converti MSG in EMF senza utilizzare Microsoft Word o Outlook su .NET
url_ignore: /it/net/conversion/msg-to-emf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EMF
otherformats: DOTX JPEG PCL OTT SVG PS ODT DOCX DOT DOCM EPUB XPS WORDML PNG MD TIFF TEXT DOC RTF EMF PDF FLATOPC DOTM GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Esporta MSG in EMF tramite .NET" h2="API .NET per il rendering di MSG su EMF su Windows, macOS e Linux senza utilizzare Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se sei uno sviluppatore .NET che cerca di aggiungere funzionalità di conversione da MSG a EMF all'interno delle tue applicazioni, le API di manipolazione del formato di file [Aspose.Total for .NET](https://products.aspose.com/total/net/) sono la strada giusta inoltrare. Utilizzando [Aspose.Email for .NET](https://products.aspose.com/email/net/), puoi convertire il formato del file MSG in HTML. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi eseguire il rendering di HTML in EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# per convertire MSG in EMF" %}}
1. Aprire il file MSG utilizzando la classe [MailMessage](https://apiference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Converti MSG in HTML utilizzando il metodo [Salva](https://apiference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Caricare HTML utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato EMF utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/4) e impostare Emf come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il file MSG tramite .NET" %}}
Prima di convertire MSG in EMF, se vuoi assicurarti di convertire l'msg corretta, puoi caricare il documento MSG, analizzarlo e dare un'occhiata alla proprietà desiderata. Utilizzando la classe [MapiMessage](https://apiference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) di [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, puoi ottenere informazioni su mittente e destinatario. Ad esempio, puoi verificare la presenza di un'msg del mittente specifica per la conversione utilizzando la proprietà [SenderName](https://apiference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Limita la modifica dei documenti EMF tramite .NET" %}}
Durante il salvataggio del documento da MSG a EMF, potrebbe essere necessario proteggere il documento di output. A volte potrebbe essere necessario limitare la possibilità di modificare un documento e consentire solo determinate azioni con esso. Ciò può essere utile per impedire ad altre persone di modificare informazioni riservate e riservate nel documento. L'API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ti consente di controllare il modo in cui limiti il contenuto utilizzando [ProtectionType](https://apiference.aspose. com/words/net/aspose.words/protectiontype) parametro di enumerazione. È possibile impostare il documento in sola lettura utilizzando le seguenti righe di codice. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MSG a EMF mediante programación: casos de uso" %}}
Convertendo file MSG in formati EMF è necessario per attivare la piena potenzialità delle tue capacità di editing immagini. Questa conversione consente a te:

**Casi d'uso:**

*   **Design grafico e illustrazione**: Convertire file MSG per creare grafici statici, illustrazioni e opere d'arte.
*   **Preservazione dell'arte digitale**: Utilizzare formati EMF per preservare l'arte digitale, garantire la compatibilità con software ereditati e mantenere l'integrità immagine.
*   **Disegno tecnico e CAD**: Convertire file MSG per supportare lo sviluppo di disegni tecnici, computer-aidato design (CAD) ed applicazioni ingegnerili.
*   **Cattura schermo e rasterizzazione**: Utilizzare formati EMF per catturare schermi, convertire grafici rasterizzati in formati vettore, migliorare la qualità della risoluzione dello schermo.
*   **Digital signage e advertising**: Convertire file MSG per creare segnalazioni digitali, materiali di pubblicità interattivi ed schermi dinamici.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
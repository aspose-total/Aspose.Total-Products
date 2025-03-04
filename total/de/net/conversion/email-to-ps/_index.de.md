---
title: C#-API zum Exportieren von E-MAIL nach PS
description: Konvertieren Sie E-MAIL in PS, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/email-to-ps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PS
otherformats: DOTM TIFF EMF DOCX MD PNG WORDML XPS DOCM RTF DOC PS PCL EPUB JPEG ODT OTT FLATOPC PDF SVG GIF DOTX TEXT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach PS" h2=".NET-API zum Rendern von E-MAIL in PS unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-PS-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMAIL-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in PS rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in PS" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMAIL in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im PS-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Ps als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.ps", SaveFormat.Ps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von EMAIL in PS sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMAIL-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von PS-Dokumenten über .NET" %}}
Beim Speichern des Document von EMAIL in PS müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-Dateien programmgesteuert in PS umwandeln: Anwendungsfälle" %}}
Wenn Sie mit dynamischen Daten arbeiten, sind PowerPoint-Presentationen (PS) eine entscheidende Komponente zur Begeisterung der Zuhörer und effektiven Kommunikation komplexer Informationen. Allerdings können PS-Dateien, wenn aus E-Mail-Anhängen erstellt werden, die ideale Dateiformat für das Vollpotential Ihrer Präsentationsfähigkeiten freimachen.

Diese Konversion ermöglicht Ihnen:

**Verwendungszwecke:**

*   **Unternehmenskommunikation**: PS-Dateien in E-Mail-Anhänge umwandeln, um ansprechende Unternehmenskommunikation wie Unternehmensergebnisse und Produktstart-ups zu erstellen.
*   **Event-Marketing**: PS verwenden, um Datenvisualisierung, RSVPs verfolgen und Kampagnenleistung messen, um die Gesamterfahrung für die Teilnehmer zu verbessern.
*   **Akademische Präsentationen**: E-Mail-Anhänge in PS-Dateien umwandeln, um informative und ansprechende Präsentationen für wissenschaftliche Konferenzen und Forschungsarbeiten erstellen zu können.
*   **Verkaufsförderung**: PS verwenden, um Verkaufsgehalt wie Produktvorstellungen und technische Überzüge zu liefern und Engagement-Indikatoren zu verfolgen, um die Verkaufsstrategien zu optimieren.
*   **Training und Einstellung**: E-Mail-Anhänge in PS-Dateien umwandeln, um interaktive Trainingseinheiten und Onboarding-Prozesse erstellen zu können, um Mitarbeiterwissenretention und Akzeptanz zu verbessern.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
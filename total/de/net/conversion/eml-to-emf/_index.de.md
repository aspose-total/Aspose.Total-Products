---
title: C#-API zum Exportieren von E-MAIL nach EMF
description: Konvertieren Sie E-MAIL in EMF, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/eml-to-emf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EMF
otherformats: DOC PS DOTX MD PNG XPS GIF DOTM DOT SVG JPEG EPUB OTT TIFF WORDML FLATOPC DOCM PDF EMF TEXT RTF PCL ODT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach EMF" h2=".NET-API zum Rendern von E-MAIL in EMF unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-EMF-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EML-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in EMF rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in EMF" %}}
1. Öffnen Sie die EML-Datei mit der Klasse [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Konvertieren Sie EML in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im EMF-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Emf als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
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

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von EML in EMF sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EML-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email/net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von EMF-Dokumenten über .NET" %}}
Beim Speichern des Document von EML in EMF müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML-Dateien programmgesteuert in EMF umwandeln: Anwendungsfälle" %}}
EML-Dateien werden verwendet, um E-Mail-Nachrichten zu speichern und sie ideal für die Erstellung von statischen Dokumenten und Kommunikationsprotokollen einzusetzen. Die Verwendung dynamischer Daten bedeutet jedoch, dass Bildformat wie EMF entscheidend sind, um visuelle Genauigkeit und Klarheit aufrechtzuerhalten.

Die Umwandlung von EML-Dateien in EMF-Format ist erforderlich, um die volle Leistungsfähigkeit deiner Dokumentvisualisierung und -analyse zu nutzen. Diese Umwandlung ermöglicht es dir:

*   **Rechts- und Verwaltungsvorgänge**: Die Umwandlung von EML-Dateien zur Erstellung von suchbaren, bearbeitbaren Protokollen für E-Mail-Kommunikation, um mit den Vorschriften zu compliance zu kommen.
*   **Digitale Forensik und Ermittlungen**: Mit EMF kannst du Analyse und Bewahrung von E-Mail-Eviden durchführen, Spuren digitaler Fußabdrücke verfolgen und Kommunikationszenarien wiederherstellen.
*   **Marketingkampagnen-Verfolgung**: Die Umwandlung von EML-Dateien zum Messen der Effektivität von E-Mail-Marketingkampagnen, die Optimierung von Absenderlisten und die Verbesserung der Öffnungsrate zu ermöglichen.
*   **E-Learning-Plattformen-Entwicklung**: Durch die Umwandlung von EML-Dateien in EMF-Format solltest du interaktive Lernmodule zur Erstellung von E-Learning-Modulen mit einer besseren Nutzererfahrung ermöglichen.
*   **Historische Archiv-Preservierung**: Mit EMF können alte E-Mail-Aufzeichnungen auf digitale Weise digitalisieren werden und somit für zukünftige Generationen erhalten und wertvolle Einblicke in vergangene Kommunikationsmuster bieten.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
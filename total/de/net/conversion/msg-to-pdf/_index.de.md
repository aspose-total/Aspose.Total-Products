---
title: C#-API zum Exportieren von E-MAIL nach PDF
description: Konvertieren Sie E-MAIL in PDF, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOT ODT WORDML JPEG PCL EMF TEXT RTF EPUB FLATOPC PDF SVG GIF OTT PS DOCX MD TIFF DOTM PNG DOCM XPS DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach PDF" h2=".NET-API zum Rendern von E-MAIL in PDF unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-PDF-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das MSG-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in PDF rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in PDF" %}}
1. Öffnen Sie die MSG-Datei mit der Klasse [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Konvertieren Sie MSG in HTML mit der Methode [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im PDF-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Pdf als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von MSG in PDF sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das MSG-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von PDF-Dokumenten über .NET" %}}
Beim Speichern des Document von MSG in PDF müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MSG-Dateien programmgesteuert in PDF umwandeln: Anwendungsfälle" %}}
Um das volle Potenzial deiner Dokumenten-Teilnahme und Analysemöglichkeiten zu nutzen, ist die Umwandlung von Nachrichten-Dateien (MSG) in Portable Document Format (PDF)-Dateien unerlässlich. Diese Umwandlung ermöglicht es dir:

**Verwendungsfälle:**

*   **Rechtsberichterstattung**: Konvertiere MSG-Dateien in PDFs zur Einhaltung von Rechtsvorschriften, um sicherzustellen, dass alle erforderlichen Dokumente korrekt und pünktlich eingereicht werden.
*   **Dokumentenbewahrung**: Verwende die Umwandlung in PDF, um historische Nachrichten und Aufzeichnungen zu erhalten, sie für zukünftige Bezugnahme oder Analyse zugänglich zu machen.
*   **Wahlüberprüfung**: Konvertiere MSG-Dateien in PDFs zur Wahlüberprüfungsprozesse, um die Integrität der Stimmverfahren und Ergebnisse zu gewährleisten.
*   **Urheberrechtsschutz**: Verwende die Umwandlung in PDF, um sensiblen Geschäftsinformationen durch die Konvertierung von geschützten Dokumenten einen unabhängigen Format zu bieten.
*   **Datenarchivverwaltung**: Konvertiere MSG-Dateien in PDFs zur Archiverhaltung und Speicherung historischer Daten, um sie für zukünftige Analyse oder Berichterstattung leicht zugänglich zu machen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
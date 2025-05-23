---
title: C#-API zum Exportieren von E-MAIL nach JPEG
description: Konvertieren Sie E-MAIL in JPEG, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach JPEG" h2=".NET-API zum Rendern von E-MAIL in JPEG unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-JPEG-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMAIL-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in JPEG rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in JPEG" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMAIL in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im JPEG-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Jpeg als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von EMAIL in JPEG sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMAIL-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von JPEG-Dokumenten über .NET" %}}
Beim Speichern des Document von EMAIL in JPEG müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-Dateien programmgesteuert in JPEG umwandeln: Anwendungsfälle" %}}
Converting Email Dateien in JPEG-Bilder ist eine Notwendigkeit um die visuelle Potenz zu freilegen

Email-Dateien mit wichtigen Kommunikationsdaten können effizient in JPEG-Bilder umgewandelt werden, was sie für statische visuelle Darstellung und Weitergabe ideal macht. Allerdings sind bei der Arbeit mit dynamischem Inhalt die sozialen Medienplattformen wie Instagram entscheidend zum visuellen Erzählen und Engagement.

Die Umwandlung von Email-Dateien in JPEG-Bilder ist erforderlich, um die volle Potenz deiner visuellen Inhalte und deinen Wert als Nachweisbarkeit zu entfalten. Diese Umwandlung ermöglicht es dir:

**Benutzerbeispiele:**

*   **Soziale Medien-Austausch**: Umwandele Email-Dateien in JPEG-Bilder, um einhaltende visuelle Inhalte bereitzustellen, die auf verschiedenen sozialen Medienplattformen geteilt werden können und somit eine breitere Zielgruppe erreichen.
*   **E-Commerce Produktvisualisierung**: Verwende JPEG-Bilder, um Produktinformationen, -spezifikationen und -merkmale darzustellen, die Online-Shopping-Erfahrungen zu verbessern.
*   ** Veranstaltungserlebnisse und Werbung**: Umwandele Email-Dateien in JPEG-Bilder, um Veranstaltungen, Produkte oder Dienstleistungen zu bewerben und Aufmerksamkeit gewinnen und Interesse wecken.
*   **Infografiken und Datenvisualisierung**: Nutze JPEG-Bilder, um Daten, Statistiken und Informationen visuell darzustellen und faszinierende Inhalte für verschiedene Zielgruppen erstellend.
*   **Digitale Marketingkampagnen**: Umwandele Email-Dateien in JPEG-Bilder zum Erstellen von ansprechenden visuellen Inhalten für Marketingkampagnen, Werbematerialien und Bewerbungen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: C#-API zum Exportieren von E-MAIL nach RTF
description: Konvertieren Sie E-MAIL in RTF, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/email-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: PS TIFF EPUB SVG WORDML OTT PNG JPEG XPS GIF MD EMF ODT TEXT DOTX PCL FLATOPC DOTM DOCM DOCX RTF DOT DOC PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach RTF" h2=".NET-API zum Rendern von E-MAIL in RTF unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-RTF-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMAIL-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in RTF rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in RTF" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMAIL in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im RTF-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Rtf als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von EMAIL in RTF sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMAIL-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von RTF-Dokumenten über .NET" %}}
Beim Speichern des Document von EMAIL in RTF müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-Dateien programmgesteuert in RTF umwandeln: Anwendungsfälle" %}}
**Umwandlung von E-Mail-Dateien in reiche Textdateiformate (RTF) Dateien**

E-Mail-Dateien sind dafür ausgelegt, textbasierte Inhalte zu speichern, was sie ideal für die Erstellung einfacher Nachrichten und Kommunikation macht. Allerdings werden RTF-Dateien bei der Formatierung und Anordnung unerlässlich, um professionelle Ansichten vorzulegen.

Die Umwandlung von E-Mail-Dateien in RTF-Formate ist erforderlich, um das volle Potenzial der visuellen Attraktivität und der Präsentationsmöglichkeiten Ihres Dokuments zu freilegen. Diese Umwandlung ermöglicht es Ihnen:

**Anwendungszwecke:**

*   **Professionelle Korrespondenz**: Verwenden Sie RTF-Dateien, um visuell ansprechende Briefe, Memoranden und formelle Kommunikationen erstellen zu können.
*   **Unternehmensberichterstattung**: Verwenden von RTF, um Berichte, Vorschläge und Präsentationen für Kunden, Stakeholder oder Management auf eine professionelle Weise vorzulegen.
*   **Marketingmaterialien**: Wandeln Sie E-Mail-Dateien in visuell ansprechende Newsletters, Broschüren und Marketingmaterialien um.
*   **Akademische Forschungsarbeiten**: Verwenden von RTF, um Forschungsarbeiten, Dissertations- oder Hochschulgradskursschriften mit präzisen Ausrichtung und Formatierung zu erstellen.
*   **Technische Dokumentation**: Wandeln Sie E-Mail-Dateien in Benutzerhandbücher, Anleitungsdokumente und technische Dokumentationen für Produkte oder Software um.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
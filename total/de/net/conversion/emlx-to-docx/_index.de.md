---
title: C#-API zum Exportieren von E-MAIL nach DOCX
description: Konvertieren Sie E-MAIL in DOCX, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/emlx-to-docx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: MD PDF SVG EMF WORDML DOT DOCX FLATOPC DOC ODT JPEG GIF PNG OTT RTF TEXT EPUB DOCM PCL PS DOTM TIFF DOTX XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach DOCX" h2=".NET-API zum Rendern von E-MAIL in DOCX unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-DOCX-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMLX-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in DOCX rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in DOCX" %}}
1. Öffnen Sie die EMLX-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMLX in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im DOCX-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Docx als SaveFormat fest
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
Wenn Sie vor der Konvertierung von EMLX in DOCX sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMLX-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von DOCX-Dokumenten über .NET" %}}
Beim Speichern des Document von EMLX in DOCX müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX-Dateien programmgesteuert in DOCX umwandeln: Anwendungsfälle" %}}
EMLX-Dateien werden verwendet, um textbasierte Informationen zu speichern, was sie ideal für die Erstellung einfacher E-Mail-Nachrichten und Newslettern macht. Allerdings sind bei der Arbeit mit dynamischer Daten Microsoft Word-Dokumente unverzichtbar für die Bearbeitung und Veröffentlichung von Inhalt.

Die Umwandlung von EMLX-Dateien in DocX-Format ist erforderlich, um den volollen Potenzial Ihrer Dokumentbearbeitungs- und -Veröffentlichungskapazitäten zu nutzen. Diese Umwandlung ermöglicht Ihnen:

**Anwendungsfälle:**

*   **Unternehmens-E-Mail-Vorlagen**: EMLX-Dateien konvertieren Sie, um personalisierbare Unternehmens-E-Mail-Vorlagen erstellen zu können und so Zeit sparen und Produktivität steigern.
*   **Newsletters und Pressemitteilungen**: Mit DocX bearbeiten und veröffentlichen Sie Newslettern, Pressemitteilungen und andere schriftliche Inhalte, um professionelles Layout und Formatierung sicherzustellen.
*   **Sitzungsminuten und Lebensläufe**: EMLX-Dateien in polished Sitzungsminuten und Lebensläufe konvertieren, um Ihre Fähigkeiten und Erfahrungen auf eine professionelle Weise zu präsentieren.
*   **Soziale Medien-Posts und Kommentare**: Mit DocX schreiben und bearbeiten Sie soziale Medien-Posts und Kommentare, die mit Ihren Publikumsgruppen effektiv kommuniziert werden können.
*   **Technische Schreibarbeit und Dokumentation**: EMLX-Dateien konvertieren Sie zu technischer Schreibarbeit und Dokumentation, um klare Anweisungen und Leitfäden für Nutzer und Kunden bereitzustellen."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
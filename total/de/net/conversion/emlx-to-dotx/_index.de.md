---
title: C#-API zum Exportieren von E-MAIL nach DOTX
description: Konvertieren Sie E-MAIL in DOTX, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/emlx-to-dotx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOTX
otherformats: OTT DOC PCL EMF DOTM MD DOCX XPS RTF PDF PNG TIFF DOCM DOTX ODT PS FLATOPC TEXT DOT GIF WORDML JPEG SVG EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach DOTX" h2=".NET-API zum Rendern von E-MAIL in DOTX unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-DOTX-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMLX-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in DOTX rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in DOTX" %}}
1. Öffnen Sie die EMLX-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMLX in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im DOTX-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Dotx als SaveFormat fest
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
Wenn Sie vor der Konvertierung von EMLX in DOTX sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMLX-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von DOTX-Dokumenten über .NET" %}}
Beim Speichern des Document von EMLX in DOTX müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX-Dateien programmgesteuert in DOTX umwandeln: Anwendungsfälle" %}}
EMXL-Dateien werden zur Speicherung von E-Mail-Nachrichteninformationen verwendet, was sie zum Erstellen von statischen E-Mails und Nachrichten macht. Allerdings sind bei der Verwendung dynamischer Daten wie beispielsweise Dokumente im Microsoft Word für die Erstellung von Dokumenten und die Zusammenarbeit unerlässlich.

Die Umwandlung von EMXL-Dateien in .docx-Format ist notwendig, um das volle Potenzial deiner Dokumenterstellungskapazitäten zu nutzen. Diese Umwandlung ermöglicht dir:

*   **Geschäftliche Kommunikation**: Konvertiere EMXL-Dateien, um professionelle Geschäftse-Mails, Berichte und Treffpunktnachweise erstellen zu können.
*   **Marketingkampagnematerialien**: Nutze Microsoft Word, um Marketingkampagnematerialien wie Broschüren, Flugscheine und Verkaufsblätter erstellen zu können.
*   **Projektmanagementsberichte**: Konvertiere EMXL-Dateien, um Projektmanagementberichte erstellen zu können, einschließlich Fortschrittsberichte, Aufgabenzuweisungen und Ressourcenzuweisungen.
*   **Wissenschaftliche und Forschungsarbeiten**: Nutze .docx-Format für die Schreibung, Bearbeitung und Zusammenarbeit von akademischen Papiern, Theses und Forschungsarbeiten.
*   **Zusammenarbeit bei der Dokumententwicklung**: Konvertiere EMXL-Dateien, um interaktive Zusammenarbitedokumente erstellen zu können, wodurch Teammitglieder in Echtzeit zusammenarbeiten können.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
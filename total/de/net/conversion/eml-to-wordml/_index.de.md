---
title: C#-API zum Exportieren von E-MAIL nach WORDML
description: Konvertieren Sie E-MAIL in WORDML, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORDML
otherformats: FLATOPC ODT RTF DOT WORDML DOTX PCL TIFF XPS SVG JPEG MD DOCM OTT DOC DOTM PNG DOCX EPUB EMF TEXT PS PDF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach WORDML" h2=".NET-API zum Rendern von E-MAIL in WORDML unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-WORDML-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EML-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in WORDML rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in WORDML" %}}
1. Öffnen Sie die EML-Datei mit der Klasse [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Konvertieren Sie EML in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im WORDML-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Wordml als SaveFormat fest
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
Wenn Sie vor der Konvertierung von EML in WORDML sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EML-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email/net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von WORDML-Dokumenten über .NET" %}}
Beim Speichern des Document von EML in WORDML müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML-Dateien programmgesteuert in WORDML umwandeln: Anwendungsfälle" %}}
E-Mail-Dateien (Electronic Mail) werden für die Speicherung von einfachen Textnachrichten verwendet, was sie ideal für einfache E-Mail-Kommunikation macht. Allerdings wird WordML (Word Markup Language) bei der Verarbeitung von Dokumentdaten zu einem unverzichtbaren Werkzeug für die Anpassung und Stilisierung.

Die Umwandlung von E-Mail-Dateien in WordML-Format ist erforderlich, um die volle Leistung Ihres Dokumentbearbeitungs- und Veröffentlichungsmanagements zu nutzen. Diese Umwandlung ermöglicht Ihnen:

**Anwendungszwecke:**

*   **Dokumentbearbeitung und -veröffentlichung**: Wandeln Sie E-Mail-Dateien in eine Möglichkeit, Dokumente abzuleiten und zu veröffentlichen, um ein konsistentes Format und Stil zu gewährleisten.
*   **E-Mail-Vorlagen und Lebensläufe**: Nutzen Sie WordML, um professionell aussehende E-Mail-Vorlagen und Lebensläufe zu erstellen, um Ihre Fähigkeiten und Erfahrungen unter Beweis zu stellen.
*   **Berichterstellung und Veröffentlichung**: Wandeln Sie E-Mail-Dateien in Berichte und Veröffentlichungen, einschließlich Artikeln, Whitepapers und weiteren Inhalten.
*   **Marketingkampagnenausstattungsmaterial**: Nutzen Sie WordML, um Marketingkampagnenausstattungsmaterial wie Broschüren, Flyer und soziale Medieninhalte zu erstellen.
*   **Akademische und wissenschaftliche Schreibarbeit**: Wandeln Sie E-Mail-Dateien in die Formatierung akademischer und wissenschaftlicher Aufsätze, Dissertationen und Doktorthesen, um angemessene Zitierungen und Beziehungen sicherzustellen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
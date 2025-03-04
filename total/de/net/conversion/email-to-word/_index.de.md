---
title: C#-API zum Exportieren von E-MAIL nach WORD
description: Konvertieren Sie E-MAIL in WORD, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/email-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: DOCM ODT TEXT PCL OTT DOCX PS FLATOPC EPUB XPS GIF WORD DOTX DOC DOTM MD WORDML PDF DOT JPEG PNG RTF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach WORD" h2=".NET-API zum Rendern von E-MAIL in WORD unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-WORD-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMAIL-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in WORD rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in WORD" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMAIL in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im WORD-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Word als SaveFormat fest
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
Wenn Sie vor der Konvertierung von EMAIL in WORD sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMAIL-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von WORD-Dokumenten über .NET" %}}
Beim Speichern des Document von EMAIL in WORD müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-Dateien programmgesteuert in WORD umwandeln: Anwendungsfälle" %}}
Um das Potenzial vollständig zu entfalten, können E-Mails in Word-Dokumente umgewandelt werden. E-Mails eignen sich hervorragend für die Aufnahme kurzer Nachrichten und sind daher für den alltäglichen Briefwechsel und die informelle Kommunikation ideal.

Bei der Erstellung von formalen Dokumenten und Präsentationen jedoch sind Word-Dokumente unverzichtbar. Sie ermöglichen es, komplexe Informationen und Ideen effektiv zu vermitteln.

Die Umwandlung des Inhalts von E-Mails in Word-Format ist notwendig, um das volle Potenzial deiner Kommunikationsfähigkeiten freizusetzen. Diese Umwandlung ermöglicht dir:

**Benutzerbeispiele:**

*   **Unternehmensberichte**: Mache E-Mails zu den Grundlagen für professionelle Unternehmensberichte, die Aktualisierungen, Finanzdaten und Marktdevelopments präsentieren können.
*   **Politische Briefe und Vorschläge**: Nutze Word, um formelle politische Briefe, Vorschläge und Präsentationen für Entscheidungsträger, Stakeholder und Kunden zu entwickeln.
*   **Akademische Schriften und Forschungsberichte**: Mache E-Mails zu hochwertigen akademischen Schriften, Forschungsberichten und Literaturreihen, um korrekte Zitation und Referenzierung gewährleisten zu können.
*   **Sitzungsminuten und Anlagen**: Nutze Word zur Erstellung von formellen Sitzungsminuten, Anlagen und Zusammenfassungen, um effektives Kommunikationsverhalten zu unterstützen und Aufzeichnungen zu führen.
*   **Persönliche Essays und Blogbeiträge**: Mache E-Mails zu inspirierenden persönlichen Essays, Blogbeiträgen und Artikeln, um deine Schreibfähigkeiten und Kreativität unter Beweis stellen zu können.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
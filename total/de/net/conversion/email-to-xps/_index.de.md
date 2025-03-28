---
title: C#-API zum Exportieren von E-MAIL nach XPS
description: Konvertieren Sie E-MAIL in XPS, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/email-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: ODT DOTM DOCX PDF JPEG TEXT DOCM WORDML RTF PS PNG TIFF DOTX EMF XPS GIF MD DOC OTT DOT SVG PCL EPUB FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach XPS" h2=".NET-API zum Rendern von E-MAIL in XPS unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-XPS-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMAIL-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in XPS rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in XPS" %}}
1. Öffnen Sie die EMAIL-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMAIL in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im XPS-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Xps als SaveFormat fest
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
Wenn Sie vor der Konvertierung von EMAIL in XPS sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMAIL-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von XPS-Dokumenten über .NET" %}}
Beim Speichern des Document von EMAIL in XPS müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL-Dateien programmgesteuert in XPS umwandeln: Anwendungsfälle" %}}
Um den folgenden Text zu übersetzen:

"Konvertieren von E-Mails in XPS-Dateien: Entdecken Sie die Potenz des visuellen Inhalts.

E-Mails sind ein entscheidender Werkzeug für die Kommunikation, aber wenn es um visuelle Inhalte geht, fallen sie oft aufs Knöpchen. Im Gegensatz zu anderen Format wie PDF oder XPS, die die ursprünglichen Grafiken und Layouterhalten, können E-Mails das Bildqualität und die Formatierung beim Versand kompromittieren.

Das ist, wo sich Konvertierung ins Spiel bringt. Konvertieren Sie E-Mails in XPS-Dateien, um zu:

**Anwendungsbereiche:**

*   **Visuelle Inhalte-Sicherung**: Konvertieren Sie E-Mails in XPS-Dateien, um sicherzustellen, dass Ihr visueller Inhalt im Umlauf bleibt, auch wenn er geteilt oder archiviert wird.
*   **Druckfreundliche Kommunikationen**: Nutzen Sie XPS-Dateien, um Druckfreundliche Versionen Ihrer E-Mails zu erstellen, perfekt für Präsentationen, Berichte und andere formelle Kommunikationsformen.
*   **Sicherheit und Einhaltung**: Konvertieren Sie E-Mails in XPS-Dateien, um Vorschriften erfüllen und sensiblen visuellen Inhalt sicherstellen.
*   **Archivierung und Aufbewahrung**: Speichern Sie XPS-Dateien, um E-Mail-Anhänge und Bilder für zukünftige Überprüfung oder Einhaltungswürdigkeit zu bewahren.
*   **Zugänglichkeit und Eingliederung**: Konvertieren Sie E-Mails in XPS-Dateien, um Zugänglichkeit verbessern zu können, indem eine alternative Formatierung für Benutzer mit visuellem Behinderungsgrad bereitgestellt wird.

Durch die Konvertierung Ihrer E-Mails in XPS-Dateien können Sie das volle Potenzial Ihres visuellen Inhalts freilegen und sicherstellen, dass es weiterhin lebendig bleibt."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
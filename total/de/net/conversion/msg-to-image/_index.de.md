---
title: C#-API zum Exportieren von E-MAIL nach IMAGE
description: Konvertieren Sie E-MAIL in IMAGE, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/msg-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: IMAGE
otherformats: XPS MD PNG DOT EPUB DOCM JPEG GIF ODT PCL DOCX WORDML DOTX TEXT DOC FLATOPC EMF PS TIFF IMAGE RTF PDF SVG OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach IMAGE" h2=".NET-API zum Rendern von E-MAIL in IMAGE unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-IMAGE-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das MSG-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in IMAGE rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in IMAGE" %}}
1. Öffnen Sie die MSG-Datei mit der Klasse [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Konvertieren Sie MSG in HTML mit der Methode [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im IMAGE-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Image als SaveFormat fest
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
Wenn Sie vor der Konvertierung von MSG in IMAGE sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das MSG-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von IMAGE-Dokumenten über .NET" %}}
Beim Speichern des Document von MSG in IMAGE müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MSG-Dateien programmgesteuert in IMAGE umwandeln: Anwendungsfälle" %}}
Bereitschaftsdateien (Bereitungsdateien) werden verwendet, um einfache Textnachrichten zu speichern und dadurch ideal für den Erhalt und die Übertragung von einfachen Nachrichten. Allerdings erwärmt man sich bei der Arbeit mit visuellem Inhalt durch die Verwendung von Bildern, die unverzichtbar zur Kommunikation komplexer Ideen und Emotionen werden.

Die Umwandlung von Bereitschaftsdateien in Bildformat ist notwendig, um das volle Potenzial deiner visuellen Kommunikation und Präsentationsmöglichkeiten zu freilegen. Diese Umwandlung ermöglicht dir:

**Anwendungszwecke:**

*   **Soziale Medien-Beiträge**: Wandele Bereitschaftsdateien in Beiträge um, indem du sie mit Bildern verschickst, um eine Botschaft zu vermitteln und Aufmerksamkeit zu gewinnen.
*   **E-Mail-Marketingkampagnen**: Verwende die Bildumwandlung, um visuelle Elemente in E-Mail-Kampagnen einzufügen, sodass sie effektiver ist, den Leser zu fesseln und Engagement zu fördern.
*   **Text-zu-Sprechpräsentationen**: Wandele Bereitschaftsdateien in interaktive Präsentationen um, die eine Text-zu-Sprecherfunktion aufweisen, sodass man sich mit Händen frei bewegen kann und Betonung auf Schlüsselbotschaften legen kann.
*   **virtuelle Hilfsassistenten und Chatbots**: Verwende die Bildumwandlung, um visuelle Hinweise für Interaktionen in virtuellen Assistenten zu fügen, sodass der Benutzererlebnis verbessert wird und Antwortzeiten beschleunigt werden.
*   **E-Learning-Inhalte erstellen**: Wandele Bereitschaftsdateien in interaktive E-Learning-Inhalte um, die Bilder beinhalten, um komplexe Konzepte zu illustrieren und Lernenden angesprochen zu werden.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
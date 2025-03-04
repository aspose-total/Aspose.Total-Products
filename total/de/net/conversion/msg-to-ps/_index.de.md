---
title: C#-API zum Exportieren von E-MAIL nach PS
description: Konvertieren Sie E-MAIL in PS, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/msg-to-ps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PS
otherformats: DOT SVG PS TIFF DOCX TEXT RTF ODT DOTM DOCM EPUB PNG EMF GIF PDF DOTX DOC WORDML FLATOPC OTT MD PCL XPS JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach PS" h2=".NET-API zum Rendern von E-MAIL in PS unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-PS-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das MSG-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in PS rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in PS" %}}
1. Öffnen Sie die MSG-Datei mit der Klasse [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Konvertieren Sie MSG in HTML mit der Methode [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im PS-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Ps als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.ps", SaveFormat.Ps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von MSG in PS sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das MSG-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von PS-Dokumenten über .NET" %}}
Beim Speichern des Document von MSG in PS müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MSG-Dateien programmgesteuert in PS umwandeln: Anwendungsfälle" %}}
Betreff: Verwendung von MSG-Dateien zur Speicherung von Textinformationen

MSG-Dateien werden für die Speicherung von Textbasiseinhalten verwendet und sind daher ideal für die Erstellung einfacher Textnachrichten und E-Mails. Allerdings werden bei der Arbeit mit Multimedia-Daten PDF-Formaten entscheidend, um visuell ansprechende Dokumente zu liefern.

Die Umwandlung von MSG-Dateien in PDF-Format ist notwendig, um die volle Leistung deiner Dokumentübertragungsfähigkeiten zu nutzen. Diese Umwandlung ermöglicht es dir:

*   **E-Commerce-Bestätigungen**: MSG-Dateien in professionelle Bestätigungen umwandeln, die Produktinformationen und Lieferdaten enthalten.
*   **Medizinische Aktenauszugs**: PDF für sichere und komplizite Datenaustausch zu verwenden, sensiblen medizinischen Daten mitzu teilen.
*   **Eventinvitationsdesign**: MSG-Dateien in ansprechende Eventinvitations umwandeln, die RSVP Informationen und Unterkunftsdetail enthalten.
*   **Technische Manuale Verteilung**: PDF zum Verteilen von technischen Manuellen verwenden, damit Kunden oder Endnutzer für sich Lesen leicht zu lesen Dokumente bereit stellen.
*   **Newsletter Veröffentlichung**: MSG-Dateien in visuell ansprechende Newslettern umwandeln, bei denen Unternehmen-Nachrichten, Promotion und Branchenews berichtsführen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
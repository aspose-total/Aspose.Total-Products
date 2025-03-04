---
title: C#-API zum Exportieren von E-MAIL nach MD
description: Konvertieren Sie E-MAIL in MD, ohne Microsoft Word oder Outlook auf .NET zu verwenden
url_ignore: /de/net/conversion/emlx-to-md/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: MD
otherformats: PDF OTT PCL JPEG RTF GIF DOC DOCX EMF EPUB TIFF DOTM TEXT DOT SVG ODT XPS PS WORDML DOTX PNG MD DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportieren Sie E-MAIL über .NET nach MD" h2=".NET-API zum Rendern von E-MAIL in MD unter Windows, macOS und Linux, ohne Word oder Outlook zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Wenn Sie ein .NET-Entwickler sind, der E-MAIL-zu-MD-Konvertierungsfunktionen in Ihren Anwendungen hinzufügen möchte, sind [Aspose.Total for .NET](https://products.aspose.com/total/net/)-APIs zur Dateiformatmanipulation der richtige Weg nach vorne. Durch die Verwendung von [Aspose.Email for .NET](https://products.aspose.com/email/net/) können Sie das EMLX-Dateiformat in HTML konvertieren. Danach können Sie mit [Aspose.Words for .NET](https://products.aspose.com/words/net/) HTML in MD rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von E-MAIL in MD" %}}
1. Öffnen Sie die EMLX-Datei mit der Klasse [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Konvertieren Sie EMLX in HTML mit der Methode [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Laden Sie HTML mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Speichern Sie das Dokument im MD-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Md als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über .NET" %}}
Wenn Sie vor der Konvertierung von EMLX in MD sicherstellen möchten, dass Sie die richtige E-Mail konvertieren, können Sie das EMLX-Dokument laden, analysieren und sich die gewünschte Eigenschaft ansehen. Durch die Verwendung der Klasse [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) von [Aspose.Email for .NET](https://products.aspose.com/email /net/) API können Sie Absender- und Empfängerinformationen abrufen. Beispielsweise können Sie mithilfe der Eigenschaft [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) nach einer bestimmten Absender-E-Mail-Adresse für die Konvertierung suchen.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von MD-Dokumenten über .NET" %}}
Beim Speichern des Document von EMLX in MD müssen Sie möglicherweise Ihr Ausgabedokument schützen. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann nützlich sein, um zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, ermöglicht es Ihnen, die Art und Weise zu steuern, wie Sie den Inhalt mit [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) Enumerationsparameter. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX-Dateien programmgesteuert in MD umwandeln: Anwendungsfälle" %}}
EMLX-Dateien werden zur Speicherung von Text-E-Mails mit Formatinformationen verwendet, sodass sie für die Erstellung einfacher E-Mail-Vorlagen und -Kompositionen ideal sind. Die Verwendung von strukturierter Daten und visuellen Darstellungen erfordert jedoch Markdown-Dateien für eine präzise Darstellung und Analyse.

Die Umwandlung von EMLX-Dateien in Markdown-Format ist erforderlich, um die volle Potenz deines Datavisualisierungskapazitäten zu nutzen. Diese Umwandlung ermöglicht es dir:

**Verwendungszwecke:**

*   **Projekt Dokumentation**: Wandele EMLX-Dateien in ein lesbares Projekt-Dokument, übersichtliche Änderungen verfolgen und mit Teammitgliedern zusammenarbeiten.
*   **Sitzungsnotizen und Beschlüsse**: Nutze Markdown, um während Sitzungen Notizen zu fügen, Minuten festzuhalten und diese an Teilnehmer weiterzugeben.
*   **Persönliche Tagebuchhaltung**: Wandele EMLX-Dateien in ein persönliches Tagebuch oder Tagebuch, um Gedanken, Erfahrungen und Reflexionen strukturiert zu dokumentieren.
*   **Wissenschaftlicher Schreibprozess**: Nutze Markdown für die Erstellung und Organisation von Forschungsartikeln, Artikeln und Essays, um Lesbarkeit und Zusammenarbeit zu verbessern.
*   **Kenntnisbasen erstellen**: Wandele EMLX-Dateien in eine Kenntnissuche, Dokumentation von Prozessen, Verfahren und Standards in einem leicht nachvollziehbaren und zugänglichen Format.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
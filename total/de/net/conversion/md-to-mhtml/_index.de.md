---
title: C#-API zum Exportieren von MD nach MHTML
description: Konvertieren Sie MD in MHTML, ohne Microsoft Word zu verwenden
url_ignore: /de/net/conversion/md-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: MHTML
otherformats: PCL RTF MHTML WORDML OTT DOTM PS ODT DOT MARKDOWN DOTX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie MD über .NET in MHTML" h2=".NET-API zum Exportieren von MD nach MHTML unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET](https://products.aspose.com/pdf/net/) können Sie das MD-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in MHTML rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von MD in MHTML" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie MD mit der Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im MHTML-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Mhtml als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die MD-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von MD in MHTML entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das MD mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly MHTML-Datei über .NET erstellen" %}}
Um Ihr MHTML vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Document auch über die API festlegen. Sie können die Bearbeitung eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="MD-Dateien programmgesteuert in MHTML umwandeln: Anwendungsfälle" %}}
Die Konvertierung von Markdown-Dateien (MD) in MHTML-Format ist notwendig, um die volle Potenz deiner Webinhaltsvisualisierungs- und Analysefähigkeiten freizusetzen. Diese Konversionsmöglichkeit ermöglicht es dir:

**Verwendungskasen:**

*   **Webinhaltsoptimierung**: MD-Dateien konvertieren, um optimierten Webinhalt zu erstellen, schneller Beladungszeiten und eine verbesserte Nutzererfahrung zu gewährleisten.
*   **E-Book-Erstellung**: Mit MHTML kannst du interaktive E-Books erstellen, Layout und Formatierung beibehalten und die Leserengagement erhöhen.
*   **Stilmanagements**: MD-Dateien konvertieren, um Stilgudemanagement zu ermöglichen, Konsistenz in den Dokumenten sichern und Inhaltsverfassen streamline.
*   **Benutzerhandbuchentwicklung**: MHTML nutzt, um interaktive Benutzerhandbücher zu erstellen, Schritt-für-Schritt-Anleitungen bereitzustellen und Wissen teilen zu ermöglichen.
*   **Intranet-Inhaltsveröffentlichung**: MD-Dateien konvertieren, um intranetinhalt veröffentlichen, Formatierung beibehalten und eine reibungslose Zusammenarbeit unter Teammitgliedern ermöglichen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
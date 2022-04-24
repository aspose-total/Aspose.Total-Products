---
title: C#-API zum Exportieren von SVG nach WORDML
description: Konvertieren Sie SVG in WORDML, ohne Microsoft Word zu verwenden
url: /de/net/conversion/svg-to-wordml/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: WORDML
otherformats: RTF OTT MARKDOWN DOT WORDML MHTML ODT XAMLFLOW PCL FLATOPC PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie SVG über .NET in WORDML" h2=".NET-API zum Exportieren von SVG nach WORDML unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET](https://products.aspose.com/pdf/net/) können Sie das SVG-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in WORDML rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von SVG in WORDML" %}}
1. Öffnen Sie die SVG-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie SVG mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document](https://apireference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im WORDML-Format mit der Methode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Wordml als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WordML
outputDocument.Save("output.wordml", SaveFormat.WordML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die SVG-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von SVG in WORDML entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das SVG mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly WORDML-Datei über .NET erstellen" %}}
Um Ihr WORDML vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Dokuments auch über die API festlegen. Sie können die Bearbeitung eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-ott/" name="SVG Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-mhtml/" name="SVG Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-wordml/" name="SVG Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-dot/" name="SVG Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-odt/" name="SVG Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-rtf/" name="SVG Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-ps/" name="SVG Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-flatopc/" name="SVG Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-pcl/" name="SVG Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-markdown/" name="SVG Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-xamlflow/" name="SVG Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/svg-to-dotx/" name="SVG Zu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
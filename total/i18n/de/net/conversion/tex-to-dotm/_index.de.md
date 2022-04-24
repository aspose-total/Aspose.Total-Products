---
title: C#-API zum Exportieren von TEX nach DOTM
description: Konvertieren Sie TEX in DOTM, ohne Microsoft Word zu verwenden
url: /de/net/conversion/tex-to-dotm/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: DOTM
otherformats: XAMLFLOW RTF PCL DOTM OTT MARKDOWN DOTX PS ODT MHTML FLATOPC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie TEX über .NET in DOTM" h2=".NET-API zum Exportieren von TEX nach DOTM unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET](https://products.aspose.com/pdf/net/) können Sie das TEX-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in DOTM rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von TEX in DOTM" %}}
1. Öffnen Sie die TEX-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie TEX mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document](https://apireference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im DOTM-Format mit der Methode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Dotm als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotm", SaveFormat.Dotm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die TEX-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von TEX in DOTM entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das TEX mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly DOTM-Datei über .NET erstellen" %}}
Um Ihr DOTM vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Dokuments auch über die API festlegen. Sie können die Bearbeitung eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-ott/" name="TEX Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-mhtml/" name="TEX Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-wordml/" name="TEX Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-dot/" name="TEX Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-odt/" name="TEX Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-rtf/" name="TEX Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-ps/" name="TEX Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-flatopc/" name="TEX Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-pcl/" name="TEX Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-markdown/" name="TEX Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-xamlflow/" name="TEX Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/tex-to-dotx/" name="TEX Zu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: C#-API zum Exportieren von CGM nach MHTML
description: Konvertieren Sie CGM in MHTML, ohne Microsoft Word zu verwenden
url: /de/net/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: WORDML MHTML DOTX MARKDOWN DOT FLATOPC XAMLFLOW RTF PCL ODT PS DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie CGM über .NET in MHTML" h2=".NET-API zum Exportieren von CGM nach MHTML unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET](https://products.aspose.com/pdf/net/) können Sie das CGM-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in MHTML rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von CGM in MHTML" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie CGM mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document](https://apireference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im MHTML-Format mit der Methode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Mhtml als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die CGM-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von CGM in MHTML entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das CGM mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly MHTML-Datei über .NET erstellen" %}}
Um Ihr MHTML vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Dokuments auch über die API festlegen. Sie können die Bearbeitung eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-ott/" name="CGM Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-mhtml/" name="CGM Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-wordml/" name="CGM Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-dot/" name="CGM Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-odt/" name="CGM Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-rtf/" name="CGM Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-ps/" name="CGM Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-flatopc/" name="CGM Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-pcl/" name="CGM Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-markdown/" name="CGM Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-xamlflow/" name="CGM Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-dotx/" name="CGM Zu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
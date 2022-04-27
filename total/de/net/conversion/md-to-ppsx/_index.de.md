---
title: Exportieren Sie MD über die C#-API nach PPSX
description: .NET-API zum Konvertieren von MD in PPSX ohne Verwendung von Microsoft Word
url: /de/net/conversion/md-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PPSX
otherformats: PPSX POWERPOINT SWF POTX OTP PPSM PPT XAML PPS PPTM POT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie MD über .NET in PPSX" h2=".NET-API zum Exportieren von MD in PPSX unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie MD in zwei einfachen Schritten ganz einfach in PPSX rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das MD-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in PPSX konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von MD in PPSX" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie MD in PPTX, indem Sie die Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im PPSX-Format und legen Sie „Ppsx“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.md");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Holen Sie sich XMP-Metadaten aus der MD-Datei über .NET" %}}
Während der Konvertierung von MD in PPSX benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer MD-Datei. Um die Metadaten einer MD-Datei abzurufen, können Sie ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-MD-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.md");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte PPSX-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre PPSX-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-pot/" name="MD Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ppsx/" name="MD Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-swf/" name="MD Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-powerpoint/" name="MD Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-otp/" name="MD Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-potm/" name="MD Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ppt/" name="MD Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-pps/" name="MD Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-potx/" name="MD Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-xaml/" name="MD Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ppsm/" name="MD Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-pptm/" name="MD Zu PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
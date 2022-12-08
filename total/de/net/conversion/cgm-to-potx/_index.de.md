---
title: Exportieren Sie CGM über die C#-API nach POTX
description: .NET-API zum Konvertieren von CGM in POTX ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/cgm-to-potx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTX
otherformats: PPTM POTX OTP XAML PPS POT PPT SWF PPSM POTM POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie CGM über .NET in POTX" h2=".NET-API zum Exportieren von CGM in POTX unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie CGM in zwei einfachen Schritten ganz einfach in POTX rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das CGM-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in POTX konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von CGM in POTX" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie CGM in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im POTX-Format und legen Sie „Potx“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potx", SaveFormat.Potx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Holen Sie sich XMP-Metadaten aus der CGM-Datei über .NET" %}}
Während der Konvertierung von CGM in POTX benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer CGM-Datei. Um die Metadaten einer CGM-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-CGM-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte POTX-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre POTX-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-pot/" name="CGM Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-ppsx/" name="CGM Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-swf/" name="CGM Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-powerpoint/" name="CGM Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-otp/" name="CGM Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-potm/" name="CGM Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-ppt/" name="CGM Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-pps/" name="CGM Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-potx/" name="CGM Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-xaml/" name="CGM Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-ppsm/" name="CGM Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/cgm-to-pptm/" name="CGM Zu PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
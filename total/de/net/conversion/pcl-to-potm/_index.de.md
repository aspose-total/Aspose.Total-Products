---
title: Exportieren Sie PCL über die C#-API nach POTM
description: .NET-API zum Konvertieren von PCL in POTM ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/pcl-to-potm/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: POTM
otherformats: PPSX SWF XAML POTX PPSM POWERPOINT OTP PPT POT PPTM POTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie PCL über .NET in POTM" h2=".NET-API zum Exportieren von PCL in POTM unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie PCL in zwei einfachen Schritten ganz einfach in POTM rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das PCL-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in POTM konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von PCL in POTM" %}}
1. Öffnen Sie die PCL-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie PCL in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im POTM-Format und legen Sie „Potm“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.pcl");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Holen Sie sich XMP-Metadaten aus der PCL-Datei über .NET" %}}
Während der Konvertierung von PCL in POTM benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer PCL-Datei. Um die Metadaten einer PCL-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-PCL-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.pcl");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte POTM-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre POTM-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-pot/" name="PCL Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-ppsx/" name="PCL Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-swf/" name="PCL Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-powerpoint/" name="PCL Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-otp/" name="PCL Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-potm/" name="PCL Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-ppt/" name="PCL Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-pps/" name="PCL Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-potx/" name="PCL Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-xaml/" name="PCL Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-ppsm/" name="PCL Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/pcl-to-pptm/" name="PCL Zu PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
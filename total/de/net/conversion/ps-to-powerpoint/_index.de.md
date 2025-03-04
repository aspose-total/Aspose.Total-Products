---
title: Exportieren Sie PS über die C#-API nach POWERPOINT
description: .NET-API zum Konvertieren von PS in POWERPOINT ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/ps-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POWERPOINT
otherformats: SWF PPTM XAML OTP PPSX POT PPT PPSM POTM PPS POTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie PS über .NET in POWERPOINT" h2=".NET-API zum Exportieren von PS in POWERPOINT unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie PS in zwei einfachen Schritten ganz einfach in POWERPOINT rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das PS-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in POWERPOINT konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von PS in POWERPOINT" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie PS in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im POWERPOINT-Format und legen Sie „Powerpoint“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Holen Sie sich XMP-Metadaten aus der PS-Datei über .NET" %}}
Während der Konvertierung von PS in POWERPOINT benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer PS-Datei. Um die Metadaten einer PS-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-PS-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte POWERPOINT-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre POWERPOINT-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PS-Dateien programmgesteuert in POWERPOINT umwandeln: Anwendungsfälle" %}}
PS-Dateien (Portable Document Format) sind ideal für die Speicherung von Dokumenten mit präzisen Layouts, was sie perfekt für die Erstellung professionell aussehender Berichte, Broschüren und Präsentationen macht. Allerdings werden bei der Arbeit mit dynamischen Inhalten Microsoft PowerPoint zu einem unverzichtbaren Werkzeug für die Visualisierung von Daten und Analyse.

Die Umwandlung von PS-Dateien in PowerPoint-Format ist notwendig, um das volle Potenzial deiner Präsentationsdesign und Kolaborationsfähigkeiten zu entfalten. Diese Umwandlung ermöglicht es dir:

**Verwendungsbeispiele:**

*   **Unternehmen:** Verwenden Sie PS-Dateien, um fesselnde Unternehmenspräsentationen zu erstellen, bei denen Produkte, Dienstleistungen oder Firmennews präsentiert werden.
*   **Marketingmaterialien:** Verwenden Sie PowerPoint, um Marketingmaterialien wie Produktbroschüren, Angebotsblätter und Werbeschriften visuell darzustellen.
*   **Bildungsinhalt:** Wandeln Sie PS-Dateien in interaktiven Bildungsinhalte um, einschließlich Vorträge, Präsentationen und Tutorials.
*   **Verkaufsmaterialien:** Verwenden Sie PowerPoint, um professionelles Verkaufsunterlagen wie Pitch-Dek, Angebote und Präsentationen zu gestalten.
*   ** Veranstaltungs Materialien:** Wandeln Sie PS-Dateien in ansprechende Veranstaltungsmaterialien um, einschließlich Konferenzprogrammen, Agenden und Handouts.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
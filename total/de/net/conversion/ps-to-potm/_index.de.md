---
title: Exportieren Sie PS über die C#-API nach POTM
description: .NET-API zum Konvertieren von PS in POTM ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/ps-to-potm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTM
otherformats: POT POTX XAML PPSM OTP POWERPOINT PPSX PPTM PPT SWF PPS POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie PS über .NET in POTM" h2=".NET-API zum Exportieren von PS in POTM unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie PS in zwei einfachen Schritten ganz einfach in POTM rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das PS-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in POTM konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von PS in POTM" %}}
1. Öffnen Sie die PS-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie PS in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im POTM-Format und legen Sie „Potm“ als SaveFormat fest
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
Während der Konvertierung von PS in POTM benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer PS-Datei. Um die Metadaten einer PS-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-PS-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="PS-Dateien programmgesteuert in POTM umwandeln: Anwendungsfälle" %}}
PDF-Dateien (Portable Document Format) werden verwendet, um Informationen von Dokumenten zu speichern, was sie für die Erstellung statischer Dokumente und Veröffentlichungen ideal macht. Allerdings spielen bei der Arbeit mit dynamischen Daten Software wie PowerPoint eine entscheidende Rolle für Präsentationen und Visualisierungen.

Die Umwandlung von PDF-Dateien in PowerPoint-Format ist erforderlich, um die volle Potenz deiner Präsentations- und Visualisierungsfähigkeiten freizusetzen. Diese Umwandlung ermöglicht es dir:

*   **Unternehmenspräsentationsdesign**: PDF-Dateien konvertieren, um fesselnde Unternehmenspräsentationen, Slideshows und Geschichten zu erstellen.
*   **Marketingkampagnen präsentieren**: PowerPoint nutzt, um Daten der Marketingkampagne, Strategien zu optimieren und ROI interaktiv zu messen.
*   **Bildungsstoff erstellen**: PDF-Dateien konvertieren, um interaktive Bildungsinhalte wie Übungen, Spiele und Simulationsprogramme zu schaffen.
*   **Forschungsberichterstattung vorbereiten**: PowerPoint nutzt, um Forschungsberichte, Berichte und andere Dokumente in einer geeigneten Form für die Veröffentlichung vorzubereiten.
*   **Präsentationen und Vorschläge erstellen**: PDF-Dateien konvertieren, um dynamische Präsentationen und Vorschläge zu erstellen, die das Publikum fesseln und komplexe Informationen klar vermitteln.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
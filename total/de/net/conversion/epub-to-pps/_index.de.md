---
title: Exportieren Sie EPUB über die C#-API nach PPS
description: .NET-API zum Konvertieren von EPUB in PPS ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/epub-to-pps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPSX XAML PPT PPTM POTM POTX SWF PPS OTP POT PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie EPUB über .NET in PPS" h2=".NET-API zum Exportieren von EPUB in PPS unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie EPUB in zwei einfachen Schritten ganz einfach in PPS rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das EPUB-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in PPS konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von EPUB in PPS" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie EPUB in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im PPS-Format und legen Sie „Pps“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Holen Sie sich XMP-Metadaten aus der EPUB-Datei über .NET" %}}
Während der Konvertierung von EPUB in PPS benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer EPUB-Datei. Um die Metadaten einer EPUB-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-EPUB-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte PPS-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre PPS-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EPUB-Dateien programmgesteuert in PPS umwandeln: Anwendungsfälle" %}}
Epub-Dateien (Elektronische Veröffentlichungsformat) werden für die Speicherung digitaler Inhalte verwendet, wodurch sie ideal für die Erstellung und Verteilung von E-Books, Artikeln und anderen schriftlichen Materialien sind. Allerdings spielen PowerPoint-Dateien bei der Bearbeitung von Präsentationsdaten eine entscheidende Rolle, um aufmunternde Slideshows und Präsentationen zu erstellen.

Die Umwandlung von Epub-Dateien in PPS-(PowerPoint-Presentations-Datei)-Format ist notwendig, um die volle Potenz deiner Präsentationsfähigkeiten zu entfalten. Diese Umwandlung ermöglicht dir:

**Anwendungszwecke:**

*   **Unternehmenskommunikation**: Wandele Epub-Dateien in Engagementformate für Unternehmen wie Jahresberichte, Unternehmensaktualisierungen und Produktpräsentationen um.
*   **Akademischer Forschungspräsentations**: Verwende PPS, um Forschungsergebnisse vorzustellen, mit Kollegen zu zusammenarbeiten und Wissen mit Kollegen zu teilen.
*   **E-Learning-Inhalte erstellen**: Wandele Epub-Dateien in interaktive E-Learning-Materialien, Simulatoren und Tutorials um.
*   **Digitale Publikationen**: Verwende PPS, um digitale Inhalte wie E-Books, Magazine und Zeitungen auf verschiedenen Plattformen zu veröffentlichen.
*   **Veranstaltungspräsentationen**: Wandele Epub-Dateien in dynamische Präsentationen für Veranstaltungen, Konferenzen und Webinaren um.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
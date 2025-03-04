---
title: Exportieren Sie EPUB über die C#-API nach PPSM
description: .NET-API zum Konvertieren von EPUB in PPSM ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/epub-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSM
otherformats: PPSM POTX OTP PPTM SWF POWERPOINT XAML PPT POTM PPS PPSX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie EPUB über .NET in PPSM" h2=".NET-API zum Exportieren von EPUB in PPSM unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie EPUB in zwei einfachen Schritten ganz einfach in PPSM rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das EPUB-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in PPSM konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von EPUB in PPSM" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie EPUB in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im PPSM-Format und legen Sie „Ppsm“ als SaveFormat fest
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
Während der Konvertierung von EPUB in PPSM benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer EPUB-Datei. Um die Metadaten einer EPUB-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-EPUB-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte PPSM-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre PPSM-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EPUB-Dateien programmgesteuert in PPSM umwandeln: Anwendungsfälle" %}}
Die Umwandlung von EPUB-Dateien in PPSM-Formaten ist notwendig, um das volle Potenzial deiner Präsentationsfähigkeiten zu freilegen.

Die Umwandlung von EPUB-Dateien in PPSM-Formaten ist von entscheidender Bedeutung, um das volle Potenzial deiner Präsentationsfähigkeiten zu freilegen. Diese Umwandlung ermöglicht es dir:

**Anwendungsszenarien:**

*   **Unternehmen präsentieren**: Wandele EPUB-Dateien in interaktive Unternehmenspräsentationen um, visualisiere Datengetriebene Einblicke und teile Kenntnisse innerhalb von Teams.
*   **Akademische Vorlesungen:** Nutze PPSM-Formate, um interaktive Vorlesungen durchzuführen, Forschungsergebnisse vorzustellen und den Unterrichtsablauf zu erleichtern.
*   **E-Learning-Inhalte erstellen**: Wandele EPUB-Dateien in interaktives E-Learning-Inhalt um, verfolge die Fortschritte der Lerner und verbessere Online-Kurse.
*   **Marketingmaterialien erstellen:** Nutze PPSM-Formate, um ansprechende Marketingmaterialien wie Broschüren, Flugblätter und Verkaufsblatt schaffen zu können.
*   **Konferenzpräsentationen**: Nutze PPSM-Formate, um Forschungspapier vorzustellen, innovative Ideen mit der Öffentlichkeit zu teilen und eine interaktive Präsentation durchzuführen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
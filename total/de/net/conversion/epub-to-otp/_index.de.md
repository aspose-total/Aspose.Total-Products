---
title: Exportieren Sie EPUB über die C#-API nach OTP
description: .NET-API zum Konvertieren von EPUB in OTP ohne Verwendung von Microsoft Word
url_ignore: /de/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie EPUB über .NET in OTP" h2=".NET-API zum Exportieren von EPUB in OTP unter Windows, macOS und Linux, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mit einem Paket leistungsstarker APIs zur Dateiformatautomatisierung [Aspose.Total für .NET](https://products.aspose.com/total/net/) können Sie EPUB in zwei einfachen Schritten ganz einfach in OTP rendern. Durch die Verwendung der PDF-Verarbeitungs-API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) können Sie das EPUB-Dateiformat in PPTX umwandeln. Danach können Sie mithilfe der Präsentationsverarbeitungs-API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) PPTX in OTP konvertieren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-API zum Konvertieren von EPUB in OTP" %}}
1. Öffnen Sie die EPUB-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie EPUB in PPTX, indem Sie die Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) verwenden
3. Laden Sie die PPTX-Datei mithilfe der Klasse [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) im OTP-Format und legen Sie „Otp“ als SaveFormat fest
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
Während der Konvertierung von EPUB in OTP benötigen Sie möglicherweise zusätzliche XMP-Metadateninformationen, um Ihren Batch-Konvertierungsprozess zu priorisieren. Beispielsweise können Sie Ihre Konvertierungsdokumente nach Erstellungsdatum abrufen und sortieren und die Dokumente entsprechend verarbeiten. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ermöglicht Ihnen den Zugriff auf die XMP-Metadaten einer EPUB-Datei. Um die Metadaten einer EPUB-Datei abzurufen, können Sie ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und die Eingabe-EPUB-Datei öffnen. Danach können Sie die Metadaten der Datei mit der Eigenschaft [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) abrufen.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Erstellen Sie eine schreibgeschützte OTP-Datei über .NET" %}}
Durch die Verwendung der [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API können Sie die Funktionen Ihrer Konvertierungsanwendung weiter verbessern. Eine der Funktionen kann darin bestehen, Ihre Ausgabedatei schreibgeschützt zu erstellen, um die Sicherheit zu erhöhen. Mit der API können Sie Ihre OTP-Datei auf Read-Only setzen, was bedeutet, dass Benutzer (nachdem sie die Präsentation öffnen) die Read-Only-Empfehlung sehen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EPUB-Dateien programmgesteuert in OTP umwandeln: Anwendungsfälle" %}}
E-Books (Elektronische Veröffentlichung) Dateien werden verwendet, um digitale Inhalte zu speichern und somit für die Erstellung dynamischer Inhalte und interaktiver Erfahrungen geeignet. Die Arbeit mit Offline-Daten hingegen macht Textdateien unverzichtbar für langfristige Speicherung und Archivierungszwecke.

Die Umwandlung von E-Book Dateien in Offline-Textdateien ist notwendig, um die volle Potenz deiner Sammlungen und Bibliotheken zu freilocken. Diese Umwandlung ermöglicht es dir:

**Verwendungsfälle:**

*   **Digitale Erhaltung**: Wandele E-Book Dateien in permanente Archivdateien um, um sicherzustellen, dass digitale Inhalte über die Zeit verfügbar bleiben.
*   **Offline Lesen und Teilen**: Nutze Offline-Textdateien, um digitale Inhalte zu verteilen, ohne auf Internetverbindung angewiesen zu sein. Dies macht sie ideal für Bereiche mit begrenztem Zugang oder in Situationen, in denen Wi-Fi nicht verfügbar ist.
*   **Bibliotheksmanagement und Organisation**: Wandele E-Book Dateien in strukturierte und organisierte Sammlungen von Textdaten um. Dies erleichtert die Suche, Kategorisierung und Rücksprache auf spezifische Informationen.
*   **Digitale Archivierung und Wiederherstellung**: Verwende Offline-Textdateien, um digitale Artefakte zu speichern und beschädigte Inhalte wiederherzustellen. Dies sichert die Integrität wertvoller Informationen für zukünftige Generationen.
*   **Offline Inhaltserstellung und Bearbeitung**: Wandele E-Book Dateien in bearbare Inhalte um, ohne auf Internetverbindung angewiesen zu sein. Dies macht sie ideal für Autoren, Schriftsteller und Verleger, die in Isolation arbeiten oder mit begrenztem Zugang zu Online-Ressourcen auskommen müssen.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
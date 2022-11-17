---
title: C++-API zum Konvertieren von PPTM in RTF
description: Exportieren Sie PPTM in RTF innerhalb Ihrer C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: RTF
otherformats: ODT DOC DOCM WORDML FLATOPC WORD DOTM DOT DOCX DOTX OTT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Rendern von PPTM in RTF" h2="Exportieren Sie PPTM in RTF in C++-Anwendungen ohne Microsoft PowerPoint- oder Word-Abhängigkeiten" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) ist ein vollständiges Paket von C++ File Format Automation-Bibliotheken. Durch die Verwendung der reichhaltigen Funktionen der im Paket verfügbaren APIs können wir PowerPoint PPTM problemlos in Word RTF konvertieren. Um die Konvertierung durchzuführen, können Sie zuerst die API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um PPTM in HTML zu konvertieren. Danach können Sie mithilfe der funktionsreichen Textverarbeitungs-API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) den HTML-Code in RTF konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von PPTM in RTF" %}}
1. Laden Sie die PPTM-Datei mit der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Rendern Sie PPTM in HTML mit der Mitgliedsfunktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mithilfe der Klassenreferenz [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument).
4. Speichern Sie das Dokument mithilfe der Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string) im RTF-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-odt/" name="PPTM Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-rtf/" name="PPTM Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-rtfm/" name="PPTM Zu RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-wordml/" name="PPTM Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-flatopc/" name="PPTM Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-word/" name="PPTM Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-dotm/" name="PPTM Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-dot/" name="PPTM Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-rtfx/" name="PPTM Zu RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-dotx/" name="PPTM Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-ott/" name="PPTM Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pptm-to-text/" name="PPTM Zu TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
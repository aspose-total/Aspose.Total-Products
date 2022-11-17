---
title: C++-API zum Konvertieren von PPS in DOT
description: Exportieren Sie PPS in DOT innerhalb Ihrer C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOT
otherformats: TEXT WORD ODT DOCX OTT DOTX DOCM DOTM DOC RTF WORDML FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Rendern von PPS in DOT" h2="Exportieren Sie PPS in DOT in C++-Anwendungen ohne Microsoft PowerPoint- oder Word-Abhängigkeiten" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) ist ein vollständiges Paket von C++ File Format Automation-Bibliotheken. Durch die Verwendung der reichhaltigen Funktionen der im Paket verfügbaren APIs können wir PowerPoint PPS problemlos in Word DOT konvertieren. Um die Konvertierung durchzuführen, können Sie zuerst die API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um PPS in HTML zu konvertieren. Danach können Sie mithilfe der funktionsreichen Textverarbeitungs-API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) den HTML-Code in DOT konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von PPS in DOT" %}}
1. Laden Sie die PPS-Datei mit der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Rendern Sie PPS in HTML mit der Mitgliedsfunktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mithilfe der Klassenreferenz [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument).
4. Speichern Sie das Dokument mithilfe der Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string) im DOT-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotument
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"htmlOutput.html");
// save dotument in DOT format
dot->Save(u"output.dot"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-text/" name="PPS Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-word/" name="PPS Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-odt/" name="PPS Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-dotx/" name="PPS Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-ott/" name="PPS Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-dotx/" name="PPS Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-dotm/" name="PPS Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-dotm/" name="PPS Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-dot/" name="PPS Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-rtf/" name="PPS Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-wordml/" name="PPS Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/pps-to-flatopc/" name="PPS Zu FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
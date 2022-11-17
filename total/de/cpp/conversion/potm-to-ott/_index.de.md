---
title: C++-API zum Konvertieren von POTM in OTT
description: Exportieren Sie POTM in OTT innerhalb Ihrer C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: OTT
otherformats: FLATOPC WORD DOCM TEXT RTF DOTM DOTX DOC WORDML DOCX ODT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Rendern von POTM in OTT" h2="Exportieren Sie POTM in OTT in C++-Anwendungen ohne Microsoft PowerPoint- oder Word-Abhängigkeiten" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) ist ein vollständiges Paket von C++ File Format Automation-Bibliotheken. Durch die Verwendung der reichhaltigen Funktionen der im Paket verfügbaren APIs können wir PowerPoint POTM problemlos in Word OTT konvertieren. Um die Konvertierung durchzuführen, können Sie zuerst die API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um POTM in HTML zu konvertieren. Danach können Sie mithilfe der funktionsreichen Textverarbeitungs-API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) den HTML-Code in OTT konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von POTM in OTT" %}}
1. Laden Sie die POTM-Datei mit der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Rendern Sie POTM in HTML mit der Mitgliedsfunktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mithilfe der Klassenreferenz [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument).
4. Speichern Sie das Dokument mithilfe der Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string) im OTT-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-flatopc/" name="POTM Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-word/" name="POTM Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-ottm/" name="POTM Zu OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-text/" name="POTM Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-rtf/" name="POTM Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-dotm/" name="POTM Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-dotx/" name="POTM Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-ott/" name="POTM Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-wordml/" name="POTM Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-ottx/" name="POTM Zu OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-odt/" name="POTM Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potm-to-dot/" name="POTM Zu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
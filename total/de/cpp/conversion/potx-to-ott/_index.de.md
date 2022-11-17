---
title: C++-API zum Konvertieren von POTX in OTT
description: Exportieren Sie POTX in OTT innerhalb Ihrer C++-Anwendungen

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: OTT
otherformats: DOTX DOTM DOCM ODT TEXT DOC WORD RTF FLATOPC WORDML DOCX DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Rendern von POTX in OTT" h2="Exportieren Sie POTX in OTT in C++-Anwendungen ohne Microsoft PowerPoint- oder Word-Abhängigkeiten" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) ist ein vollständiges Paket von C++ File Format Automation-Bibliotheken. Durch die Verwendung der reichhaltigen Funktionen der im Paket verfügbaren APIs können wir PowerPoint POTX problemlos in Word OTT konvertieren. Um die Konvertierung durchzuführen, können Sie zuerst die API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um POTX in HTML zu konvertieren. Danach können Sie mithilfe der funktionsreichen Textverarbeitungs-API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) den HTML-Code in OTT konvertieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von POTX in OTT" %}}
1. Laden Sie die POTX-Datei mit der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
2. Rendern Sie POTX in HTML mit der Mitgliedsfunktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Html als SaveFormat fest
3. Laden Sie die konvertierte HTML-Datei mithilfe der Klassenreferenz [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument).
4. Speichern Sie das Dokument mithilfe der Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string) im OTT-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-dotx/" name="POTX Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-dotm/" name="POTX Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-ottm/" name="POTX Zu OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-odt/" name="POTX Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-text/" name="POTX Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-ott/" name="POTX Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-word/" name="POTX Zu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-rtf/" name="POTX Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-flatopc/" name="POTX Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-wordml/" name="POTX Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-ottx/" name="POTX Zu OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/potx-to-dot/" name="POTX Zu DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
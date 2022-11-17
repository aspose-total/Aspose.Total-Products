---
title: API C++ per convertire POTM in ODT
description: Esporta POTM in ODT all'interno delle tue applicazioni C++

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: ODT
otherformats: DOTM DOCX RTF DOTX FLATOPC WORD DOCM DOC WORDML DOT OTT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per il rendering di POTM in ODT" h2="Esporta POTM in ODT in applicazioni C++ senza dipendenze da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è un pacchetto completo di librerie C++ File Format Automation. Utilizzando le ricche funzionalità delle API disponibili nel pacchetto, possiamo convertire facilmente PowerPoint POTM in Word ODT. Per eseguire la conversione, puoi prima utilizzare l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per convertire POTM in HTML. Successivamente, utilizzando l'API di elaborazione testi ricca di funzionalità [Aspose.Words for C++](https://products.aspose.com/words/cpp/) puoi convertire l'HTML in ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire POTM in ODT" %}}
1. Caricare il file POTM utilizzando [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) riferimento alla classe
2. Eseguire il rendering di POTM in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e impostare Html come SaveFormat
3. Caricare il file HTML convertito utilizzando il riferimento alla classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. Salvare il odtumento in formato ODT utilizzando [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) funzione membro
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-dotm/" name="POTM Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-odtx/" name="POTM Per ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-rtf/" name="POTM Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-dotx/" name="POTM Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-flatopc/" name="POTM Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-word/" name="POTM Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-odtm/" name="POTM Per ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-odt/" name="POTM Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-wordml/" name="POTM Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-dot/" name="POTM Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-ott/" name="POTM Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/potm-to-text/" name="POTM Per TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
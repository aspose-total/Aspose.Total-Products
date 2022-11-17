---
title: API C++ per convertire PPSX in ODT
description: Esporta PPSX in ODT all'interno delle tue applicazioni C++

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: ODT
otherformats: TEXT DOCX RTF DOT DOTX DOTM DOCM FLATOPC DOC WORD WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per il rendering di PPSX in ODT" h2="Esporta PPSX in ODT in applicazioni C++ senza dipendenze da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è un pacchetto completo di librerie C++ File Format Automation. Utilizzando le ricche funzionalità delle API disponibili nel pacchetto, possiamo convertire facilmente PowerPoint PPSX in Word ODT. Per eseguire la conversione, puoi prima utilizzare l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per convertire PPSX in HTML. Successivamente, utilizzando l'API di elaborazione testi ricca di funzionalità [Aspose.Words for C++](https://products.aspose.com/words/cpp/) puoi convertire l'HTML in ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire PPSX in ODT" %}}
1. Caricare il file PPSX utilizzando [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) riferimento alla classe
2. Eseguire il rendering di PPSX in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e impostare Html come SaveFormat
3. Caricare il file HTML convertito utilizzando il riferimento alla classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. Salvare il odtumento in formato ODT utilizzando [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) funzione membro
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-text/" name="PPSX Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-odtx/" name="PPSX Per ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-rtf/" name="PPSX Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-dot/" name="PPSX Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-dotx/" name="PPSX Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-dotm/" name="PPSX Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-odtm/" name="PPSX Per ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-flatopc/" name="PPSX Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-odt/" name="PPSX Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-word/" name="PPSX Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-wordml/" name="PPSX Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/ppsx-to-ott/" name="PPSX Per OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
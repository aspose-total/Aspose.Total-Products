---
title: API C++ per convertire PPS in DOCM
description: Esporta PPS in DOCM all'interno delle tue applicazioni C++
url: /it/cpp/conversion/pps-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCM
otherformats: DOTX DOC DOCX DOTM DOT WORDML ODT WORD FLATOPC TEXT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per il rendering di PPS in DOCM" h2="Esporta PPS in DOCM in applicazioni C++ senza dipendenze da Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è un pacchetto completo di librerie C++ File Format Automation. Utilizzando le ricche funzionalità delle API disponibili nel pacchetto, possiamo convertire facilmente PowerPoint PPS in Word DOCM. Per eseguire la conversione, puoi prima utilizzare l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per convertire PPS in HTML. Successivamente, utilizzando l'API di elaborazione testi ricca di funzionalità [Aspose.Words for C++](https://products.aspose.com/words/cpp/) puoi convertire l'HTML in DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire PPS in DOCM" %}}
1. Caricare il file PPS utilizzando [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) riferimento alla classe
2. Eseguire il rendering di PPS in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e impostare Html come SaveFormat
3. Caricare il file HTML convertito utilizzando il riferimento alla classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
4. Salvare il docmumento in formato DOCM utilizzando [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string) funzione membro
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-dotx/" name="PPS Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-docm/" name="PPS Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-docmx/" name="PPS Per DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-dotm/" name="PPS Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-dot/" name="PPS Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-wordml/" name="PPS Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-odt/" name="PPS Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-word/" name="PPS Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-flatopc/" name="PPS Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-text/" name="PPS Per TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-rtf/" name="PPS Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pps-to-ott/" name="PPS Per OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
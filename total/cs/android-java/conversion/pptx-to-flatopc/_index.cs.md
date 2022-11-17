---
title: Export PPTX do FLATOPC na Andorid přes Java
description: Převeďte PPTX na FLATOPC v mobilních aplikacích bez instalace jakéhokoli softwaru

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: FLATOPC
otherformats: DOCM WORDML OTT DOC WORD DOT DOTX DOCX RTF DOTM ODT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderujte PPTX do FLATOPC na Andoridu přes Javu" h2="Rozhraní API pro formát souborů pro převod PPTX na FLATOPC v aplikacích pro Android bez závislosti na Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) umožňuje manipulaci s formáty souborů v aplikacích pro Android. Pomocí rozhraní API poskytovaných v balíčku můžete automatizovat proces převodu PowerPoint PPTX do Word FLATOPC ve vašich aplikacích.
Zadaný dokument můžete převést ve dvou krocích. K vykreslení PPTX do HTML můžete použít [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/), což je PowerPoint API pro aplikace Android. Pptxé pomocí API pro zpracování dokumentů [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/) můžete převést HTML na FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Vykreslování PPTX do FLATOPC v Androidu" %}}
1. Otevřete soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Převeďte PPTX do HTML pomocí [uložit](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí třídy [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. Uložte dokument do formátu FLATOPC pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) a nastavte Flatopc jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Slides pro Android přes Javu](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) a [Aspose.Words pro Andorid přes Javu](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašem aplikací.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-flatopcm/" name="PPTX Na FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-wordml/" name="PPTX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-ott/" name="PPTX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-flatopc/" name="PPTX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-word/" name="PPTX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-dot/" name="PPTX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-dotx/" name="PPTX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-flatopcx/" name="PPTX Na FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-rtf/" name="PPTX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-dotm/" name="PPTX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-odt/" name="PPTX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pptx-to-text/" name="PPTX Na TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
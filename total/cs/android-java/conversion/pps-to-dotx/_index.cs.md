---
title: Export PPS do DOTX na Andorid přes Java
description: Převeďte PPS na DOTX v mobilních aplikacích bez instalace jakéhokoli softwaru

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOTX
otherformats: TEXT DOCX OTT ODT FLATOPC DOC DOT WORDML DOTM DOCM WORD RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderujte PPS do DOTX na Andoridu přes Javu" h2="Rozhraní API pro formát souborů pro převod PPS na DOTX v aplikacích pro Android bez závislosti na Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) umožňuje manipulaci s formáty souborů v aplikacích pro Android. Pomocí rozhraní API poskytovaných v balíčku můžete automatizovat proces převodu PowerPoint PPS do Word DOTX ve vašich aplikacích.
Zadaný dokument můžete převést ve dvou krocích. K vykreslení PPS do HTML můžete použít [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/), což je PowerPoint API pro aplikace Android. Ppsé pomocí API pro zpracování dokumentů [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/) můžete převést HTML na DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Vykreslování PPS do DOTX v Androidu" %}}
1. Otevřete soubor PPS pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Převeďte PPS do HTML pomocí [uložit](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí třídy [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. Uložte dokument do formátu DOTX pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) a nastavte Dotx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Slides pro Android přes Javu](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) a [Aspose.Words pro Andorid přes Javu](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašem aplikací.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-text/" name="PPS Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-dotxx/" name="PPS Na DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-ott/" name="PPS Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-odt/" name="PPS Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-flatopc/" name="PPS Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-dotx/" name="PPS Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-dot/" name="PPS Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-wordml/" name="PPS Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-dotm/" name="PPS Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-dotxm/" name="PPS Na DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-word/" name="PPS Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pps-to-rtf/" name="PPS Na RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
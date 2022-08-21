---
title: Export POT do DOTM na Andorid přes Java
description: Převeďte POT na DOTM v mobilních aplikacích bez instalace jakéhokoli softwaru
url: /cs/android-java/conversion/pot-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOTM
otherformats: RTF DOCM WORDML DOTX DOCX TEXT DOT WORD DOC FLATOPC OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderujte POT do DOTM na Andoridu přes Javu" h2="Rozhraní API pro formát souborů pro převod POT na DOTM v aplikacích pro Android bez závislosti na Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) umožňuje manipulaci s formáty souborů v aplikacích pro Android. Pomocí rozhraní API poskytovaných v balíčku můžete automatizovat proces převodu PowerPoint POT do Word DOTM ve vašich aplikacích.
Zadaný dokument můžete převést ve dvou krocích. K vykreslení POT do HTML můžete použít [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/), což je PowerPoint API pro aplikace Android. Poté pomocí API pro zpracování dokumentů [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/) můžete převést HTML na DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Vykreslování POT do DOTM v Androidu" %}}
1. Otevřete soubor POT pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Převeďte POT do HTML pomocí [uložit](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí třídy [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
4. Uložte dokument do formátu DOTM pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int)) a nastavte Dotm jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Slides pro Android přes Javu](https://dotms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) a [Aspose.Words pro Andorid přes Javu](https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašem aplikací.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotmument
Dotmument dotmument = new Dotmument("htmlOutput.html");
// save dotmument in DOTM format
dotmument.save("output.dotm",SaveFormat.Dotm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-rtf/" name="POT Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-dotmm/" name="POT Na DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-wordml/" name="POT Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-dotx/" name="POT Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-dotmx/" name="POT Na DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-text/" name="POT Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-dot/" name="POT Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-word/" name="POT Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-dotm/" name="POT Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-flatopc/" name="POT Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-ott/" name="POT Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/pot-to-odt/" name="POT Na ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
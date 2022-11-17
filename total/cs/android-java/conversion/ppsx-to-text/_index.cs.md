---
title: Export PPSX do TEXT na Andorid přes Java
description: Převeďte PPSX na TEXT v mobilních aplikacích bez instalace jakéhokoli softwaru

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: TEXT
otherformats: DOTM RTF DOTX WORDML DOT WORD FLATOPC ODT OTT DOCM DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderujte PPSX do TEXT na Andoridu přes Javu" h2="Rozhraní API pro formát souborů pro převod PPSX na TEXT v aplikacích pro Android bez závislosti na Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) umožňuje manipulaci s formáty souborů v aplikacích pro Android. Pomocí rozhraní API poskytovaných v balíčku můžete automatizovat proces převodu PowerPoint PPSX do Word TEXT ve vašich aplikacích.
Zadaný dokument můžete převést ve dvou krocích. K vykreslení PPSX do HTML můžete použít [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/), což je PowerPoint API pro aplikace Android. Ppsxé pomocí API pro zpracování dokumentů [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/) můžete převést HTML na TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Vykreslování PPSX do TEXT v Androidu" %}}
1. Otevřete soubor PPSX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Převeďte PPSX do HTML pomocí [uložit](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí třídy [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. Uložte dokument do formátu TEXT pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) a nastavte Text jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Slides pro Android přes Javu](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) a [Aspose.Words pro Andorid přes Javu](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašem aplikací.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Textument
Textument textument = new Textument("htmlOutput.html");
// save textument in TEXT format
textument.save("output.text",SaveFormat.Text);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-dotm/" name="PPSX Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-rtf/" name="PPSX Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-dotx/" name="PPSX Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-wordml/" name="PPSX Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-dot/" name="PPSX Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-word/" name="PPSX Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-flatopc/" name="PPSX Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-odt/" name="PPSX Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-ott/" name="PPSX Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-textm/" name="PPSX Na TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-text/" name="PPSX Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ppsx-to-textx/" name="PPSX Na TEXTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
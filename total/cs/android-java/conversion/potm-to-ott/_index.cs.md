---
title: Export POTM do OTT na Andorid přes Java
description: Převeďte POTM na OTT v mobilních aplikacích bez instalace jakéhokoli softwaru
url: /cs/android-java/conversion/potm-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: OTT
otherformats: ODT DOC DOCM WORD DOTX TEXT DOT WORDML FLATOPC DOTM RTF DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderujte POTM do OTT na Andoridu přes Javu" h2="Rozhraní API pro formát souborů pro převod POTM na OTT v aplikacích pro Android bez závislosti na Microsoft PowerPoint nebo Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) umožňuje manipulaci s formáty souborů v aplikacích pro Android. Pomocí rozhraní API poskytovaných v balíčku můžete automatizovat proces převodu PowerPoint POTM do Word OTT ve vašich aplikacích.
Zadaný dokument můžete převést ve dvou krocích. K vykreslení POTM do HTML můžete použít [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/), což je PowerPoint API pro aplikace Android. Potmé pomocí API pro zpracování dokumentů [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/) můžete převést HTML na OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Vykreslování POTM do OTT v Androidu" %}}
1. Otevřete soubor POTM pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Převeďte POTM do HTML pomocí [uložit](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) a nastavte Html jako SaveFormat
3. Načtěte převedený soubor HTML pomocí třídy [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument)
4. Uložte dokument do formátu OTT pomocí metody [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) a nastavte Ott jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.Slides pro Android přes Javu](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) a [Aspose.Words pro Andorid přes Javu](https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašem aplikací.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-odt/" name="POTM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-ott/" name="POTM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-ottm/" name="POTM Na OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-word/" name="POTM Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-dotx/" name="POTM Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-text/" name="POTM Na TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-dot/" name="POTM Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-wordml/" name="POTM Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-flatopc/" name="POTM Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-dotm/" name="POTM Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-rtf/" name="POTM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/potm-to-ottx/" name="POTM Na OTTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
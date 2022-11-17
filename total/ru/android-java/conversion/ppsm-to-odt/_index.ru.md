---
title: Экспорт PPSM в ODT на Andorid через Java
description: Конвертируйте PPSM в ODT в мобильных приложениях без установки какого-либо программного обеспечения

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: ODT
otherformats: TEXT DOCM DOTM OTT DOTX WORD DOT WORDML DOCX DOC RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг PPSM в ODT на Andorid через Java" h2="API форматов файлов для преобразования PPSM в ODT в приложениях Android независимо от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) позволяет управлять форматами файлов в приложениях Android. С помощью API-интерфейсов, предоставляемых в пакете, вы можете автоматизировать процесс преобразования PowerPoint PPSM в Word ODT в своих приложениях.
Вы можете преобразовать данный документ в два этапа. Вы можете использовать [Aspose.Slides for Andorid через Java](https://products.aspose.com/slides/android-java/), который представляет собой API PowerPoint для приложений Android для преобразования PPSM в HTML. После этого с помощью API обработки документов [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) вы можете конвертировать HTML в ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSM в ODT рендеринг в Android" %}}
1. Откройте файл PPSM, используя класс [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте PPSM в HTML, используя [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument).
4. Сохраните документ в формате ODT, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) и установите Odt как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Slides for Android via Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) и [Aspose.Words для Andorid через Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) в вашем Приложения.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-text/" name="PPSM К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-odtm/" name="PPSM К ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-dotm/" name="PPSM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-ott/" name="PPSM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-dotx/" name="PPSM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-word/" name="PPSM К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-dot/" name="PPSM К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-wordml/" name="PPSM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-odtx/" name="PPSM К ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-odt/" name="PPSM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-rtf/" name="PPSM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/ppsm-to-flatopc/" name="PPSM К FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
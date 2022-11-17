---
title: Экспорт POWERPOINT в DOTX на Andorid через Java
description: Конвертируйте POWERPOINT в DOTX в мобильных приложениях без установки какого-либо программного обеспечения

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOTX
otherformats: ODT RTF DOT DOC DOCM DOTM DOCX FLATOPC WORDML OTT WORD TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг POWERPOINT в DOTX на Andorid через Java" h2="API форматов файлов для преобразования POWERPOINT в DOTX в приложениях Android независимо от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) позволяет управлять форматами файлов в приложениях Android. С помощью API-интерфейсов, предоставляемых в пакете, вы можете автоматизировать процесс преобразования PowerPoint POWERPOINT в Word DOTX в своих приложениях.
Вы можете преобразовать данный документ в два этапа. Вы можете использовать [Aspose.Slides for Andorid через Java](https://products.aspose.com/slides/android-java/), который представляет собой API PowerPoint для приложений Android для преобразования POWERPOINT в HTML. После этого с помощью API обработки документов [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) вы можете конвертировать HTML в DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POWERPOINT в DOTX рендеринг в Android" %}}
1. Откройте файл POWERPOINT, используя класс [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте POWERPOINT в HTML, используя [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument).
4. Сохраните документ в формате DOTX, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) и установите Dotx как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Slides for Android via Java](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) и [Aspose.Words для Andorid через Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) в вашем Приложения.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
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
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-odt/" name="PPTX К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-rtf/" name="PPTX К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-dot/" name="PPTX К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-dotx/" name="PPTX К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-dotxm/" name="PPTX К DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-dotm/" name="PPTX К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-dotxx/" name="PPTX К DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-flatopc/" name="PPTX К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-wordml/" name="PPTX К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-ott/" name="PPTX К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-word/" name="PPTX К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pptx-to-text/" name="PPTX К TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
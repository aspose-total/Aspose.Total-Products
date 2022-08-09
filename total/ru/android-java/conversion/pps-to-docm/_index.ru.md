---
title: Экспорт PPS в DOCM на Andorid через Java
description: Конвертируйте PPS в DOCM в мобильных приложениях без установки какого-либо программного обеспечения
url: /ru/android-java/conversion/pps-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCM
otherformats: OTT DOTM FLATOPC DOT RTF DOC TEXT DOCX WORDML WORD DOTX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг PPS в DOCM на Andorid через Java" h2="API форматов файлов для преобразования PPS в DOCM в приложениях Android независимо от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/) позволяет управлять форматами файлов в приложениях Android. С помощью API-интерфейсов, предоставляемых в пакете, вы можете автоматизировать процесс преобразования PowerPoint PPS в Word DOCM в своих приложениях.
Вы можете преобразовать данный документ в два этапа. Вы можете использовать [Aspose.Slides for Andorid через Java](https://products.aspose.com/slides/android-java/), который представляет собой API PowerPoint для приложений Android для преобразования PPS в HTML. После этого с помощью API обработки документов [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/) вы можете конвертировать HTML в DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPS в DOCM рендеринг в Android" %}}
1. Откройте файл PPS, используя класс [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте PPS в HTML, используя [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument).
4. Сохраните документ в формате DOCM, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int)) и установите Docm как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Slides для Android через Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) и [Aspose.Words для Andorid через Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) в вашем Приложения.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-ott/" name="PPS К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-dotm/" name="PPS К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-flatopc/" name="PPS К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-dot/" name="PPS К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-rtf/" name="PPS К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-docm/" name="PPS К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-text/" name="PPS К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-docmx/" name="PPS К DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-wordml/" name="PPS К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-word/" name="PPS К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-dotx/" name="PPS К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/pps-to-odt/" name="PPS К ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
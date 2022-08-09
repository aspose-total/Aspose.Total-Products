---
title: Экспорт POTM в TEXT на Andorid через Java
description: Конвертируйте POTM в TEXT в мобильных приложениях без установки какого-либо программного обеспечения
url: /ru/android-java/conversion/potm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: TEXT
otherformats: OTT DOCX DOCM FLATOPC ODT DOTX DOTM DOC RTF WORDML WORD DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг POTM в TEXT на Andorid через Java" h2="API форматов файлов для преобразования POTM в TEXT в приложениях Android независимо от Microsoft PowerPoint или Word." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/) позволяет управлять форматами файлов в приложениях Android. С помощью API-интерфейсов, предоставляемых в пакете, вы можете автоматизировать процесс преобразования PowerPoint POTM в Word TEXT в своих приложениях.
Вы можете преобразовать данный документ в два этапа. Вы можете использовать [Aspose.Slides for Andorid через Java](https://products.aspose.com/slides/android-java/), который представляет собой API PowerPoint для приложений Android для преобразования POTM в HTML. После этого с помощью API обработки документов [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/) вы можете конвертировать HTML в TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM в TEXT рендеринг в Android" %}}
1. Откройте файл POTM, используя класс [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте POTM в HTML, используя [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument).
4. Сохраните документ в формате TEXT, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) и установите Text как СохранитьФормат
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Slides для Android через Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) и [Aspose.Words для Andorid через Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) в вашем Приложения.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
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
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-ott/" name="POTM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-textx/" name="POTM К TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-textm/" name="POTM К TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-flatopc/" name="POTM К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-odt/" name="POTM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-dotx/" name="POTM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-dotm/" name="POTM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-text/" name="POTM К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-rtf/" name="POTM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-wordml/" name="POTM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-word/" name="POTM К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/potm-to-dot/" name="POTM К DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Конвертировать POTM в DOTX через Java
description: Java API для экспорта POTM в DOTX без использования Microsoft Word или PowerPoint
url: /ru/java/conversion/potm-to-dotx/
family: total
platformtag: net
feature: conversion
informat: POTMM
outformat: DOTX
otherformats: WORDML ODT DOTX OTT DOT WORD RTF FLATOPC DOTM TEXT DOTXX DOTXM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать POTM в DOTX через Java" h2="Локальный Java API для преобразования PowerPoint POTM в DOTX в любых приложениях Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Java](https://products.aspose.com/total/java/) Библиотеки автоматизации форматов файлов позволяют разработчикам Java автоматизировать процесс пакетного преобразования PowerPoint POTM в Word DOTX. Преобразование документа представляет собой двухэтапный процесс и включает использование двух API. Мы будем использовать [Aspose.Slides for Java](https://products.aspose.com/slides/java/), который представляет собой API PowerPoint для работы с презентациями и управления ими для преобразования POTM в HTML. После этого с помощью многофункционального API обработки текста [Aspose.Words for Java](https://products.aspose.com/words/java/) мы преобразуем HTML в DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как преобразовать POTM в DOTX через Java" %}}
1. Откройте файл POTM, используя класс [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте POTM в HTML, используя [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Dotxument](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument).
4. Сохраните документ в формате DOTX, используя метод [save](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Для преобразования файлов POTM в DOTX вы можете легко использовать Aspose.Total для Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) и включите библиотеки в ваш pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Используя API, вы также можете выполнить преобразование файла POTM в DOTX с водяным знаком. Чтобы добавить водяной знак в документ DOTX, вы можете сначала преобразовать файл POTM в HTML и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл HTML с помощью класса [Dotxument](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-word/" name="POTM К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-dotx/" name="POTM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-odt/" name="POTM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-ott/" name="POTM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-rtf/" name="POTM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-flatopc/" name="POTM К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-wordml/" name="POTM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-dotxm/" name="POTM К DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-text/" name="POTM К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-dotxx/" name="POTM К DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-dotm/" name="POTM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/potm-to-dot/" name="POTM К DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
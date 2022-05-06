---
title: Конвертировать POT в DOTX через Java
description: Java API для экспорта POT в DOTX без использования Microsoft Word или PowerPoint
url_ignore: /ru/java/conversion/pot-to-dotx/
family: total
platformtag: net
feature: conversion
informat: POT
outformat: DOTX
otherformats: RTF DOTX ODT WORD WORDML FLATOPC DOT OTT DOTXM TEXT DOTXX DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать POT в DOTX через Java" h2="Локальный Java API для преобразования PowerPoint POT в DOTX в любых приложениях Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Java](https://products.aspose.com/total/java/) Библиотеки автоматизации форматов файлов позволяют разработчикам Java автоматизировать процесс пакетного преобразования PowerPoint POT в Word DOTX. Преобразование документа представляет собой двухэтапный процесс и включает использование двух API. Мы будем использовать [Aspose.Slides for Java](https://products.aspose.com/slides/java/), который представляет собой API PowerPoint для работы с презентациями и управления ими для преобразования POT в HTML. После этого с помощью многофункционального API обработки текста [Aspose.Words for Java](https://products.aspose.com/words/java/) мы преобразуем HTML в DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как преобразовать POT в DOTX через Java" %}}
1. Откройте файл POT, используя класс [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте POT в HTML, используя [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате DOTX, используя метод [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Для преобразования файлов POT в DOTX вы можете легко использовать Aspose.Total для Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) и включите библиотеки в ваш pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Используя API, вы также можете выполнить преобразование файла POT в DOTX с водяным знаком. Чтобы добавить водяной знак в документ DOTX, вы можете сначала преобразовать файл POT в HTML и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл HTML с помощью класса [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-word/" name="POT К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-dotx/" name="POT К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-odt/" name="POT К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-ott/" name="POT К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-rtf/" name="POT К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-flatopc/" name="POT К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-wordml/" name="POT К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-dotxm/" name="POT К DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-text/" name="POT К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-dotxx/" name="POT К DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-dotm/" name="POT К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pot-to-dot/" name="POT К DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
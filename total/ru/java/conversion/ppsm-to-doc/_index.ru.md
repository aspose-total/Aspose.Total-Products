---
title: Конвертировать PPSM в DOC через Java
description: Java API для экспорта PPSM в DOC без использования Microsoft Word или PowerPoint
url_ignore: /ru/java/conversion/ppsm-to-doc/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: DOC
otherformats: DOTX DOCX WORD ODT DOT OTT FLATOPC DOTM TEXT DOCM WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать PPSM в DOC через Java" h2="Локальный Java API для преобразования PowerPoint PPSM в DOC в любых приложениях Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Java](https://products.aspose.com/total/java/) Библиотеки автоматизации форматов файлов позволяют разработчикам Java автоматизировать процесс пакетного преобразования PowerPoint PPSM в Word DOC. Преобразование документа представляет собой двухэтапный процесс и включает использование двух API. Мы будем использовать [Aspose.Slides for Java](https://products.aspose.com/slides/java/), который представляет собой API PowerPoint для работы с презентациями и управления ими для преобразования PPSM в HTML. После этого с помощью многофункционального API обработки текста [Aspose.Words for Java](https://products.aspose.com/words/java/) мы преобразуем HTML в DOC.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как преобразовать PPSM в DOC через Java" %}}
1. Откройте файл PPSM, используя класс [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте PPSM в HTML, используя [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) и установите Html как SaveFormat
3. Загрузите преобразованный файл HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате DOC, используя метод [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Для преобразования файлов PPSM в DOC вы можете легко использовать Aspose.Total для Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и включите библиотеки в ваш pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Используя API, вы также можете выполнить преобразование файла PPSM в DOC с водяным знаком. Чтобы добавить водяной знак в документ DOC, вы можете сначала преобразовать файл PPSM в HTML и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-word/" name="PPSM К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-dotx/" name="PPSM К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-odt/" name="PPSM К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-ott/" name="PPSM К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-rtf/" name="PPSM К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-flatopc/" name="PPSM К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-wordml/" name="PPSM К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-docm/" name="PPSM К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-text/" name="PPSM К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-docx/" name="PPSM К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-dotm/" name="PPSM К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsm-to-dot/" name="PPSM К DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
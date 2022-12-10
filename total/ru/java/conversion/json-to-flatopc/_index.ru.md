---
title: Преобразование формата JSON в FLATOPC через Java
description: Разобрать JSON в FLATOPC на Java без использования Microsoft Word
url_ignore: /ru/java/conversion/json-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: EPUB ODT PCL WORD RTF DOC DOCM DOTX DOT MOBI PS FLATOPC WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в FLATOPC через Java" h2="Локальный Java API для преобразования JSON в FLATOPC без использования Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете конвертировать JSON в FLATOPC в своих Java-приложениях в два этапа. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в PDF. На втором этапе вы можете конвертировать PDF в FLATOPC с помощью API обработки текстов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в FLATOPC через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) и [Сохранить](https://reference.aspose.com/ ячейки/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате FLATOPC, используя [Сохранить](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Кроме того, API позволяет вам устанавливать параметры макета для вашего JSON при анализе JSON в FLATOPC с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в FLATOPC через Java" %}}
Используя API, вы также можете преобразовать JSON в FLATOPC с водяным знаком. Чтобы добавить водяной знак в документ FLATOPC, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в FLATOPC. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-flatopc/" name="JSON К FLAКPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-docm/" name="JSON К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-word/" name="JSON К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-wordml/" name="JSON К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-odt/" name="JSON К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-rtf/" name="JSON К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-doc/" name="JSON К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-mobi/" name="JSON К MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-ott/" name="JSON К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-dotx/" name="JSON К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-pcl/" name="JSON К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-dot/" name="JSON К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-epub/" name="JSON К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-ps/" name="JSON К PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
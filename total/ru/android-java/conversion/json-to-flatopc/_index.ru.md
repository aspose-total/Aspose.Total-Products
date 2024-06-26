---
title: Преобразование формата JSON в FLATOPC в Android через Java
description: Разобрать JSON в FLATOPC на Java без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: DOC PS CHM DOTX MOBI WORDML PCL OTT ODT DOT DOCM WORD EPUB RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование формата JSON в FLATOPC в приложениях для Android" h2="Преобразование JSON в FLATOPC в приложениях Android без использования Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете преобразовать JSON в FLATOPC в своих приложениях для Android в два этапа. Во-первых, с помощью мощного API обработки электронных таблиц [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) вы можете преобразовать JSON в PDF. На втором этапе вы можете преобразовать PDF в FLATOPC с помощью API обработки текстов [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Оба API относятся к семейству продуктов [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в FLATOPC в Android через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и прочитайте действительные данные JSON из файла.
2. Импортируйте файл JSON на лист, используя класс [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) и [Save](https://reference.aspose.com/ячейки/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) в формате PDF
3. Загрузите документ PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате FLATOPC, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions). )) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://releases.aspose.com/total/java/) и установить библиотеки в ваше приложение.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Установите макет и конвертируйте формат JSON в FLATOPC в Android через Java" %}}
Кроме того, API позволяет вам устанавливать параметры макета для вашего формата JSON при анализе JSON в FLATOPC с помощью [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование формата JSON в FLATOPC с водяным знаком в Android через Java" %}}
С помощью API вы также можете конвертировать JSON в FLATOPC с водяным знаком. Чтобы добавить водяной знак в ваш документ FLATOPC, вы можете сначала преобразовать файл JSON в PDF и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PDF с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), создайте экземпляр TextWatermarkOptions и установите его свойства, вызвать метод Watermark.setText и передать текст водяного знака и объект TextWatermarkOptions. После добавления водяного знака вы можете сохранить документ в FLATOPC.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
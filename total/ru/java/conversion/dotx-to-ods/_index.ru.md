---
title: Java API для преобразования DOTX в ODS
description: Преобразование DOTX в ODS через Java без использования Microsoft Word или Microsoft Excel
url: /ru/java/conversion/dotx-to-ods/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: ODS
otherformats: XLAM XLTX XLSX TSV XLT EXCEL ODS FODS SXC DIF XLTM XLS XLSM XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать DOTX в ODS через Java" h2="Локальный Java API для преобразования DOTX в ODS без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование DOTX в ODS с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. Используя многофункциональный API для обработки и преобразования документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете экспортировать DOTX в HTML. После этого, используя [Aspose.Cells for Java](https://products.aspose.com/cells/java/), вы можете конвертировать HTML в ODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования DOTX в ODS" %}}
1. Откройте файл DOTX, используя класс [Dotxument](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument).
2. Преобразуйте DOTX в HTML, используя [Сохранить](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате ODS с помощью [Сохранить](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.Words для Java](https://dotxs.aspose.com/words/java/installation/) и [Aspose.Cells для Java](https://dotxs.aspose.com/cells/java/ установка/) в вашем pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Перед преобразованием DOTX в ODS вы можете удалить неиспользуемую информацию из документа DOTX через [Aspose.Words for Java](https://products.aspose.com/words/java/). Иногда может потребоваться удалить неиспользуемую или повторяющуюся информацию, чтобы уменьшить размер выходного документа и время обработки. Класс [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) позволяет указать параметры очистки документа. Чтобы удалить повторяющиеся стили или просто неиспользуемые стили или списки из документа, вы можете использовать метод [Очистка](https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup()). Вы можете использовать [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) и [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) для обнаружения и удаления стилей, помеченных как «неиспользуемые».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotxument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Удалить неиспользуемую информацию из документа DOTX через Java" %}}
После преобразования DOTX в ODS [Aspose.Cells for Java](https://products.aspose.com/cells/java/) позволяет сохранить документ для потоковой передачи. Если вам нужно сохранить файлы в поток, вам следует создать объект FileOutputStream, а затем [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) файл в этот объект Stream, вызвав метод сохранения [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) объект. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsm/" name="DOTX К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlt/" name="DOTX К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-ods/" name="DOTX К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-tsv/" name="DOTX К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xls/" name="DOTX К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsb/" name="DOTX К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-fods/" name="DOTX К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-dif/" name="DOTX К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xltx/" name="DOTX К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlam/" name="DOTX К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xlsx/" name="DOTX К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-xltm/" name="DOTX К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-sxc/" name="DOTX К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/dotx-to-excel/" name="DOTX К EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
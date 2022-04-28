---
title: Java API для преобразования DOCX в XLSM
description: Преобразование DOCX в XLSM через Java без использования Microsoft Word или Microsoft Excel
url: /ru/java/conversion/docx-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLSM
otherformats: XLSM SXC XLT XLSM XLSB XLTX XLS EXCEL TSV ODS XLAM XLTM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать DOCX в XLSM через Java" h2="Локальный Java API для преобразования DOCX в XLSM без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование DOCX в XLSM с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. Используя многофункциональный API для обработки и преобразования документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете экспортировать DOCX в HTML. После этого, используя [Aspose.Cells for Java](https://products.aspose.com/cells/java/), вы можете конвертировать HTML в XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для преобразования DOCX в XLSM" %}}
1. Откройте файл DOCX, используя класс [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document).
2. Преобразуйте DOCX в HTML, используя [Сохранить](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате XLSM с помощью [Сохранить](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.Words для Java](https://docxs.aspose.com/words/java/installation/) и [Aspose.Cells для Java](https://docxs.aspose.com/cells/java/ установка/) в вашем pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Перед преобразованием DOCX в XLSM вы можете удалить неиспользуемую информацию из документа DOCX через [Aspose.Words for Java](https://products.aspose.com/words/java/). Иногда может потребоваться удалить неиспользуемую или повторяющуюся информацию, чтобы уменьшить размер выходного документа и время обработки. Класс [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) позволяет указать параметры очистки документа. Чтобы удалить повторяющиеся стили или просто неиспользуемые стили или списки из документа, вы можете использовать метод [Очистка](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Вы можете использовать [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) и [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) для обнаружения и удаления стилей, помеченных как «неиспользуемые».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Удалить неиспользуемую информацию из документа DOCX через Java" %}}
После преобразования DOCX в XLSM [Aspose.Cells for Java](https://products.aspose.com/cells/java/) позволяет сохранить документ для потоковой передачи. Если вам нужно сохранить файлы в поток, вам следует создать объект FileOutputStream, а затем [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) файл в этот объект Stream, вызвав метод сохранения [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) объект. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsm/" name="DOCX К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlt/" name="DOCX К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-ods/" name="DOCX К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-tsv/" name="DOCX К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xls/" name="DOCX К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsb/" name="DOCX К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-fods/" name="DOCX К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-dif/" name="DOCX К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xltx/" name="DOCX К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlam/" name="DOCX К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xlsx/" name="DOCX К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-xltm/" name="DOCX К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-sxc/" name="DOCX К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/docx-to-excel/" name="DOCX К EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
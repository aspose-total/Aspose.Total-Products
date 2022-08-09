---
title: Android API для преобразования DOCM в TSV
description: Преобразование DOCM в TSV в Android через Java без использования Microsoft Word или Microsoft Excel
url: /ru/android-java/conversion/docm-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: TSV
otherformats: EXCEL XLSB SXC XLS XLTX XLSM ODS FODS XLSX DIF XLT XLTM CSV XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование DOCM в TSV в приложениях для Android" h2="Экспорт DOCM в TSV на Android через Java без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/), вы можете интегрировать функцию преобразования DOCM в TSV в свои приложения для Android. Во-первых, вы можете конвертировать DOCM в HTML с помощью многофункционального API для обработки и преобразования документов [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/). После этого, используя [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), вы можете конвертировать HTML в TSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для преобразования DOCM в TSV" %}}
1. Откройте файл DOCM, используя класс [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument).
2. Преобразуйте DOCM в HTML, используя [Сохранить](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате TSV с помощью [Сохранить](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установить [Aspose.Cells для Android через Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) и [Aspose.Words для Android через Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить неиспользуемую информацию из документа DOCM в Android через Java" %}}
Перед преобразованием DOCM в TSV вы можете удалить неиспользуемую информацию из документа DOCM с помощью [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/). Иногда может потребоваться удалить неиспользуемую или повторяющуюся информацию, чтобы уменьшить размер выходного документа и время обработки. Класс [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) позволяет указать параметры очистки документа. Чтобы удалить повторяющиеся стили или просто неиспользуемые стили или списки из документа, вы можете использовать метод [Очистка](https://reference.aspose.com/words/java/com.aspose.words/Docmument#cleanup()). Вы можете использовать [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) и [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) для обнаружения и удаления стилей, помеченных как «неиспользуемые».
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранить файл TSV для потоковой передачи на Android через Java" %}}
После преобразования DOCM в TSV [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/) позволяет сохранить документ для потоковой передачи. Если вам нужно сохранить файлы в поток, вам следует создать объект FileOutputStream, а затем [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) файл в этот объект Stream, вызвав метод сохранения [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) объект.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-excel/" name="DOCM К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xlsb/" name="DOCM К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-sxc/" name="DOCM К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xls/" name="DOCM К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xltx/" name="DOCM К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xlsm/" name="DOCM К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-ods/" name="DOCM К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-fods/" name="DOCM К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xlsx/" name="DOCM К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-dif/" name="DOCM К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xlt/" name="DOCM К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xltm/" name="DOCM К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-tsv/" name="DOCM К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docm-to-xlam/" name="DOCM К XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Android API для преобразования DOCX в DIF
description: Преобразование DOCX в DIF в Android через Java без использования Microsoft Word или Microsoft Excel
url: /ru/android-java/conversion/docx-to-dif/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: DIF
otherformats: XLT XLSB FODS XLSM XLSX XLAM XLS EXCEL XLTX CSV TSV ODS SXC XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование DOCX в DIF в приложениях для Android" h2="Экспорт DOCX в DIF на Android через Java без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/), вы можете интегрировать функцию преобразования DOCX в DIF в свои приложения для Android. Во-первых, вы можете конвертировать DOCX в HTML с помощью многофункционального API для обработки и преобразования документов [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/). После этого, используя [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), вы можете конвертировать HTML в DIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для преобразования DOCX в DIF" %}}
1. Откройте файл DOCX, используя класс [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument).
2. Преобразуйте DOCX в HTML, используя [Сохранить](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате DIF с помощью [Сохранить](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установить [Aspose.Cells для Android через Java](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) и [Aspose.Words для Android через Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить неиспользуемую информацию из документа DOCX в Android через Java" %}}
Перед преобразованием DOCX в DIF вы можете удалить неиспользуемую информацию из документа DOCX с помощью [Aspose.Words для Android через Java](https://products.aspose.com/words/android-java/). Иногда может потребоваться удалить неиспользуемую или повторяющуюся информацию, чтобы уменьшить размер выходного документа и время обработки. Класс [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) позволяет указать параметры очистки документа. Чтобы удалить повторяющиеся стили или просто неиспользуемые стили или списки из документа, вы можете использовать метод [Очистка](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). Вы можете использовать [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) и [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) для обнаружения и удаления стилей, помеченных как «неиспользуемые».
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранить файл DIF для потоковой передачи на Android через Java" %}}
После преобразования DOCX в DIF [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/) позволяет сохранить документ для потоковой передачи. Если вам нужно сохранить файлы в поток, вам следует создать объект FileOutputStream, а затем [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) файл в этот объект Stream, вызвав метод сохранения [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) объект.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xlt/" name="DOCX К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xlsb/" name="DOCX К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-fods/" name="DOCX К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xlsm/" name="DOCX К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xlsx/" name="DOCX К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xlam/" name="DOCX К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xls/" name="DOCX К XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-excel/" name="DOCX К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xltx/" name="DOCX К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-dif/" name="DOCX К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-tsv/" name="DOCX К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-ods/" name="DOCX К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-sxc/" name="DOCX К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/docx-to-xltm/" name="DOCX К XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Преобразование PDF в ODS в Android через Java
description: Рендеринг PDF в ODS на Android через Java API без использования Microsoft Excel или Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: ODS
otherformats: XLTX CSV DIF TSV TXT XLTM SXC XLSM FODS XLT EXCEL XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг PDF в ODS на Android через Java" h2="Преобразование PDF в ODS в приложениях для Android без использования Microsoft<sup>&reg;</sup> Excel или Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете интегрировать функцию преобразования PDF в ODS в свои приложения для Android в два этапа. Во-первых, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), вы можете конвертировать PDF в XLSX. Во-вторых, вы можете конвертировать XLSX в ODS с помощью мощного API обработки электронных таблиц [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Оба API относятся к семейству продуктов [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для рендеринга PDF в ODS" %}}
1. Откройте файл PDF, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PDF в XLSX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате ODS, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://releases.aspose.com/total/java/) и установите [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) и [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-через-java-установку/) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP файла PDF в Android через Java" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) позволяет получить доступ к метаданным XMP файла PDF. Чтобы получить метаданные, создайте объект [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document), откройте входной файл PDF и используйте [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--), чтобы получить метаданные.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Защитите ODS-документ в Android с помощью Java" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) поддерживает защиту файла ODS в зависимости от ваших потребностей. Чтобы защитить свой документ, вы можете использовать метод [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-ods.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
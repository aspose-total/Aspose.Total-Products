---
title: Java API для преобразования ODT в CSV или с помощью бесплатного онлайн-конвертера
description: Преобразование ODT в CSV через Java без использования Microsoft Word или Microsoft Excel или онлайн. Быстро протестируйте бесплатный онлайн-конвертер ODT в CSV, прежде чем интегрировать код. 
url_ignore: /ru/java/conversion/odt-to-csv/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: CSV
otherformats: XLTM XLSM XLSX XLT XLS DIF EXCEL SXC ODS XLSB FODS XLAM TSV XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Конвертировать ODT в CSV через Java или онлайн-приложение" h2="Локальный Java API для преобразования ODT в CSV без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование ODT в CSV с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. Используя многофункциональный API для обработки и преобразования документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете экспортировать ODT в HTML. После этого, используя [Aspose.Cells for Java](https://products.aspose.com/cells/java/), вы можете конвертировать HTML в CSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования ODT в CSV" %}}
1. Откройте файл ODT, используя класс [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Преобразуйте ODT в HTML, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате CSV с помощью [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.Words для Java](https://docs.aspose.com/words/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/installation/) в вашем pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Бесплатный онлайн-конвертер ODT в CSV</h3>

<iframe title="Онлайн-инструмент от csv до odt долларов" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=csv&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Перед преобразованием ODT в CSV вы можете удалить неиспользуемую информацию из документа ODT через [Aspose.Words for Java](https://products.aspose.com/words/java/). Иногда может потребоваться удалить неиспользуемую или повторяющуюся информацию, чтобы уменьшить размер выходного документа и время обработки. Класс [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) позволяет указать параметры очистки документа. Чтобы удалить повторяющиеся стили или просто неиспользуемые стили или списки из документа, вы можете использовать метод [Очистка](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Вы можете использовать [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) и [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) для обнаружения и удаления стилей, помеченных как «неиспользуемые».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Удалить неиспользуемую информацию из документа ODT через Java" %}}
После преобразования ODT в CSV [Aspose.Cells for Java](https://products.aspose.com/cells/java/) позволяет сохранить документ для потоковой передачи. Если вам нужно сохранить файлы в поток, вам следует создать объект FileOutputStream, а затем [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) файл в этот объект Stream, вызвав метод сохранения [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) объект. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
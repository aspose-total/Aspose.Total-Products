---
title: Java API для рендеринга MD в TSV
description: Экспорт MD в TSV через Java API без использования Microsoft Excel или Adobe Reader
url: /ru/java/conversion/md-to-tsv/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TSV
otherformats: XLT XLSB EXCEL XLAM TXT TSV SXC FODS XLSM DIF ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт MD в TSV через Java" h2="Преобразование файла MD в TSV с помощью локального Java API в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете интегрировать функцию преобразования MD в TSV в свои Java-приложения в два этапа. Во-первых, с помощью [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) вы можете преобразовать MD в XLSX. На втором этапе вы можете конвертировать XLSX в TSV с помощью API программирования электронных таблиц [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать файл MD в TSV через Java" %}}
1. Откройте файл MD, используя класс [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте MD в XLSX, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) метод
3. Загрузите документ XLSX с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате TSV, используя [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Cells для Java](https://docs.aspose.com/cells/java/ установка/) в вашем pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Если ваш документ MD защищен паролем, вы не сможете преобразовать его в TSV без пароля. Используя API, вы можете сначала открыть защищенный документ, используя действующий пароль, а затем преобразовать его. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного MD в TSV через Java" %}}
При преобразовании файла MD в TSV вы также можете добавить водяной знак в выходной формат файла TSV. Чтобы добавить водяной знак, создайте новую рабочую книгу, чтобы открыть преобразованный файл XLSX. Выберите рабочий лист через его индекс, создайте форму и используйте ее функцию addTextEffect, установите цвета, прозрачность и многое другое. После этого вы можете сохранить документ XLSX в формате TSV с водяным знаком. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-dif/" name="MD К DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xltx/" name="MD К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-md/" name="MD К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-fods/" name="MD К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xltm/" name="MD К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-excel/" name="MD К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xlsm/" name="MD К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xlam/" name="MD К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xlt/" name="MD К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xlsb/" name="MD К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ods/" name="MD К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-sxc/" name="MD К SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
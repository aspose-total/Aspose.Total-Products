---
title: Преобразование XLSM в DOC с помощью Java или с помощью бесплатного онлайн-конвертера
description: Java API для экспорта XLSM в DOC или онлайн с использованием Excel или Word или онлайн. Быстро протестируйте бесплатный онлайн-конвертер CSV в DOC, прежде чем интегрировать код.
url_ignore: /ru/java/conversion/xlsm-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOC
otherformats: DOCX POWERPOINT PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта XLSM в DOC или онлайн" h2="Локальный Java API для экспорта XLSM в DOC или онлайн, не полагаясь на Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование XLSM в DOC — это двухэтапный процесс. Сначала вы будете использовать API [Aspose.Cells для Java](https://products.aspose.com/cells/java) для преобразования данного документа XLSM в PDF, а затем с помощью [Aspose.Pdf для Java](https://products.aspose.com/pdf/java) API, вы можете легко конвертировать PDF-документ в DOC. Оба API входят в набор библиотек автоматизации форматов файлов [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать XLSM в DOC через Java API" %}}
1. Откройте файл XLSM с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте XLSM в PDF и установите для SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Сохраните документ в формате DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод и установите Doc как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Онлайн-конвертер XLSM в DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlsm" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsm-to-doc/">Попробуйте наше бесплатное приложение для преобразования XLSM в DOC</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-docx/" name="XLSM К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-pptx/" name="XLSM К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-powerpoint/" name="XLSM К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-word/" name="XLSM К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
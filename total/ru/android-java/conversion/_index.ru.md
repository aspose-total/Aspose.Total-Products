---
title: Преобразование документов через Android API 
url: /ru/android-java/conversion/
description: Преобразование форматов Word, Excel, PowerPoint, HTML, PDF и изображений с помощью API преобразования Android. Android конвертирует Office docx, xlsx, pptx в PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование документов с помощью Android API" h2="Конвертируйте Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, изображения и другие форматы с помощью Aspose.Total для Android через Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) предоставляет решение для преобразования и управления документами для приложений Android, не полагаясь на какое-либо другое программное обеспечение. Программисты могут легко автоматизировать решение для управления документами и манипулирования ими, интегрируя API в новые разработанные приложения или в существующие приложения. Интегрируя API, программист может легко добавлять функциональные возможности для создания, редактирования или преобразования документов различных форматов в приложении. API PDF Converter в Android обрабатывает такие случаи преобразования, как Office DOCX, XLSX, PPTX в PDF или наоборот. Кроме того, несколько случаев, когда API имеет дело, перечислены ниже, и несколько ссылок приведены для соответствующих случаев преобразования. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Конвертировать PDF в CSV" %}}
Total Android API поддерживает преобразование PDF в Excel XLSX и CSV. Это двухэтапный процесс. Два общих API [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/) и Aspose.Cells для Android через Java](https://products.aspose.com/ячейки/android-java/). Процесс заключается в том, что вы можете сначала конвертировать PDF в формат Excel XLSX, а затем XLSX в CSV. Более подробно, загрузите PDF-файл через класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и отобразите в XLSX через [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Затем загрузите обработанный документ XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и вызовите [save](https://reference.aspose.com). /cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод.

{{% blocks/products/pf/feature-page-code h3="Android - Преобразование PDF в Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Преобразование Excel в Word" %}}
Android API также обрабатывает преобразование Excel. Процесс таков: загрузите файл EXCEL XLSX с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и преобразуйте EXCEL в PDF, сначала установив SaveFormat на AUTO. Затем загрузите сохраненный файл PDF с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) и вызовите [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) для сохранения документа в формате Word DOC/DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Преобразование Excel в Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование POWERPOINT в HTML и MHTML" %}}
Android Total API работает с различными форматами, включая файлы PowerPoint, поэтому может преобразовывать презентации в HTML и MHTML. Процесс таков: загрузите файл POWERPOINT PPT/PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) и вызовите [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) для преобразования POWERPOINT в HTML. Кроме того, теперь загрузите преобразованный HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и вызовите [save](https://reference.aspose.com/cells/java/com.aspose.cells/) для преобразования MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android – Преобразование слайдов PowerPoint в HTML и MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}
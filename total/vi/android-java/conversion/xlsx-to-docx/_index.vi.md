---
title: Xuất XLSX sang DOCX trong Android
description: API Android để chuyển đổi XLSX sang DOCX mà không cần sử dụng Microsoft Word
url: /vi/android-java/conversion/xlsx-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: DOCX
otherformats: POWERPOINT PPTX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất XLSX sang DOCX trên Android qua Java" h2="Chuyển đổi XLSX sang DOCX trong Ứng dụng Android của bạn mà không cần sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/) là một gói API tự động hóa tệp mạnh mẽ. Bằng cách sử dụng hai trong số các API của nó, bạn có thể tích hợp tính năng chuyển đổi XLSX sang DOCX bên trong các ứng dụng Android của mình. Trong bước đầu tiên, bạn có thể xuất XLSX sang PDF bằng cách sử dụng [Aspose.Cells dành cho Android qua Java](https://products.aspose.com/cells/android-java/). Sau đó, bằng cách sử dụng [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển đổi PDF sang DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để xuất XLSX sang DOCX" %}}
1. Mở tệp XLSX bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi XLSX sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Lưu tài liệu sang định dạng DOCX bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) phương pháp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF cho Android qua Java](https://docxs.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells cho Android qua Java](https://docxs.aspose.com/cells / java / aspose-cells-for-android-via-java-install / # install-asposecells-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thuộc tính tùy chỉnh khỏi tệp XLSX trong Android qua Java" %}}
Ngoài chuyển đổi tài liệu, [Aspose.Cells cho Android qua Java](https://products.aspose.com/cells/android-java/) cũng cung cấp rất nhiều tính năng khác. Trước quá trình chuyển đổi, bạn có thể xóa các thuộc tính tùy chỉnh của tài liệu XLSX. Để xóa thuộc tính tùy chỉnh, hãy gọi phương thức [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove (java.lang.String)) và chuyển tên của thuộc tính tài liệu sẽ bị xóa.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/xlsx-to-powerpoint/" name="XLSX Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/xlsx-to-pptx/" name="XLSX Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/xlsx-to-docx/" name="XLSX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/xlsx-to-word/" name="XLSX Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi CSV sang DOCX bằng Java
description: Java API để xuất CSV sang DOCX bằng Excel hoặc Word
url_ignore: /vi/java/conversion/csv-to-docx/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOCXX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để xuất CSV sang DOCX" h2="Trên API Premise Java để Xuất CSV sang DOCX mà không cần dựa vào Microsoft Excel & reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Đưa CSV sang DOCX là một quá trình gồm hai bước. Trước tiên, bạn sẽ sử dụng API [Aspose.Cells for Java](https://products.aspose.com/cells/java) để chuyển đổi tài liệu CSV đã cho sang PDF, sau đó bằng cách sử dụng [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, bạn có thể dễ dàng chuyển đổi tài liệu PDF của mình sang DOCX. Cả hai API đều nằm trong bộ sưu tập các thư viện tự động hóa định dạng tệp [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi CSV sang DOCX qua Java API" %}}
1. Mở tệp CSV bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi CSV sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Lưu tài liệu sang định dạng DOCX bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) và đặt Docx là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-docxx/" name="CSV Đến DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-pptx/" name="CSV Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-powerpoint/" name="CSV Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/csv-to-word/" name="CSV Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi FODS sang WORD bằng Java
description: Java API để xuất FODS sang WORD bằng Excel hoặc Word
url_ignore: /vi/java/conversion/fods-to-word/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: WORD
otherformats: PPTX WORD WORDX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để xuất FODS sang WORD" h2="Trên API Premise Java để Xuất FODS sang WORD mà không cần dựa vào Microsoft Excel & reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Đưa FODS sang WORD là một quá trình gồm hai bước. Trước tiên, bạn sẽ sử dụng API [Aspose.Cells for Java](https://products.aspose.com/cells/java) để chuyển đổi tài liệu FODS đã cho sang PDF, sau đó bằng cách sử dụng [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, bạn có thể dễ dàng chuyển đổi tài liệu PDF của mình sang WORD. Cả hai API đều nằm trong bộ sưu tập các thư viện tự động hóa định dạng tệp [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi FODS sang WORD qua Java API" %}}
1. Mở tệp FODS bằng lớp [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi FODS sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Lưu tài liệu sang định dạng WORD bằng [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) và đặt Word là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-wordx/" name="FODS Đến WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-pptx/" name="FODS Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-powerpoint/" name="FODS Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-word/" name="FODS Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
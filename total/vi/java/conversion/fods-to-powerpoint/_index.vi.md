---
title: Chuyển đổi FODS sang POWERPOINT bằng Java hoặc với Trình chuyển đổi trực tuyến miễn phí
description: Java API để xuất FODS sang POWERPOINT bằng Excel hoặc Word hoặc trực tuyến. Kiểm tra trình chuyển đổi trực tuyến CSV sang DOC miễn phí một cách nhanh chóng trước khi tích hợp mã.
url_ignore: /vi/java/conversion/fods-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: POWERPOINT WORD PPTX POWERPOINTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java để xuất FODS sang POWERPOINT hoặc trực tuyến" h2="Trên API Premise Java để Xuất FODS sang POWERPOINT mà không cần dựa vào Microsoft Excel & reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Đưa FODS sang POWERPOINT là một quá trình gồm hai bước. Trước tiên, bạn sẽ sử dụng API [Aspose.Cells for Java](https://products.aspose.com/cells/java) để chuyển đổi tài liệu FODS đã cho sang PDF, sau đó bằng cách sử dụng [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, bạn có thể dễ dàng chuyển đổi tài liệu PDF của mình sang POWERPOINT. Cả hai API đều nằm trong bộ sưu tập các thư viện tự động hóa định dạng tệp [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cách chuyển đổi FODS sang POWERPOINT qua Java API" %}}
1. Mở tệp FODS bằng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Chuyển đổi FODS sang PDF và đặt SaveFormat thành TỰ ĐỘNG
3. Tải tệp PDF đã chuyển đổi bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Lưu tài liệu sang định dạng POWERPOINT bằng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) và đặt Powerpoint là SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn phải sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://releases.aspose.com/total/java/) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Công cụ chuyển đổi trực tuyến từ FODS sang POWERPOINT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=fods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/fods-to-pptx/">Hãy dùng thử ứng dụng miễn phí của chúng tôi để chuyển đổi FODS sang POWERPOINT</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-powerpointx/" name="FODS Đến POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-pptx/" name="FODS Đến PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-powerpoint/" name="FODS Đến POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/fods-to-word/" name="FODS Đến WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
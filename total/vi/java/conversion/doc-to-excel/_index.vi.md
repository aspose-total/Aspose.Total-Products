---
title: Java API để chuyển đổi DOC sang EXCEL
description: Chuyển đổi DOC sang EXCEL qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/java/conversion/doc-to-excel/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: XLSX
otherformats: EXCEL SXC DIF XLTX XLSX TSV XLAM XLTM FODS ODS XLT XLSM EXCEL XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi DOC sang EXCEL qua Java" h2="Trên API Premise Java để chuyển đổi DOC sang EXCEL mà không cần sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi DOC sang EXCEL qua [Aspose.Total cho Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể xuất DOC sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells cho Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C ++ để chuyển đổi DOC sang EXCEL" %}}
1. Mở tệp DOC bằng lớp [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Chuyển đổi DOC sang HTML bằng cách sử dụng [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng EXCEL bằng cách sử dụng [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.lang.String,% 20com.aspose.cells). Phương thức SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm [Aspose.Words dành cho Java](https://docs.aspose.com/words/java/installation/) và [Aspose.Cells dành cho Java](https://docs.aspose.com/cells/java/ cài đặt /) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}](](](](](
Trước khi chuyển đổi DOC sang EXCEL, bạn có thể xóa thông tin không sử dụng khỏi Tài liệu DOC qua [Aspose.Words for Java](https://products.aspose.com/words/java/). Đôi khi bạn có thể cần phải loại bỏ thông tin không sử dụng hoặc trùng lặp để giảm kích thước của tài liệu đầu ra và thời gian xử lý. Lớp [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) cho phép bạn chỉ định các tùy chọn để làm sạch tài liệu. Để xóa các kiểu trùng lặp hoặc chỉ các kiểu hoặc danh sách không sử dụng khỏi tài liệu, bạn có thể sử dụng phương pháp [Dọn dẹp](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup ()). Bạn có thể sử dụng [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) và [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) thuộc tính để phát hiện và xóa các kiểu được đánh dấu là "không sử dụng".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}](](](
{{% blocks/products/pf/feature-page-section  h2="Xóa thông tin không sử dụng khỏi tài liệu DOC qua Java" %}}
Sau khi chuyển đổi DOC sang EXCEL, [Aspose.Cells cho Java](https://products.aspose.com/cells/java/) cho phép bạn lưu tài liệu của mình vào luồng. Nếu bạn cần lưu tệp vào Luồng thì bạn nên tạo một đối tượng FileOutputStream rồi [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.io). OutputStream,% 20com.aspose.cells.SaveOptions)) tệp vào đối tượng Luồng đó bằng cách gọi phương thức lưu của [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) vật. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsm/" name="DOC Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlt/" name="DOC Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-ods/" name="DOC Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-tsv/" name="DOC Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xls/" name="DOC Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsb/" name="DOC Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-fods/" name="DOC Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-dif/" name="DOC Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltx/" name="DOC Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlam/" name="DOC Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xlsx/" name="DOC Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-xltm/" name="DOC Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-sxc/" name="DOC Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/doc-to-excel/" name="DOC Đến EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
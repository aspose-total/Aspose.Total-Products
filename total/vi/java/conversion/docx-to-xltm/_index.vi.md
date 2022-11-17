---
title: Java API để chuyển đổi DOCX sang XLTM
description: Chuyển đổi DOCX sang XLTM qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url_ignore: /vi/java/conversion/docx-to-xltm/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLTM
otherformats: XLTX XLSX DIF EXCEL XLT XLSM TSV ODS XLSB SXC XLAM XLS FODS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi DOCX sang XLTM qua Java" h2="Trên API Premise Java để chuyển đổi DOCX sang XLTM mà không cần sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi DOCX sang XLTM qua [Aspose.Total for Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể xuất DOCX sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells for Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi DOCX sang XLTM" %}}
1. Mở tệp DOCX bằng lớp [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Chuyển đổi DOCX sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng XLTM bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)).SaveOptions)) Phương thức 
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm [Aspose.Words dành for Java](https://docxs.aspose.com/words/java/installation/) và [Aspose.Cells for Java](https://docxs.aspose.com/cells/java/installation/) trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Trước khi chuyển đổi DOCX sang XLTM, bạn có thể xóa thông tin không sử dụng khỏi Tài liệu DOCX qua [Aspose.Words for Java](https://products.aspose.com/words/java/). Đôi khi bạn có thể cần phải loại bỏ thông tin không sử dụng hoặc trùng lặp để giảm kích thước của tài liệu đầu ra và thời gian xử lý. Lớp [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) cho phép bạn chỉ định các tùy chọn để làm sạch tài liệu. Để xóa các kiểu trùng lặp hoặc chỉ các kiểu hoặc danh sách không sử dụng khỏi tài liệu, bạn có thể sử dụng phương pháp [Dọn dẹp](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Bạn có thể sử dụng [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) và [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) thuộc tính để phát hiện và xóa các kiểu được đánh dấu là "không sử dụng".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Xóa thông tin không sử dụng khỏi tài liệu DOCX qua Java" %}}
Sau khi chuyển đổi DOCX sang XLTM, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) cho phép bạn lưu tài liệu của mình vào luồng. Nếu bạn cần lưu tệp vào Luồng thì bạn nên tạo một đối tượng FileOutputStream rồi [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) tệp vào đối tượng Luồng đó bằng cách gọi phương thức lưu của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) vật. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xlsm/" name="DOCX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xlt/" name="DOCX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-ods/" name="DOCX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-tsv/" name="DOCX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xls/" name="DOCX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xlsb/" name="DOCX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-fods/" name="DOCX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-dif/" name="DOCX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xltx/" name="DOCX Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xlam/" name="DOCX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xlsx/" name="DOCX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-xltm/" name="DOCX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-sxc/" name="DOCX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/docx-to-excel/" name="DOCX Đến EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
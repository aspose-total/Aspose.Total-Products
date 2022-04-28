---
title: Chuyển đổi định dạng DOTM sang JSON qua Java
description: Chuyển đổi định dạng DOTM sang JSON qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/java/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng DOTM sang JSON qua Java" h2="Trên API Premise Java để chuyển đổi DOTM sang JSON mà không cần sử dụng Microsoft<sup>&reg;</sup> Word hoặc Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi định dạng DOTM sang JSON thông qua [Aspose.Total cho Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Java](https://products.aspose.com/words/java/), bạn có thể xuất DOTM sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells cho Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng DOTM sang JSON qua Java" %}}
1. Mở tệp DOTM bằng lớp [Dotmument](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Chuyển đổi DOTM sang HTML bằng cách sử dụng [Save](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng JSON bằng cách sử dụng [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,% 20com.aspose.cells). Phương thức SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu DOTM đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions. Ví dụ mã sau đây cho thấy cách thử mở tài liệu được mã hóa bằng mật khẩu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOTM được bảo vệ sang định dạng JSON qua Java" %}}
Trong khi chuyển đổi DOTM sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để đặt phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, tạo Phạm vi dữ liệu được xuất bằng phương thức Cells.createRange, gọi phương thức JsonUtility.exportRangeToJson với các tham chiếu của Range & ExportRangeToJsonOptions và ghi dữ liệu chuỗi JSON vào tệp qua Phương thức BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xlam/" name="DOTM Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xlt/" name="DOTM Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-csv/" name="DOTM Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xlsx/" name="DOTM Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-fods/" name="DOTM Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xltm/" name="DOTM Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xlsm/" name="DOTM Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xltx/" name="DOTM Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-ods/" name="DOTM Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-xlsb/" name="DOTM Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-excel/" name="DOTM Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-sxc/" name="DOTM Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-tsv/" name="DOTM Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/dotm-to-dif/" name="DOTM Đến DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
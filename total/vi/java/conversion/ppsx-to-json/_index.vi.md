---
title: Chuyển đổi định dạng PPSX sang JSON qua Java
description: Chuyển đổi định dạng PPSX sang JSON qua Java mà không cần sử dụng Microsoft Excel hoặc PowerPoint
url: /vi/java/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng PPSX sang JSON qua Java" h2="Trên API Premise Java để xuất PPSX sang JSON mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi PPSX sang định dạng JSON qua [Aspose.Total cho Java](https://products.aspose.com/total/java/) là một quy trình đơn giản gồm hai bước. Trong bước đầu tiên, bạn có thể xuất PPSX sang HTML bằng cách sử dụng [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Thứ hai, bằng cách sử dụng [Aspose.Cells cho Java](https://products.aspose.com/cells/java/), bạn có thể chuyển đổi HTML sang JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng PPSX sang JSON qua Java" %}}
1. Mở tệp PPSX bằng lớp [Trình bày](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Chuyển đổi PPSX sang HTML bằng cách sử dụng [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Phương thức ISaveOptions-)
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng JSON bằng cách sử dụng [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.lang.String,% 20com.aspose.cells). Phương thức SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Java trực tiếp từ dự án dựa trên [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và bao gồm các thư viện trong pom.xml của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Yêu cầu chuyển đổi" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu PPSX đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi PPSX được bảo vệ sang định dạng JSON qua Java" %}}
Trong khi chuyển đổi PPSX sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để đặt phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, tạo Phạm vi dữ liệu được xuất bằng phương thức Cells.createRange, gọi phương thức JsonUtility.exportRangeToJson với các tham chiếu của Range & ExportRangeToJsonOptions và ghi dữ liệu chuỗi JSON vào tệp qua Phương thức BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-doc/" name="PPSX Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-docm/" name="PPSX Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-docx/" name="PPSX Đến DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dot/" name="PPSX Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dotm/" name="PPSX Đến DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-dotx/" name="PPSX Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-odt/" name="PPSX Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-ott/" name="PPSX Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-rtf/" name="PPSX Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-text/" name="PPSX Đến TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-word/" name="PPSX Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/ppsx-to-wordml/" name="PPSX Đến WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
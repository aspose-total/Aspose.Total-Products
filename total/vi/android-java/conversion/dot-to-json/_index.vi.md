---
title: Chuyển đổi định dạng DOT sang JSON trong Android qua Java
description: Phân tích cú pháp định dạng DOT sang JSON trong Android thông qua Java mà không cần sử dụng Microsoft Word hoặc Excel
url: /vi/android-java/conversion/dot-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: JSON
otherformats: XLAM XLSB XLTM ODS XLT TSV SXC EXCEL FODS DIF XLTX CSV XLS XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng DOT sang JSON trong Android qua Java" h2="Thiết kế các ứng dụng Android để xuất DOT sang JSON mà không cần sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> Word hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi định dạng DOT sang JSON trong Ứng dụng Android của mình qua [Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/). Bằng cách sử dụng API chuyển đổi và thao tác tài liệu [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/), bạn có thể xuất DOT sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells cho Android qua Java](https://products.aspose.com/cells/android-java/), bạn có thể chuyển đổi HTML sang JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng DOT sang JSON trong Android" %}}
1. Mở tệp DOT bằng lớp [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
2. Chuyển đổi DOT sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng JSON bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt thư viện trong ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOT được bảo vệ sang định dạng JSON trong Android qua Java" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu DOT đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. API cho phép bạn mở tài liệu được mã hóa bằng cách chuyển mật khẩu chính xác vào đối tượng LoadOptions. Ví dụ mã sau đây cho thấy cách mở một tài liệu được mã hóa bằng mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOT sang JSON trong Range trong Android qua Java" %}}
Trong khi chuyển đổi DOT sang JSON, bạn cũng có thể đặt dải ô thành định dạng JSON đầu ra của mình. Để thiết lập phạm vi, bạn có thể mở HTML đã chuyển đổi bằng cách sử dụng lớp Workbook, tạo Phạm vi dữ liệu được xuất bằng phương thức Cells.createRange, gọi phương thức JsonUtility.exportRangeToJson với các tham chiếu của Range & ExportRangeToJsonOptions và ghi dữ liệu chuỗi JSON vào tệp qua Phương thức BufferedWriter.write.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlam/" name="DOT Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlsb/" name="DOT Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xltm/" name="DOT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-ods/" name="DOT Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlt/" name="DOT Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-tsv/" name="DOT Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-sxc/" name="DOT Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-excel/" name="DOT Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-fods/" name="DOT Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-dif/" name="DOT Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xltx/" name="DOT Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-csv/" name="DOT Đến CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xls/" name="DOT Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlsm/" name="DOT Đến XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
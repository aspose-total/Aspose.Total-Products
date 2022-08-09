---
title: API Android để chuyển đổi DOTX sang EXCEL
description: Chuyển đổi DOTX sang EXCEL trong Android qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/android-java/conversion/dotx-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: XLSX
otherformats: XLTX FODS XLAM XLSM SXC DIF XLSB XLS ODS TSV XLTM XLT XLSX CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOTX sang EXCEL trong các ứng dụng Android" h2="Xuất DOTX sang EXCEL trong Android qua Java mà không sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> Word hoặc Microsoft <sup> <sup>&reg;</sup>; </sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/), bạn có thể tích hợp tính năng chuyển đổi DOTX sang EXCEL bên trong các ứng dụng Android của mình. Trước tiên, bạn có thể chuyển đổi DOTX sang HTML bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/). Sau đó, bằng cách sử dụng [Aspose.Cells cho Java](https://products.aspose.com/cells/android-java/), bạn có thể chuyển đổi HTML sang EXCEL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để chuyển đổi DOTX sang EXCEL" %}}
1. Mở tệp DOTX bằng lớp [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Chuyển đổi DOTX sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng EXCEL bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Cells cho Android qua Java](https://dotxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) và [Aspose.Words dành cho Android qua Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thông tin không sử dụng khỏi tài liệu DOTX trong Android qua Java" %}}
Trước khi chuyển đổi DOTX sang EXCEL, bạn có thể xóa thông tin không sử dụng khỏi Tài liệu DOTX qua [Aspose.Words dành cho Android qua Java](https://products.aspose.com/words/android-java/). Đôi khi bạn có thể cần phải loại bỏ thông tin không sử dụng hoặc trùng lặp để giảm kích thước của tài liệu đầu ra và thời gian xử lý. Lớp [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) cho phép bạn chỉ định các tùy chọn để làm sạch tài liệu. Để xóa các kiểu trùng lặp hoặc chỉ các kiểu hoặc danh sách không sử dụng khỏi tài liệu, bạn có thể sử dụng phương pháp [Dọn dẹp](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup ()). Bạn có thể sử dụng [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) và [UnusedBuiltinStyles](https://reference.aspose.com/words/java) để phát hiện và xóa các kiểu được đánh dấu là "không sử dụng".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp EXCEL để phát trực tuyến trong Android qua Java" %}}
Sau khi chuyển đổi DOTX sang EXCEL, [Aspose.Cells dành cho Android qua Java](https://products.aspose.com/cells/android-java/) cho phép bạn lưu tài liệu của mình vào luồng. Nếu bạn cần lưu tệp vào Luồng thì bạn nên tạo một đối tượng FileOutputStream và sau đó [lưu](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.io. OutputStream,% 20com.aspose.cells.SaveOptions)) tệp vào đối tượng Luồng đó bằng cách gọi phương thức lưu của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sự vật.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xltx/" name="DOTX Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-fods/" name="DOTX Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xlam/" name="DOTX Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xlsm/" name="DOTX Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-sxc/" name="DOTX Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-dif/" name="DOTX Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xlsb/" name="DOTX Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xls/" name="DOTX Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-ods/" name="DOTX Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-tsv/" name="DOTX Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xltm/" name="DOTX Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xlt/" name="DOTX Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-xlsx/" name="DOTX Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotx-to-excel/" name="DOTX Đến EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
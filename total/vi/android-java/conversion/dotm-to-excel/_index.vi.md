---
title: API Android để chuyển đổi DOTM sang EXCEL
description: Chuyển đổi DOTM sang EXCEL trong Android qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/android-java/conversion/dotm-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLSX
otherformats: XLS SXC XLT XLSX TSV XLTM XLAM FODS XLSB XLTX XLSM CSV DIF ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOTM sang EXCEL trong các ứng dụng Android" h2="Xuất DOTM sang EXCEL trong Android qua Java mà không sử dụng Microsoft <sup>&reg;</sup> Word hoặc Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), bạn có thể tích hợp tính năng chuyển đổi DOTM sang EXCEL bên trong các ứng dụng Android của mình. Trước tiên, bạn có thể chuyển đổi DOTM sang HTML bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Sau đó, bằng cách sử dụng [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), bạn có thể chuyển đổi HTML sang EXCEL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để chuyển đổi DOTM sang EXCEL" %}}
1. Mở tệp DOTM bằng lớp [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Chuyển đổi DOTM sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng EXCEL bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Cells for Android via Java](https://dotms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) và [Aspose.Words for Android via Java](https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thông tin không sử dụng khỏi tài liệu DOTM trong Android qua Java" %}}
Trước khi chuyển đổi DOTM sang EXCEL, bạn có thể xóa thông tin không sử dụng khỏi Tài liệu DOTM qua [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Đôi khi bạn có thể cần phải loại bỏ thông tin không sử dụng hoặc trùng lặp để giảm kích thước của tài liệu đầu ra và thời gian xử lý. Lớp [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) cho phép bạn chỉ định các tùy chọn để làm sạch tài liệu. Để xóa các kiểu trùng lặp hoặc chỉ các kiểu hoặc danh sách không sử dụng khỏi tài liệu, bạn có thể sử dụng phương pháp [Dọn dẹp](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup ()). Bạn có thể sử dụng [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) và [UnusedBuiltinStyles](https://reference.aspose.com/words/java) để phát hiện và xóa các kiểu được đánh dấu là "không sử dụng".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp EXCEL để phát trực tuyến trong Android qua Java" %}}
Sau khi chuyển đổi DOTM sang EXCEL, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) cho phép bạn lưu tài liệu của mình vào luồng. Nếu bạn cần lưu tệp vào Luồng thì bạn nên tạo một đối tượng FileOutputStream và sau đó [lưu](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.io. OutputStream,% 20com.aspose.cells.SaveOptions)) tệp vào đối tượng Luồng đó bằng cách gọi phương thức lưu của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sự vật.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xls/" name="DOTM Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-sxc/" name="DOTM Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xlt/" name="DOTM Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xlsx/" name="DOTM Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-tsv/" name="DOTM Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xltm/" name="DOTM Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xlam/" name="DOTM Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-fods/" name="DOTM Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xlsb/" name="DOTM Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xltx/" name="DOTM Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-xlsm/" name="DOTM Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-excel/" name="DOTM Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-dif/" name="DOTM Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dotm-to-ods/" name="DOTM Đến ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
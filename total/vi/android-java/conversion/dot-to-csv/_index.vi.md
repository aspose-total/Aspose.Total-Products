---
title: API Android để chuyển đổi DOT sang CSV
description: Chuyển đổi DOT sang CSV trong Android qua Java mà không cần sử dụng Microsoft Word hoặc Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: CSV
otherformats: XLTX XLSX SXC TSV DIF EXCEL ODS XLSB FODS XLS XLTM XLAM XLSM XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi DOT sang CSV trong các ứng dụng Android" h2="Xuất DOT sang CSV trong Android qua Java mà không sử dụng Microsoft <sup>&reg;</sup> Word hoặc Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), bạn có thể tích hợp tính năng chuyển đổi DOT sang CSV bên trong các ứng dụng Android của mình. Trước tiên, bạn có thể chuyển đổi DOT sang HTML bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, giàu tính năng [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Sau đó, bằng cách sử dụng [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), bạn có thể chuyển đổi HTML sang CSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để chuyển đổi DOT sang CSV" %}}
1. Mở tệp DOT bằng lớp [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
2. Chuyển đổi DOT sang HTML bằng cách sử dụng [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String, com.aspose.words.SaveOptions) ) phương pháp
3. Tải tài liệu HTML bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng CSV bằng cách sử dụng [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.Cells for Android via Java](https://dots.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) và [Aspose.Words for Android via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Xóa thông tin không sử dụng khỏi tài liệu DOT trong Android qua Java" %}}
Trước khi chuyển đổi DOT sang CSV, bạn có thể xóa thông tin không sử dụng khỏi Tài liệu DOT qua [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Đôi khi bạn có thể cần phải loại bỏ thông tin không sử dụng hoặc trùng lặp để giảm kích thước của tài liệu đầu ra và thời gian xử lý. Lớp [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) cho phép bạn chỉ định các tùy chọn để làm sạch tài liệu. Để xóa các kiểu trùng lặp hoặc chỉ các kiểu hoặc danh sách không sử dụng khỏi tài liệu, bạn có thể sử dụng phương pháp [Dọn dẹp](https://reference.aspose.com/words/java/com.aspose.words/Dotument#cleanup ()). Bạn có thể sử dụng [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) và [UnusedBuiltinStyles](https://reference.aspose.com/words/java) để phát hiện và xóa các kiểu được đánh dấu là "không sử dụng".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp CSV để phát trực tuyến trong Android qua Java" %}}
Sau khi chuyển đổi DOT sang CSV, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) cho phép bạn lưu tài liệu của mình vào luồng. Nếu bạn cần lưu tệp vào Luồng thì bạn nên tạo một đối tượng FileOutputStream và sau đó [lưu](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.io. OutputStream,% 20com.aspose.cells.SaveOptions)) tệp vào đối tượng Luồng đó bằng cách gọi phương thức lưu của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sự vật.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xltx/" name="DOT Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlsx/" name="DOT Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-sxc/" name="DOT Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-tsv/" name="DOT Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-dif/" name="DOT Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-excel/" name="DOT Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-ods/" name="DOT Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlsb/" name="DOT Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-fods/" name="DOT Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xls/" name="DOT Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xltm/" name="DOT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlam/" name="DOT Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlsm/" name="DOT Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/dot-to-xlt/" name="DOT Đến XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
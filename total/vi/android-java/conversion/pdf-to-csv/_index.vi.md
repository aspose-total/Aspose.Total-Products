---
title: Chuyển đổi PDF sang CSV trong Android qua Java
description: Kết xuất PDF sang CSV trong Android thông qua API Java mà không cần sử dụng Microsoft Excel hoặc Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: CSV
otherformats: XLTX XLSM EXCEL TSV TXT XLSB MD DIF XLAM XLTM FODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PDF sang CSV trong Android qua Java" h2="Chuyển đổi PDF sang CSV trong các ứng dụng Android mà không yêu cầu Microsoft <sup>&reg;</sup> Excel hoặc Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi PDF sang CSV trong các ứng dụng Android của mình trong quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển PDF sang XLSX. Thứ hai, bạn có thể chuyển đổi XLSX sang CSV bằng cách sử dụng API xử lý bảng tính mạnh mẽ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Cả hai API đều thuộc họ sản phẩm [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để hiển thị PDF sang CSV" %}}
1. Mở tệp PDF bằng lớp [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi PDF sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng CSV bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total for Android via Java trực tiếp từ [Maven](https://releases.aspose.com/total/java/) và cài đặt [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-install/) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [download](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP của tệp PDF trong Android qua Java" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) cho phép bạn truy cập siêu dữ liệu XMP của tệp PDF. Để lấy siêu dữ liệu, hãy tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở tệp PDF đầu vào và sử dụng [getMetadata ()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) thuộc tính để lấy siêu dữ liệu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Bảo vệ tài liệu CSV trong Android qua Java" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) hỗ trợ bảo vệ tệp CSV của bạn tùy theo nhu cầu của bạn. Để bảo vệ tài liệu của mình, bạn có thể sử dụng phương pháp [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook (java.lang.String)) của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) lớp.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-csv.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
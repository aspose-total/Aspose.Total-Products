---
title: Chuyển đổi SVG sang FODS trong Android qua Java
description: Kết xuất SVG sang FODS trong Android thông qua API Java mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/android-java/conversion/svg-to-fods/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: FODS
otherformats: MD CSV ODS XLSM XLT XLTM TXT TSV SXC EXCEL XLAM XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất SVG sang FODS trong Android qua Java" h2="Chuyển đổi SVG sang FODS trong các ứng dụng Android mà không yêu cầu Microsoft <sup> <sup>&reg;</sup>; </sup> Excel hoặc Adobe <sup> <sup>&reg;</sup>; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể tích hợp tính năng chuyển đổi SVG sang FODS trong các ứng dụng Android của mình trong quy trình hai bước. Thứ nhất, bằng cách sử dụng [Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/), bạn có thể chuyển SVG sang XLSX. Thứ hai, bạn có thể chuyển đổi XLSX sang FODS bằng cách sử dụng API xử lý bảng tính mạnh mẽ [Aspose.Cells cho Android qua Java](https://products.aspose.com/cells/android-java/). Cả hai API đều thuộc họ sản phẩm [Aspose.Total cho Android qua Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android để hiển thị SVG sang FODS" %}}
1. Mở tệp SVG bằng lớp [Tài liệu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Chuyển đổi SVG sang XLSX bằng cách sử dụng [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) phương pháp
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Lưu tài liệu sang định dạng FODS bằng cách sử dụng [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Bạn có thể dễ dàng sử dụng Aspose.Total cho Android qua Java trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) và cài đặt [Aspose.PDF cho Android qua Java](https://docs.aspose.com/pdf/androidjava/installation/) và [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-install/) trong các ứng dụng của bạn.

Ngoài ra, bạn có thể tải tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận siêu dữ liệu XMP của tệp SVG trong Android qua Java" %}}
[Aspose.PDF dành cho Android qua Java](https://products.aspose.com/pdf/android-java/) cho phép bạn truy cập siêu dữ liệu XMP của tệp SVG. Để lấy siêu dữ liệu, hãy tạo đối tượng [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) và mở tệp SVG đầu vào và sử dụng [getMetadata ()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) thuộc tính để lấy siêu dữ liệu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Bảo vệ tài liệu FODS trong Android qua Java" %}}
[Aspose.Cells cho Android qua Java](https://products.aspose.com/cells/android-java/) hỗ trợ bảo vệ tệp FODS của bạn tùy theo nhu cầu của bạn. Để bảo vệ tài liệu của mình, bạn có thể sử dụng phương pháp [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook (java.lang.String)) của [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) lớp.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-fods.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-md/" name="SVG Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-fods/" name="SVG Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-ods/" name="SVG Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-xlsm/" name="SVG Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-xlt/" name="SVG Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-xltm/" name="SVG Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-txt/" name="SVG Đến TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-tsv/" name="SVG Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-sxc/" name="SVG Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-excel/" name="SVG Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-xlam/" name="SVG Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/android-java/conversion/svg-to-xlsb/" name="SVG Đến XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
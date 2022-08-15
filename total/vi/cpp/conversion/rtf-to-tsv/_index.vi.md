---
title: Chuyển đổi RTF sang TSV trong C++
description: C++ API để chuyển đổi RTF sang TSV mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/cpp/conversion/rtf-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: TSV
otherformats: XLSB XLTM XLS DIF FODS XLTX XLSM ODS XLSX EXCEL XLT CSV XLAM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để chuyển đổi RTF sang TSV" h2="Xuất RTF sang TSV qua C++ mà không sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> Word hoặc Microsoft <sup> <sup>&reg;</sup>; </sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể bao gồm tính năng chuyển đổi RTF sang TSV trong các ứng dụng C++ của mình một cách dễ dàng. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, mạnh mẽ và dễ sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất RTF sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp/), bạn có thể chuyển đổi HTML sang TSV. Cả hai API đều nằm trong gói [Aspose.Total cho C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi RTF sang TSV" %}}
1. Mở tệp RTF bằng tham chiếu lớp [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
2. Chuyển đổi RTF sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string_saveformat)
3. Tải tài liệu HTML bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng TSV bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Truy cập Thuộc tính tài liệu RTF qua C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) cũng cho phép bạn truy cập các thuộc tính tài liệu của tệp RTF và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi. Để truy cập thuộc tính tài liệu, bạn có thể sử dụng [BuiltInRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_rtfument_properties) để lấy các thuộc tính tích hợp và [CustomRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_rtfument_properties) để lấy các thuộc tính tùy chỉnh. Ví dụ mã sau đây cho thấy cách liệt kê tất cả các thuộc tính tích hợp và tùy chỉnh trong một tài liệu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-rtfument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp TSV vào Luồng qua C++" %}}
Sau khi chuyển đổi RTF sang TSV, [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp/) cho phép bạn lưu tài liệu của mình vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) phương thức.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xlsb/" name="RTF Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xltm/" name="RTF Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xls/" name="RTF Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-dif/" name="RTF Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-fods/" name="RTF Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xltx/" name="RTF Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xlsm/" name="RTF Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-ods/" name="RTF Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xlsx/" name="RTF Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-excel/" name="RTF Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xlt/" name="RTF Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-tsv/" name="RTF Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-xlam/" name="RTF Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/rtf-to-sxc/" name="RTF Đến SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
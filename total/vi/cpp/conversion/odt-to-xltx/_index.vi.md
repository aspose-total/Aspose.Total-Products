---
title: Chuyển đổi ODT sang XLTX trong C++
description: C++ API để chuyển đổi ODT sang XLTX mà không cần sử dụng Microsoft Word hoặc Microsoft Excel
url: /vi/cpp/conversion/odt-to-xltx/
family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: XLTX
otherformats: XLTM TSV XLS XLSB FODS XLSM XLAM XLT ODS SXC DIF EXCEL XLSX CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để chuyển đổi ODT sang XLTX" h2="Xuất ODT sang XLTX qua C++ mà không sử dụng Microsoft <sup> <sup>&reg;</sup>; </sup> Word hoặc Microsoft <sup> <sup>&reg;</sup>; </sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể bao gồm tính năng chuyển đổi ODT sang XLTX trong các ứng dụng C++ của mình một cách dễ dàng. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, mạnh mẽ và dễ sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất ODT sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp/), bạn có thể chuyển đổi HTML sang XLTX. Cả hai API đều nằm trong gói [Aspose.Total cho C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi ODT sang XLTX" %}}
1. Mở tệp ODT bằng tham chiếu lớp [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
2. Chuyển đổi ODT sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string_saveformat)
3. Tải tài liệu HTML bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng XLTX bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Truy cập Thuộc tính tài liệu ODT qua C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) cũng cho phép bạn truy cập các thuộc tính tài liệu của tệp ODT và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi. Để truy cập thuộc tính tài liệu, bạn có thể sử dụng [BuiltInOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_odtument_properties) để lấy các thuộc tính tích hợp và [CustomOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_odtument_properties) để lấy các thuộc tính tùy chỉnh. Ví dụ mã sau đây cho thấy cách liệt kê tất cả các thuộc tính tích hợp và tùy chỉnh trong một tài liệu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-odtument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp XLTX vào Luồng qua C++" %}}
Sau khi chuyển đổi ODT sang XLTX, [Aspose.Cells cho C++](https://products.aspose.com/cells/cpp/) cho phép bạn lưu tài liệu của mình vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) phương thức.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xltm/" name="ODT Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-tsv/" name="ODT Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xls/" name="ODT Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xlsb/" name="ODT Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-fods/" name="ODT Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xlsm/" name="ODT Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xlam/" name="ODT Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xlt/" name="ODT Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-ods/" name="ODT Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-sxc/" name="ODT Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-dif/" name="ODT Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-excel/" name="ODT Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xlsx/" name="ODT Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/odt-to-xltx/" name="ODT Đến XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
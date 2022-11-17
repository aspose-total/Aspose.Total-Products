---
title: Chuyển đổi WORDML sang CSV trong C++
description: C++ API để chuyển đổi WORDML sang CSV mà không cần sử dụng Microsoft Word hoặc Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: CSV
otherformats: DIF FODS XLTX ODS XLAM EXCEL XLT SXC XLSX XLTM XLSM XLSB XLS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ để chuyển đổi WORDML sang CSV" h2="Xuất WORDML sang CSV qua C++ mà không sử dụng Microsoft <sup>&reg;</sup> Word hoặc Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể bao gồm tính năng chuyển đổi WORDML sang CSV trong các ứng dụng C++ của mình một cách dễ dàng. Bằng cách sử dụng API chuyển đổi và thao tác tài liệu phong phú, mạnh mẽ và dễ sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất WORDML sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), bạn có thể chuyển đổi HTML sang CSV. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi WORDML sang CSV" %}}
1. Mở tệp WORDML bằng tham chiếu lớp [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
2. Chuyển đổi WORDML sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string_saveformat)
3. Tải tài liệu HTML bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng CSV bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Truy cập Thuộc tính tài liệu WORDML qua C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) cũng cho phép bạn truy cập các thuộc tính tài liệu của tệp WORDML và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi. Để truy cập thuộc tính tài liệu, bạn có thể sử dụng [BuiltInWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordmlument_properties) để lấy các thuộc tính tích hợp và [CustomWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordmlument_properties) để lấy các thuộc tính tùy chỉnh. Ví dụ mã sau đây cho thấy cách liệt kê tất cả các thuộc tính tích hợp và tùy chỉnh trong một tài liệu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordmlument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu tệp CSV vào Luồng qua C++" %}}
Sau khi chuyển đổi WORDML sang CSV, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) cho phép bạn lưu tài liệu của mình vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) phương thức.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-dif/" name="WORDML Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-fods/" name="WORDML Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xltx/" name="WORDML Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-ods/" name="WORDML Đến ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xlam/" name="WORDML Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-excel/" name="WORDML Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xlt/" name="WORDML Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-sxc/" name="WORDML Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xlsx/" name="WORDML Đến XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xltm/" name="WORDML Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xlsm/" name="WORDML Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xlsb/" name="WORDML Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-xls/" name="WORDML Đến XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/wordml-to-tsv/" name="WORDML Đến TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
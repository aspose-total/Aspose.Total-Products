---
title: API C++ để chuyển đổi SVG sang XLAM
description: Chuyển đổi SVG sang XLAM thông qua API C++ mà không cần sử dụng Microsoft Excel hoặc Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: XLAM
otherformats: FODS XLTX EXCEL TSV DIF XLSB SXC XLSM XLT TXT MD XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất SVG sang XLAM trong các ứng dụng C++" h2="Chuyển đổi SVG sang XLAM trong các ứng dụng C++ gốc mà không yêu cầu Microsoft <sup>&reg;</sup> Excel hoặc Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi SVG sang XLAM trong C++ thông qua thư viện tự động định dạng tệp [Aspose.Total for C++](https://products.aspose.com/total/cpp/) là một quy trình đơn giản gồm hai bước. Trong bước đầu tiên, bạn có thể xuất SVG sang XLSX bằng cách sử dụng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), Sau đó, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API lập trình bảng tính, bạn có thể chuyển đổi XLSX thành XLAM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi SVG sang XLAM" %}}
1. Mở tệp SVG bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi SVG sang XLSX bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Tải tài liệu XLSX bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng XLAM bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận hoặc đặt thông tin tệp SVG thông qua C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) cũng cho phép bạn nhận thông tin về tài liệu SVG của mình và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi của mình. Để nhận thông tin cụ thể về tệp của tệp SVG, trước tiên bạn cần gọi phương thức [get_Info ()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) của [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) lớp. Khi đối tượng DocumentInfo được truy xuất, bạn có thể nhận các giá trị của các thuộc tính riêng lẻ. Hơn nữa, bạn cũng có thể thiết lập các thuộc tính bằng cách sử dụng các phương thức tương ứng của lớp DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu định dạng tệp XLAM để phát trực tuyến qua C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) cho phép lưu định dạng tệp XLAM vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi phương thức Lưu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlam-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-fods/" name="SVG Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-xltx/" name="SVG Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-excel/" name="SVG Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-tsv/" name="SVG Đến TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-dif/" name="SVG Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-xlsb/" name="SVG Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-sxc/" name="SVG Đến SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-xlsm/" name="SVG Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-xlt/" name="SVG Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-txt/" name="SVG Đến TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-md/" name="SVG Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/svg-to-xltm/" name="SVG Đến XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
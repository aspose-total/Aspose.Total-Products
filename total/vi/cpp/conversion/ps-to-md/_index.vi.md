---
title: API C++ để chuyển đổi PS sang MD
description: Chuyển đổi PS sang MD thông qua API C++ mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url: /vi/cpp/conversion/ps-to-md/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: MD
otherformats: XLAM DIF XLTX TXT XLTM EXCEL XLSM XLT FODS CSV XLSB ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất PS sang MD trong các ứng dụng C++" h2="Chuyển đổi PS sang MD trong các ứng dụng C++ gốc mà không yêu cầu Microsoft <sup> <sup>&reg;</sup>; </sup> Excel hoặc Adobe <sup> <sup>&reg;</sup>; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi PS sang MD trong C++ thông qua thư viện tự động định dạng tệp [Aspose.Total for C++](https://products.aspose.com/total/cpp/) là một quy trình đơn giản gồm hai bước. Trong bước đầu tiên, bạn có thể xuất PS sang XLSX bằng cách sử dụng [Aspose.PDF cho C++](https://products.aspose.com/pdf/cpp/), Sau đó, bằng cách sử dụng [Aspose.Cells cho C++]( https://products.aspose.com/cells/cpp/) API lập trình bảng tính, bạn có thể chuyển đổi XLSX thành MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi PS sang MD" %}}
1. Mở tệp PS bằng tham chiếu lớp [Tài liệu](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi PS sang XLSX bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Tải tài liệu XLSX bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng MD bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận hoặc đặt thông tin tệp PS thông qua C++" %}}
[Aspose.PDF cho C++](https://products.aspose.com/pdf/cpp/) cũng cho phép bạn nhận thông tin về tài liệu PS của mình và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi của mình. Để nhận thông tin cụ thể về tệp của tệp PS, trước tiên bạn cần gọi phương thức [get_Info ()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) của [Tài liệu](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) lớp. Khi đối tượng DocumentInfo được truy xuất, bạn có thể nhận các giá trị của các thuộc tính riêng lẻ. Hơn nữa, bạn cũng có thể thiết lập các thuộc tính bằng cách sử dụng các phương thức tương ứng của lớp DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu định dạng tệp MD để phát trực tuyến qua C++" %}}
[Aspose.Cells cho C++](https://products.aspose.com/cells/net/) cho phép lưu định dạng tệp MD vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi phương thức Lưu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-md-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xlam/" name="PS Đến XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-dif/" name="PS Đến DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xltx/" name="PS Đến XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-txt/" name="PS Đến TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xltm/" name="PS Đến XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-excel/" name="PS Đến EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xlsm/" name="PS Đến XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xlt/" name="PS Đến XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-fods/" name="PS Đến FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-md/" name="PS Đến MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-xlsb/" name="PS Đến XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/ps-to-ods/" name="PS Đến ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
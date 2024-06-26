---
title: API C++ để chuyển đổi TEX sang XLSM
description: Chuyển đổi TEX sang XLSM thông qua API C++ mà không cần sử dụng Microsoft Excel hoặc Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XLSM
otherformats: XLTM TXT SXC EXCEL ODS CSV XLAM XLT DIF XLTX TSV MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Kết xuất TEX sang XLSM trong các ứng dụng C++" h2="Chuyển đổi TEX sang XLSM trong các ứng dụng C++ gốc mà không yêu cầu Microsoft <sup>&reg;</sup> Excel hoặc Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Chuyển đổi TEX sang XLSM trong C++ thông qua thư viện tự động định dạng tệp [Aspose.Total for C++](https://products.aspose.com/total/cpp/) là một quy trình đơn giản gồm hai bước. Trong bước đầu tiên, bạn có thể xuất TEX sang XLSX bằng cách sử dụng [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), Sau đó, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API lập trình bảng tính, bạn có thể chuyển đổi XLSX thành XLSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ để chuyển đổi TEX sang XLSM" %}}
1. Mở tệp TEX bằng tham chiếu lớp [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Chuyển đổi TEX sang XLSX bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Tải tài liệu XLSX bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng XLSM bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh là `` nuget install Aspose.Total.Cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nhận hoặc đặt thông tin tệp TEX thông qua C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) cũng cho phép bạn nhận thông tin về tài liệu TEX của mình và cho phép bạn đưa ra quyết định sáng suốt trước quá trình chuyển đổi của mình. Để nhận thông tin cụ thể về tệp của tệp TEX, trước tiên bạn cần gọi phương thức [get_Info ()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) của [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) lớp. Khi đối tượng DocumentInfo được truy xuất, bạn có thể nhận các giá trị của các thuộc tính riêng lẻ. Hơn nữa, bạn cũng có thể thiết lập các thuộc tính bằng cách sử dụng các phương thức tương ứng của lớp DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lưu định dạng tệp XLSM để phát trực tuyến qua C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) cho phép lưu định dạng tệp XLSM vào luồng. Để lưu tệp vào một luồng, hãy tạo một đối tượng MemoryStream hoặc FileStream và lưu tệp vào đối tượng luồng đó bằng cách gọi [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) phương thức [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) của đối tượng. Chỉ định định dạng tệp mong muốn bằng cách sử dụng kiểu liệt kê [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) khi gọi phương thức Lưu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsm-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
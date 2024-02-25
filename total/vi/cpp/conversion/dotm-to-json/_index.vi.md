---
title: Chuyển đổi định dạng DOTM sang JSON trong C++
description: Xuất DOTM sang JSON bằng C++ mà không cần sử dụng Microsoft Excel hoặc Word

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng DOTM sang JSON thông qua C++" h2="Xuất DOTM sang JSON qua C++ mà không sử dụng Microsoft <sup>&reg;</sup> Word hoặc Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for C++](https://products.aspose.com/total/cpp/), bạn có thể chuyển đổi định dạng DOTM sang JSON trong các ứng dụng C++ của mình. Thứ nhất, bằng cách sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cpp/), bạn có thể xuất DOTM sang HTML. Sau đó, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), bạn có thể chuyển đổi HTML sang định dạng JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng DOTM sang JSON thông qua C++" %}}
1. Mở tệp DOTM bằng tham chiếu lớp [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
2. Chuyển đổi DOTM sang HTML bằng cách sử dụng hàm thành viên [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat)
3. Tải tài liệu HTML bằng cách sử dụng tham chiếu lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Lưu tài liệu sang định dạng JSON bằng hàm thành viên [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi DOTM được bảo vệ sang định dạng JSON qua C++" %}}
Sử dụng API, bạn cũng có thể mở tài liệu được bảo vệ bằng mật khẩu. Nếu tài liệu DOTM đầu vào của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó sang định dạng JSON mà không sử dụng mật khẩu. Để thực hiện việc này, hãy sử dụng quá tải hàm tạo đặc biệt, chấp nhận một đối tượng LoadOptions. Đối tượng này chứa thuộc tính Mật khẩu, thuộc tính chỉ định chuỗi mật khẩu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
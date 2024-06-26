---
title: Chuyển đổi định dạng JSON sang POTM qua C++
description: Phân tích cú pháp JSON thành POTM trong C++ mà không cần sử dụng Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTX OTP ODP PPT PPTM PPSM PPSX POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng JSON sang POTM qua C++" h2="API C++ để phân tích cú pháp JSON thành POTM mà không cần sử dụng Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi JSON thành POTM trong bất kỳ ứng dụng C++ nào bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), bạn có thể phân tích cú pháp JSON thành PPTX. Sau đó, bằng cách sử dụng [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), bạn có thể chuyển đổi PPTX sang POTM. Cả hai API đều nằm trong gói [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang POTM qua C++" %}}
1. Tạo đối tượng [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Lưu JSON dưới dạng PPTX bằng phương pháp [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Lưu tài liệu sang định dạng POTM bằng phương pháp [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành POTM thông qua C++" %}}
Trong khi phân tích cú pháp JSON thành POTM, bạn cũng có thể đặt kích thước của hàng và cột bằng cách tải JSON với lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Nếu bạn cần đặt cùng một chiều cao hàng cho tất cả các hàng trong trang tính, bạn có thể thực hiện bằng cách sử dụng [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) của bộ sưu tập [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Tương tự, để đặt cùng một chiều rộng cột cho tất cả các cột trong trang tính, hãy sử dụng phương pháp [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) của bộ sưu tập ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi định dạng JSON sang POTM với Watermark trong C++" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành POTM với hình mờ. Để thêm hình mờ vào tài liệu POTM của bạn, trước tiên bạn có thể phân tích cú pháp JSON thành PPTX và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PPTX mới được tạo bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), tải trang chiếu đầu tiên, Thêm một AutoShape của kiểu Hình chữ nhật, thêm TextFrame vào Hình chữ nhật, tạo đối tượng Đoạn văn cho khung văn bản, tạo đối tượng Portion cho đoạn văn, thêm hình mờ bằng cách sử dụng set_Text () và có thể lưu tài liệu vào POTM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
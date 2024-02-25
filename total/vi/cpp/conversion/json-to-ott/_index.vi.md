---
title: Chuyển đổi định dạng JSON sang OTT thông qua C++
description: C++ API t0 Phân tích cú pháp JSON thành OTT mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: OTT
otherformats: ODT DOCM EPUB PS PCL DOTX MOBI CHM RTF WORD WORDML DOT FLATOPC DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng JSON sang OTT thông qua C++" h2="Phân tích cú pháp JSON thành OTT trong các ứng dụng C++ mà không cần sử dụng Microsoft <sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for C++](https://products.aspose.com/total/cpp/), bạn có thể phân tích cú pháp JSON thành OTT trong các ứng dụng C++ của mình bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), bạn có thể xuất JSON sang PDF. Sau đó, bằng cách sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cppp/), bạn có thể chuyển đổi PDF sang OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON thành OTT trong C++" %}}
1. Tạo đối tượng [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Lưu JSON dưới dạng PDF bằng phương pháp [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Lưu tài liệu sang định dạng OTT bằng phương pháp [Lưu](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành OTT trong C++" %}}
Trong khi phân tích cú pháp JSON thành OTT, bạn cũng có thể đặt kích thước của hàng và cột bằng cách tải JSON với lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Nếu bạn cần đặt cùng một chiều cao hàng cho tất cả các hàng trong trang tính, bạn có thể thực hiện bằng cách sử dụng [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) của bộ sưu tập [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Tương tự, để đặt cùng một chiều rộng cột cho tất cả các cột trong trang tính, hãy sử dụng phương pháp [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) của bộ sưu tập ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi định dạng JSON thành OTT với Watermark trong C++" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành OTT với hình mờ. Để thêm hình mờ vào tài liệu OTT của bạn, trước tiên bạn có thể chuyển đổi JSON sang PDF và thêm hình mờ vào tài liệu đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), đặt các thuộc tính khác nhau cho hình mờ văn bản,
gọi phương thức SetText và chuyển văn bản & đối tượng watermark của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào OTT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
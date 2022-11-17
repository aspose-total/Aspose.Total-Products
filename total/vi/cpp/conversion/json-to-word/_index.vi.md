---
title: Chuyển đổi định dạng JSON sang WORD thông qua C++
description: C++ API t0 Phân tích cú pháp JSON thành WORD mà không cần sử dụng Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOC
otherformats: PS PCL DOCM WORDML FLATOPC OTT ODT MOBI CHM DOC DOT DOTX EPUB RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi định dạng JSON sang WORD thông qua C++" h2="Phân tích cú pháp JSON thành WORD trong các ứng dụng C++ mà không cần sử dụng Microsoft <sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for C++](https://products.aspose.com/total/cpp/), bạn có thể phân tích cú pháp JSON thành WORD trong các ứng dụng C++ của mình bằng hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), bạn có thể xuất JSON sang PDF. Sau đó, bằng cách sử dụng [Aspose.Words for C++](https://products.aspose.com/words/cppp/), bạn có thể chuyển đổi PDF sang WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON thành WORD trong C++" %}}
1. Tạo đối tượng [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Lưu JSON dưới dạng PDF bằng phương pháp [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Lưu tài liệu sang định dạng WORD bằng phương pháp [Lưu](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Total.Cpp ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [download](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục & chuyển đổi định dạng JSON thành WORD trong C++" %}}
Trong khi phân tích cú pháp JSON thành WORD, bạn cũng có thể đặt kích thước của hàng và cột bằng cách tải JSON với lớp [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Nếu bạn cần đặt cùng một chiều cao hàng cho tất cả các hàng trong trang tính, bạn có thể thực hiện bằng cách sử dụng [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) của bộ sưu tập [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Tương tự, để đặt cùng một chiều rộng cột cho tất cả các cột trong trang tính, hãy sử dụng phương pháp [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) của bộ sưu tập ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi định dạng JSON thành WORD với Watermark trong C++" %}}
Sử dụng API, bạn cũng có thể phân tích cú pháp JSON thành WORD với hình mờ. Để thêm hình mờ vào tài liệu WORD của bạn, trước tiên bạn có thể chuyển đổi JSON sang PDF và thêm hình mờ vào tài liệu đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), đặt các thuộc tính khác nhau cho hình mờ văn bản,
gọi phương thức SetText và chuyển văn bản & đối tượng watermark của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào WORD.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-ps/" name="JSON Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-pcl/" name="JSON Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-docm/" name="JSON Đến DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-wordml/" name="JSON Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-flatopc/" name="JSON Đến FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-ott/" name="JSON Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-odt/" name="JSON Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-mobi/" name="JSON Đến MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-word/" name="JSON Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-doc/" name="JSON Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-dot/" name="JSON Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-dotx/" name="JSON Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-epub/" name="JSON Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/cpp/conversion/json-to-rtf/" name="JSON Đến RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
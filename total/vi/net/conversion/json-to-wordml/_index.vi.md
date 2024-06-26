---
title: Chuyển đổi định dạng JSON sang WORDML qua .NET
description: Phân tích cú pháp JSON thành WORDML trong C# mà không cần sử dụng Microsoft Word
url_ignore: /vi/net/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: PS OTT FLATOPC DOCM EPUB RTF DOTX ODT PCL WORDML DOC WORD DOT MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang WORDML qua C#" h2="C# API để phân tích cú pháp JSON thành WORDML mà không sử dụng Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể phân tích cú pháp JSON thành WORDML trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai ứng dụng đơn giản các bước. Đầu tiên, bằng cách sử dụng [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể xuất JSON sang PDF. Sau đó, bằng cách sử dụng [Aspose.Words for .NET](https://products.aspose.com/words/net/), bạn có thể chuyển đổi PDF sang WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang WORDML qua C#" %}}
1. Tạo một đối tượng [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) và [Save](https://reference.aspose.com/cells/net/ aspose.cells.workbook/save/method/4) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng WORDML bằng phương pháp [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành WORDML qua C#" %}}
Trong khi phân tích cú pháp JSON thành WORDML, bạn cũng có thể đặt các tùy chọn bố cục cho JSON của mình bằng cách sử dụng [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp định dạng JSON thành WORDML với Watermark" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành WORDML với hình mờ. Để thêm hình mờ vào tài liệu WORDML của bạn, trước tiên bạn có thể phân tích cú pháp tệp JSON thành PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Document](https://reference.aspose.com/words/net/aspose.words/document), tạo một bản sao của TextWatermarkOptions và đặt các thuộc tính của nó, Gọi phương thức Watermark.SetText và chuyển văn bản & đối tượng watermark của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào WORDML. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
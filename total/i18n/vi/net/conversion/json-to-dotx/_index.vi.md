---
title: Chuyển đổi định dạng JSON sang DOTX qua .NET
description: Phân tích cú pháp JSON thành DOTX trong C # mà không cần sử dụng Microsoft Word
url: /vi/net/conversion/json-to-dotx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC PCL EPUB FLATOPC DOCM ODT WORDML DOTX WORD MOBI PS DOT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang DOTX qua C #" h2="C # API để phân tích cú pháp JSON thành DOTX mà không sử dụng Microsoft <sup> & reg; </sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total cho .NET] (https://products.aspose.com/total/net/), bạn có thể phân tích cú pháp JSON thành DOTX trong bất kỳ ứng dụng .NET, C #, ASP.NET và VB.NET nào trong hai ứng dụng đơn giản các bước. Đầu tiên, bằng cách sử dụng [Aspose.Cells cho .NET] (https://products.aspose.com/cells/net/), bạn có thể xuất JSON sang PDF. Sau đó, bằng cách sử dụng [Aspose.Words for .NET] (https://products.aspose.com/words/net/), bạn có thể chuyển đổi PDF sang DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang DOTX qua C #" %}}
1. Tạo một đối tượng [Workbook] (https://apireference.aspose.com/cells/net/aspose.cells/workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility] (https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) và [Save] (https://apireference.aspose.com/ cells / net / aspose.cells.workbook / save / method / 4) nó dưới dạng PDF
3. Tải tài liệu PDF bằng cách sử dụng lớp [Document] (https://apireference.aspose.com/words/net/aspose.words/document)
4. Lưu tài liệu sang định dạng DOTX bằng phương pháp [Lưu] (https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành DOTX qua C #" %}}
Trong khi phân tích cú pháp JSON thành DOTX, bạn cũng có thể đặt các tùy chọn bố cục cho JSON của mình bằng cách sử dụng [JsonLayoutOptions] (https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp định dạng JSON thành DOTX với Watermark" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành DOTX với hình mờ. Để thêm hình mờ vào tài liệu DOTX của bạn, trước tiên bạn có thể phân tích cú pháp tệp JSON thành PDF và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PDF mới được tạo bằng cách sử dụng lớp [Tài liệu] (https://apireference.aspose.com/words/net/aspose.words/document), tạo một bản sao của TextWatermarkOptions và đặt các thuộc tính của nó , Gọi phương thức Watermark.SetText và chuyển văn bản & đối tượng watermark của TextWatermarkOptions. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào DOTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-ott/" name="JSON Đến OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-flatopc/" name="JSON Đến FLAĐếnPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-ps/" name="JSON Đến PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-dotx/" name="JSON Đến DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-rtf/" name="JSON Đến RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-wordml/" name="JSON Đến WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-odt/" name="JSON Đến ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-word/" name="JSON Đến WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-epub/" name="JSON Đến EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-doc/" name="JSON Đến DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-dot/" name="JSON Đến DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-pcl/" name="JSON Đến PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-mobi/" name="JSON Đến MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-docm/" name="JSON Đến DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi định dạng JSON sang SVGZ qua .NET
description: Phân tích cú pháp JSON thành SVGZ bằng C# mà không sử dụng phụ thuộc của bên thứ ba
url: /vi/net/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE WMF DXF TGA SVGZ PSD WMZ DICOM JPEG2000 EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi Định dạng JSON sang SVGZ qua C#" h2="API C# để phân tích cú pháp JSON thành SVGZ mà không sử dụng phụ thuộc của bên thứ ba" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total cho .NET](https://products.aspose.com/total/net/), bạn có thể phân tích cú pháp JSON thành SVGZ trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai ứng dụng đơn giản các bước. Đầu tiên, bằng cách sử dụng [Aspose.Cells cho .NET](https://products.aspose.com/cells/net/), bạn có thể xuất JSON sang JPEG. Sau đó, bằng cách sử dụng [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), bạn có thể chuyển đổi JPEG thành SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi Định dạng JSON sang SVGZ qua C#" %}}
1. Tạo đối tượng [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) mới và đọc dữ liệu JSON từ tệp
2. Chuyển đổi JSON sang JPEG bằng phương pháp [Lưu](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Tải tài liệu JPEG bằng cách sử dụng lớp [Hình ảnh](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Lưu tài liệu sang định dạng SVGZ bằng phương pháp [Lưu](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.Total '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.Total ''.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành SVGZ qua C#" %}}
Trong khi phân tích cú pháp JSON thành SVGZ, bạn cũng có thể đặt các tùy chọn bố cục cho JSON của mình bằng [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Định dạng JSON thành SVGZ với Hình mờ" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành SVGZ với hình mờ trong tài liệu SVGZ của mình. Để thêm hình mờ, trước tiên bạn có thể kết xuất tài liệu JSON của mình thành JPEG và thêm hình mờ vào đó. Để trình diễn thao tác, bạn có thể tải hình ảnh JPEG đã chuyển đổi của mình, thêm các phép biến đổi bằng cách sử dụng một đối tượng thuộc lớp Ma trận và vẽ một chuỗi làm hình mờ trên bề mặt hình ảnh bằng cách sử dụng [Đồ họa](https://apireference.aspose.com/imaging/ net / aspose.imaging / graphics) phương thức lớp '[DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) phương thức. Sau khi thêm hình mờ vào đó, bạn có thể lưu JPEG dưới dạng SVGZ. Dưới đây là một ví dụ mã minh họa cách thêm hình mờ đường chéo vào tài liệu của bạn. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn chuyển đổi khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-wmz/" name="JSON Đến WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-dicom/" name="JSON Đến DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-psd/" name="JSON Đến PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-jpeg2000/" name="JSON Đến JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-tga/" name="JSON Đến TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-emz/" name="JSON Đến EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-svgz/" name="JSON Đến SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-wmf/" name="JSON Đến WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-image/" name="JSON Đến IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/vi/net/conversion/json-to-dxf/" name="JSON Đến DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi định dạng JSON sang TGA qua .NET
description: Phân tích cú pháp JSON thành TGA bằng C# mà không sử dụng phụ thuộc của bên thứ ba
url_ignore: /vi/net/conversion/json-to-tga/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: TGA
otherformats: EMZ PSD IMAGE TGA DXF WMZ WMF JPEG2000 SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi Định dạng JSON sang TGA qua C#" h2="API C# để phân tích cú pháp JSON thành TGA mà không sử dụng phụ thuộc của bên thứ ba" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bằng cách sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể phân tích cú pháp JSON thành TGA trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai ứng dụng đơn giản các bước. Đầu tiên, bằng cách sử dụng [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể xuất JSON sang JPEG. Sau đó, bằng cách sử dụng [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), bạn có thể chuyển đổi JPEG thành TGA.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi Định dạng JSON sang TGA qua C#" %}}
1. Tạo đối tượng [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) mới và đọc dữ liệu JSON từ tệp
2. Chuyển đổi JSON sang JPEG bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Tải tài liệu JPEG bằng cách sử dụng lớp [Hình ảnh](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Lưu tài liệu sang định dạng TGA bằng phương pháp [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành TGA qua C#" %}}
Trong khi phân tích cú pháp JSON thành TGA, bạn cũng có thể đặt các tùy chọn bố cục cho JSON của mình bằng [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Nó cho phép bạn xử lý Mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Phân tích cú pháp Định dạng JSON thành TGA với Hình mờ" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành TGA với hình mờ trong tài liệu TGA của mình. Để thêm hình mờ, trước tiên bạn có thể kết xuất tài liệu JSON của mình thành JPEG và thêm hình mờ vào đó. Để trình diễn thao tác, bạn có thể tải hình ảnh JPEG đã chuyển đổi của mình, thêm các phép biến đổi bằng cách sử dụng một đối tượng thuộc lớp Ma trận và vẽ một chuỗi làm hình mờ trên bề mặt hình ảnh bằng cách sử dụng [Đồ họa](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) phương thức lớp '[DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) phương thức. Sau khi thêm hình mờ vào đó, bạn có thể lưu JPEG dưới dạng TGA. Dưới đây là một ví dụ mã minh họa cách thêm hình mờ đường chéo vào tài liệu của bạn. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi định dạng JSON sang PPT qua .NET
description: Phân tích cú pháp JSON thành PPT trong C# mà không cần sử dụng Microsoft PowerPoint
url_ignore: /vi/net/conversion/json-to-ppt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: PPSM POT POTM PPS OTP POWERPOINT PPTM PPT PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi định dạng JSON sang PPT qua C#" h2="C# API để phân tích cú pháp JSON thành PPT mà không cần sử dụng Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Bạn có thể chuyển đổi JSON thành PPT trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào trong hai bước đơn giản. Đầu tiên, bằng cách sử dụng [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể phân tích cú pháp JSON thành PPTX. Sau đó, bằng cách sử dụng [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), bạn có thể chuyển đổi PPTX sang PPT. Cả hai API đều nằm trong gói [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Chuyển đổi định dạng JSON sang PPT qua C#" %}}
1. Tạo một đối tượng [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) mới và đọc dữ liệu JSON hợp lệ từ tệp
2. Nhập tệp JSON vào trang tính bằng cách sử dụng lớp [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) và [Save](https://reference.aspose.com/cells/net/ aspose.cells.workbook/save/method/4) nó dưới dạng PPTX
3. Tải tài liệu PPTX bằng cách sử dụng lớp [Trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Lưu tài liệu sang định dạng PPT bằng phương pháp [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Đặt bố cục và chuyển đổi định dạng JSON thành PPT qua C#" %}}
Trong khi phân tích cú pháp JSON thành PPT, bạn cũng có thể đặt các tùy chọn bố cục cho định dạng JSON của mình bằng cách sử dụng [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Nó cho phép bạn xử lý mảng dưới dạng bảng, bỏ qua null, bỏ qua tiêu đề mảng, bỏ qua tiêu đề đối tượng, chuyển đổi chuỗi thành số hoặc ngày, đặt định dạng ngày và số, và đặt kiểu tiêu đề. Tất cả các tùy chọn này cho phép bạn trình bày dữ liệu của mình theo nhu cầu của bạn. Đoạn mã sau đây cho bạn biết cách đặt các tùy chọn bố cục.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi định dạng JSON sang PPT với Watermark" %}}
Sử dụng API, bạn cũng có thể chuyển đổi JSON thành PPT với hình mờ. Để thêm hình mờ vào tài liệu PPT của bạn, trước tiên bạn có thể phân tích cú pháp JSON thành PPTX và thêm hình mờ vào đó. Để thêm hình mờ, hãy tải tệp PPTX mới được tạo bằng cách sử dụng lớp [Bản trình bày](https://reference.aspose.com/slides/net/aspose.slides/presentation), chọn bản trình bày chính, thêm loại hình dạng bằng cách sử dụng AddAutoShape và thêm văn bản hình mờ bằng AddTextFrame. Sau khi thêm hình mờ, bạn có thể lưu tài liệu vào PPT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
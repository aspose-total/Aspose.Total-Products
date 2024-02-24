---
title: Chuyển đổi trang web HTML thành hình ảnh bằng C#
description: Quét các trang web của trang web và xuất HTML sang Hình ảnh. Phát triển các ứng dụng .NET để cạo dữ liệu trang web thành JPEG, PNG, GIF, BMP, v.v. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi các trang web thành hình ảnh thông qua C#" h2="Trích xuất dữ liệu trang web ra khỏi các trang web HTML. Chuyển đổi HTML thành hình ảnh JPG, GIF, PNG, BMP trong các ứng dụng .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Tại sao phải chuyển đổi các trang web thành hình ảnh?</h2>
<p>Chuyển đổi các trang web thành hình ảnh có thể hữu ích trong nhiều tình huống. Đó là một yêu cầu chung cho nhiều ứng dụng. Trong một số trường hợp, cần phải chụp toàn bộ trang web dưới dạng hình ảnh, bao gồm cả những phần không hiển thị trên màn hình. Điều này có thể hữu ích để tạo các bản xem trước trang web, thu thập biên lai và hóa đơn hoặc lưu trữ các trang web cho các mục đích pháp lý. Nó có thể được sử dụng để tạo ảnh chụp màn hình của các trang web cho mục đích tài liệu hoặc thử nghiệm. Nó cũng có thể được sử dụng để tạo hình thu nhỏ hoặc bản xem trước của trang web để sử dụng trong kết quả tìm kiếm hoặc phòng trưng bày hình ảnh. Cho dù bạn đang xây dựng ứng dụng máy tính để bàn hay ứng dụng web, có nhiều tùy chọn có sẵn để chuyển đổi trang web thành hình ảnh bằng C#.</p><br />

<p>Chuyển đổi các trang web thành hình ảnh bằng C# có thể mang lại một số lợi ích, bao gồm:</p><br />
<ul>
<li>Cải thiện khả năng tiếp cận: Hình ảnh có thể dễ đọc và dễ hiểu hơn đối với người khiếm thị hoặc các khuyết tật khác.</li>
<li>Tăng tính di động: Có thể dễ dàng chia sẻ hoặc nhúng hình ảnh vào các tài liệu hoặc ứng dụng khác.</li>
</ul>
<p>Chuyển đổi các trang web thành hình ảnh bằng C# cũng có thể đưa ra một số thách thức, bao gồm:</p><br />
<ul>
<li>Hỗ trợ định dạng hạn chế: Một số API hoặc công cụ có thể không hỗ trợ tất cả các định dạng hình ảnh hoặc có thể có giới hạn về kích thước hoặc độ phân giải của hình ảnh đầu ra.</li>
<li>Những vấn đề tương thích: Một số trang web có thể không hiển thị chính xác trong tất cả các trình duyệt hoặc có thể yêu cầu các cài đặt hoặc plugin cụ thể để hiển thị đúng.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Làm cách nào để chuyển đổi các trang web thành hình ảnh bằng C#?" %}}
Để chuyển đổi các trang web thành hình ảnh bằng C#, bạn có thể sử dụng API Aspose.HTML cho .NET cung cấp chức năng này để chuyển đổi các trang HTML thành định dạng hình ảnh, bao gồm JPEG, PNG và TIFF.</p>

1. Tải tài liệu HTML bằng cách sử dụng một trong các hàm tạo có sẵn trong [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Bạn có thể tải HTML từ tệp, mã HTML, luồng hoặc URL.
2. Tạo một phiên bản mới của [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) và đặt thuộc tính ImageFormat thành JPEG. Theo mặc định, thuộc tính Định dạng được đặt thành PNG.
3. sử dụng [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) phương thức từ lớp Trình chuyển đổi để lưu tài liệu HTML dưới dạng tệp JPEG. Bạn sẽ cần cung cấp HTMLDocument, ImageSaveOptions và đường dẫn tệp đầu ra làm tham số cho phương thức ConvertHTML().
4. Tệp JPEG kết quả sẽ được lưu vào đường dẫn tệp được chỉ định.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi hình ảnh và cạo trang web" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc cài đặt trực tiếp từ Package Manager Console của Visual Studio.

Hai [Aspose.Total for .NET](https://products.aspose.com/total/net/) API con, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) sẽ được tích hợp.

Ngoài ra, hãy tải trình cài đặt MSI ngoại tuyến hoặc tệp DLL trong tệp ZIP từ [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
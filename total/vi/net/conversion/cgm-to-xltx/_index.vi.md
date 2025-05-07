---
title: Chuyển đổi CGM sang XLTX thông qua API C#
description: C# API để chuyển đổi tệp CGM sang XLTX mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/cgm-to-xltx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLTX
otherformats: EXCEL TXT ODS MD FODS SXC XLSB XLTM XLT TSV DIF XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị CGM sang XLTX" h2="Xuất tệp CGM sang XLTX qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp CGM sang XLTX trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành XLTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang XLTX" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang XLSX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng XLTX bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Xltx` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang XLTX qua C#" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành XLTX mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang XLTX với Watermark qua C#" %}}
Trong khi chuyển đổi tệp CGM sang XLTX, bạn cũng có thể thêm hình mờ vào định dạng tệp XLTX đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng XLTX với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang XLTX theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM sang định dạng XLTX là cần thiết để khai thác đầy đủ được khả năng vi xử lý dữ liệu và phân tích. Đây là một quá trình quan trọng để đảm bảo bạn có thể:

**Chuyên mục sử dụng:**

*   **Hỗn hợp tác thiết kế đồ họa**: Chuyển các file CGM để chia sẻ tài nguyên thiết kế với các bên liên quan, tạo điều kiện dễ dàng合作 và đảm bảo tính nhất quán trong các yếu tố hình ảnh.

*   **Tăng cường hiệu quả trong minh họa và trình bày**: Sử dụng XLTX để thêm nội dung đa phương tiện tương tác, animation và hiệu ứng 3D vào các minh họa và trình bày, làm cho chúng trở nên hấp dẫn và hiệu quả hơn.

*   **Quản lý tài nguyên kỹ thuật số**: Chuyển các file CGM để lưu và quản lý các tài nguyên kỹ thuật số như logo, biểu tượng và hình ảnh trong một kho dữ liệu trung tâm, đảm bảo dễ dàng truy cập và cập nhật.

*   **Tạo tài liệu kỹ thuật tương tác**: Sử dụng XLTX để tạo các tài liệu kỹ thuật tương tác, bao gồm hướng dẫn người dùng, sách hướng dẫn và thông tin về sản phẩm.

*   **Tạo vật liệu quảng cáo và branding**: Chuyển các file CGM để tạo các vật liệu quảng cáo hấp dẫn, như biểu đồ thông tin, brochure và quảng cáo, kết hợp hình ảnh động và animation.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
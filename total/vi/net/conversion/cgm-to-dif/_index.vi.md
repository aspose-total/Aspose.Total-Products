---
title: Chuyển đổi CGM sang DIF thông qua API C#
description: C# API để chuyển đổi tệp CGM sang DIF mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: FODS EXCEL ODS XLT TSV MD XLTX XLSB TXT DIF XLTM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị CGM sang DIF" h2="Xuất tệp CGM sang DIF qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp CGM sang DIF trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành DIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang DIF" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang XLSX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng DIF bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Dif` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang DIF qua C#" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành DIF mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang DIF với Watermark qua C#" %}}
Trong khi chuyển đổi tệp CGM sang DIF, bạn cũng có thể thêm hình mờ vào định dạng tệp DIF đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng DIF với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang DIF theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM thành các định dạng DIF là việc cần thiết để khai thác đầy đủ được khả năng của vector graphics và capabilities illustration của bạn. Điều này cho phép bạn:

**Use Cases:**

*   **Chỉnh sửa vector graphics**: Chuyển các file CGM sang định dạng DIF để chỉnh sửa và điều khiển các vector graphics, tạo các hình dạng và đường thẳng chính xác.
*   **Thiết kế minh họa**: Sử dụng các định dạng DIF để tạo các minh họa chuyên nghiệp, với sự kiểm soát chi tiết về độ rộng tuyến, style và màu sắc.
*   **Visual hóa kiến trúc**: Chuyển các file CGM sang định dạng DIF để visual hóa các thiết kế kiến trúc, tạo các mô hình 2D và 3D, và truyền达 ý tưởng thiết kế một cách hiệu quả.
*   **Thiết kế đồ họa và in ấn**: Sử dụng các định dạng DIF để准备 vector graphics cho việc in ấn, với chất lượng in cao và đường thẳng chính xác.
*   **Kỹ thuật xây dựng (CAD)**: Chuyển các file CGM sang định dạng DIF để cải thiện các workflow CAD, tự động hóa các任务 như chuyển đổi dữ liệu và quản lý file.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
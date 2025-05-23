---
title: Chuyển đổi CGM sang SXC thông qua API C#
description: C# API để chuyển đổi tệp CGM sang SXC mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/cgm-to-sxc/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SXC
otherformats: TSV XLTX DIF ODS XLTM SXC TXT XLSM XLT EXCEL MD XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị CGM sang SXC" h2="Xuất tệp CGM sang SXC qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp CGM sang SXC trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang SXC" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang XLSX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng SXC bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Sxc` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang SXC qua C#" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành SXC mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang SXC với Watermark qua C#" %}}
Trong khi chuyển đổi tệp CGM sang SXC, bạn cũng có thể thêm hình mờ vào định dạng tệp SXC đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng SXC với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang SXC theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM thành các định dạng SXC là một quá trình cần thiết để bạn có thể khai thác được tiềm năng đầy đủ trong khả năng hiển thị dữ liệu và phân tích.

**Những trường hợp ứng dụng:**

* **Optimizing Business Operations**: Chuyển đổi các file CGM để phân tích quy trình kinh doanh, theo dõi chỉ số quan trọng (KPIs) và tìm kiếm các khu vực có thể cải thiện.
* **Phân tích tài chính và kế hoạch**: Sử dụng SXC để hiển thị dữ liệu tài chính, dự đoán xu hướng và tạo bảng điều khiển tương tác cho các bên liên quan.
* **Quản lý chuỗi cung cấp**: Chuyển đổi các file CGM để simulating cácenarios trong chuỗi cung cấp, tối ưu hóa logistics và dự đoán nhu cầu.
* **Đánh giá tác động môi trường**: Sử dụng SXC để hiển thị dữ liệu môi trường, mô phỏng các scenario và dự đoán tác động của các chính sách khác nhau.
* **Phân tích dữ liệu y tế**: Chuyển đổi các file CGM để phân tích dữ liệu bệnh nhân, theo dõi tiến trình bệnh và nhận biết các xu hướng trong kết quả y tế.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
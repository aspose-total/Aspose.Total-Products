---
title: Chuyển đổi CGM sang XLSM thông qua API C#
description: C# API để chuyển đổi tệp CGM sang XLSM mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/cgm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSM
otherformats: XLSB XLT XLTX XLSM XLAM XLTM MD TSV EXCEL TXT ODS FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị CGM sang XLSM" h2="Xuất tệp CGM sang XLSM qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp CGM sang XLSM trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang XLSM" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang XLSX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng XLSM bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Xlsm` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang XLSM qua C#" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành XLSM mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang XLSM với Watermark qua C#" %}}
Trong khi chuyển đổi tệp CGM sang XLSM, bạn cũng có thể thêm hình mờ vào định dạng tệp XLSM đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng XLSM với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang XLSM theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM (Computer Graphics Metafile) thành các định dạng XLSM (Excel Smart Document) làm cách để khai thác đầy đủ được khả năng hiển thị và phân tích dữ liệu của bạn. Đây là một quá trình chuyển đổi có thể giúp bạn:

**Ứng dụng:**

* **Thiết kế sản phẩm và prototyping**: Chuyển file CGM thành các mô hình 3D tương tác, simulating trải nghiệm người dùng và validate ý tưởng thiết kế trong Excel.
* **Khoa học và phân tích nghiên cứu**: Sử dụng XLSM để hiển thị dữ liệu khoa học phức tạp như kết quả thí nghiệm, output từ simulation và các mô hình 3D, giúp bạn hiểu rõ hơn và làm quyết định tốt hơn.
* **Bизнес thông tin và báo cáo**: Chuyển file CGM thành các bảng điều khiển tương tác, báo cáo và biểu đồ trong Excel Smart Documents để các bên tham gia có thể xem xét dễ dàng.
* **Viết báo cáo và hiển thị dữ liệu marketing**: Sử dụng XLSM để hiển thị dữ liệu về hành vi của khách hàng, theo dõi xu hướng bán hàng và nhận biết các mẫu hình trong hiệu quả của các chiến dịch marketing.
* **Khai thác dữ liệu trong thiết kế và prototyping kiến trúc/công nghiệp**: Chuyển file CGM thành các mô hình xây dựng tương tác, simulating tính chịu lực của cấu trúc và phân tích các chỉ số về hiệu suất.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Chuyển đổi CGM sang ODS thông qua API C#
description: C# API để chuyển đổi tệp CGM sang ODS mà không cần sử dụng Microsoft Excel hoặc Adobe Reader
url_ignore: /vi/net/conversion/cgm-to-ods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODS
otherformats: SXC XLT XLAM XLTM XLSB EXCEL ODS TXT XLSM TSV FODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# để hiển thị CGM sang ODS" h2="Xuất tệp CGM sang ODS qua C# mà không sử dụng Microsoft<sup>&reg;</sup> Excel hoặc Adobe <sup> & reg; </sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sử dụng [Aspose.Total for .NET](https://products.aspose.com/total/net/), bạn có thể dễ dàng chuyển đổi tệp CGM sang ODS trong bất kỳ ứng dụng .NET, C#, ASP.NET và VB.NET nào. Đầu tiên, bằng cách sử dụng [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), bạn có thể xuất CGM sang XLSX. Sau đó, bằng cách sử dụng API lập trình bảng tính [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), bạn có thể chuyển đổi XLSX thành ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API để chuyển đổi CGM sang ODS" %}}
1. Mở tệp CGM bằng lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Chuyển đổi CGM sang XLSX bằng phương pháp [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Tải tài liệu XLSX bằng cách sử dụng lớp [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Lưu tài liệu sang định dạng ODS bằng phương pháp [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) và đặt `Ods` làm SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu chuyển đổi" %}}
Cài đặt từ dòng lệnh dưới dạng ```nuget install Aspose.Total``` hoặc thông qua Package Manager Console của Visual Studio với ```Install-Package Aspose.Total```.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi CGM được bảo vệ sang ODS qua C#" %}}
Nếu tài liệu CGM của bạn được bảo vệ bằng mật khẩu, bạn không thể chuyển đổi nó thành ODS mà không có mật khẩu. Sử dụng API, trước tiên bạn có thể mở tài liệu được bảo vệ bằng mật khẩu hợp lệ và chuyển đổi sau đó. Để mở tệp được mã hóa, bạn có thể khởi tạo phiên bản mới của lớp [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) và chuyển tên tệp và mật khẩu làm đối số.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang ODS với Watermark qua C#" %}}
Trong khi chuyển đổi tệp CGM sang ODS, bạn cũng có thể thêm hình mờ vào định dạng tệp ODS đầu ra của mình. Để thêm hình mờ, bạn có thể tạo một đối tượng Workbook mới và mở tài liệu XLSX đã chuyển đổi, chọn Trang tính thông qua chỉ mục của nó, tạo Hình dạng và sử dụng chức năng AddTextEffect của nó. Sau đó, bạn có thể lưu tài liệu XLSX của mình dưới dạng ODS với Hình mờ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi tệp CGM sang ODS theo chương trình: Các trường hợp sử dụng" %}}
Chuyển đổi các file CGM (Computer Graphics Metafile) thành các định dạng ODS (OpenDocument Spreadsheet) là việc cần thiết để khai thác được đầy đủ khả năng hiển thị và phân tích dữ liệu của bạn. Việc này cho phép bạn:

**Ứng dụng:**

*   **Phân tích thông tin doanh nghiệp**: Chuyển file CGM để phân tích hiệu quả làm việc, theo dõi các chỉ số quan trọng và nhận biết các xu hướng trong dữ liệu.
*   **Kiểm tra chất lượng dữ liệu**: Sử dụng ODS để kiểm tra độ nguyên tắc của dữ liệu, phát hiện lỗi và đảm bảo tính nhất quán giữa các bộ dữ liệu khác nhau.
*   **Phân tích nghiên cứu thị trường**: Chuyển file CGM để phân tích xu hướng thị trường, hành vi của khách hàng và hoạt động của đối thủ.
*   **Optimizing hiệu quả làm việc**: Sử dụng ODS để tối ưu quá trình làm việc, nhận biết các lĩnh vực cần cải thiện và đo lường tác động của thay đổi.
*   **Lập kế hoạch tài chính và báo cáo**: Chuyển file CGM để tạo các mô hình tài chính, dự đoán doanh thu và跟踪 chi phí.

Việc chuyển đổi file CGM thành các định dạng ODS cũng cho phép bạn tận dụng các tính năng mạnh mẽ của ODS, như:

*   Format dữ liệu điều kiện
*   Bảng động
*   Kiểm tra dữ liệu
*   Công cụ hợp tác

Bằng việc chuyển đổi các file CGM thành ODS, bạn có thể unlock một loạt lợi ích, bao gồm độ chính xác cao hơn trong dữ liệu, cải thiện hợp tác và những hiểu biết doanh nghiệp tốt hơn.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}